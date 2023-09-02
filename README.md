# graphqa-rest
http://localhost:8080/graphiql?path=/graphql

Run below query
query abc {
  bookById(id:"book-1") {
    id
    name
  }
}
It should return all books.
add different query in schema file and play around.
