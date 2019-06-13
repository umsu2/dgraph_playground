# dgraph_playground
playing around with dgraph



* to load the db with zipped data run the following command 
`docker exec -it dgraph_playground_zero_1 dgraph live -r 1million.rdf.gz --zero localhost:5080 -d server:9080`
