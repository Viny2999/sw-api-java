# Star WarsAPI

A Simple Star Wars Java API using Spring.

# Instruction
Run `gradle bootRun` to start

# Endpoints
Get all planets: `GET localhost:8080/planets`

Search by INDEX: `GET localhost:8080/planets/<INDEX>`

Search by Name: `GET localhost:8080/planets/name/<NAME>`

Post a planet: `POST localhost:8080/planets`

Delete a planet: `DELETE localhost:8080/planets/<INDEX>`

# Example of body to create planet
{	
	"name": "name",
	"climate": "unknown",
	"terrain": "unknown"
}
