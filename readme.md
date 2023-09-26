# LOA Webserver

## Description

Webserver to provide REST API for my Life Organizer App.  

## Planned features

- [ ] User management
- [ ] Note keeping
- [ ] Todo tracking
- [ ] Habit tracking

## Libraries and Tools used in this project

### Main crates used

- [axum](https://crates.io/crates/axum) to create the server
- [tokio](https://crates.io/crates/tokio) for async support
- [serde](https://crates.io/crates/serde) for serializing and deserializing data
- [sqlx](https://crates.io/crates/sqlx) for querying the mysql based database
- [argon2](https://crates.io/crates/argon2) for hashing passwords
- [tracing](https://crates.io/crates/tracing) and [color-eyre](https://crates.io/crates/color-eyre) for good logging
- [axum-swagger-ui](https://crates.io/crates/axum-swagger-ui) for providing code to use OpenApi tools

### Tools

- OpenApi for defining REST API endpoints
- Docker for facilitating platform independent deployments

## To-Do

### General To-Do

Rough general todos for this project
Do this but not necessarily in order

- [ ] Planning (do for each feature)
	- [ ] Plan database layout and corresponding structs
	- [ ] Implement OpenAPI stuff to define REST API endpoints
	- [ ] Create dummy data
	- [ ] Write tests for these endpoints
- [ ] Implementation (do for each feature)
	- [ ] Create structs and enums to express the state of each feature hidden behind the API endoints
	- [ ] Implement the code around these structs and enums
- [ ] Add dockerfile to containerize this application
	- The application doesn't have to be done yet does not have to be working at this moment
- [ ] Create docker composer file to connect to database

### Per Feature To-Do

- [ ] General To-Do

#### User Management

- [ ] General To-Do

#### Note Keeping

- [ ] General To-Do

#### To-Do List

- [ ] General To-Do

#### Habit Tracking

- [ ] General To-Do