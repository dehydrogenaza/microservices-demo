This is a simple playground for learning Spring Cloud.

The goal is to create a REST API for creating random NPCs for use in tabletop role-playing games

Uses:
- Netflix Eureka
- OpenFeign

Microservices:
- Discovery: Eureka Server (registry)
- NPC Generator API: web API providing random NPCs for use in RPG campaigns; uses a separate microservice to get random names
- Random Names API: returns random names (NPCs, locations) from a database