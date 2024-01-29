1. Create a directory for project and initialize go modules file

`go mod init github.com/[username]/hackernews`

2. Setup the project using the graphql template

`go run github.com/99designs/gqlgen init`

3. Define schema in `graph/schema.graphqls`

4. Regenerate files based on the schema

`go run github.com/99designs/gqlgen generate`

5. Implement the resolvers in `schema.resolvers.go`

6. Start the server

`go run server.go`

7. Access Graphiql at http://localhost:8080
