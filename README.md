# Cassandra Docker

## Start Cassandra
`
docker-compose up -d --build
`

## Stop Cassandra
`
docker-compose down
`

## Connect to Cassandra
`
docker exec -it ttscassandra cqlsh
`

## Terminal to Cassandra
`
docker exec -it ttscassandra bash
`

## Connect from Dev Center
`
127.0.0.1:9042
`

<br/>
<hr/>
<br/>

> If needed: `route /P add 172.100.100.0 MASK 255.255.255.0 10.0.75.0`

