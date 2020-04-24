# OVERVIEW
An example of graphQL with Java and spring boot.  
From: https://www.graphql-java.com/tutorials/getting-started-with-spring-boot/

## RUN
* Download GraphQL Playground  
`$ brew cask install graphql-playground`
* Run BookDetailsApplication.java
* Open GraphQL Playground: After starting it you will be asked for a URL, enter http://localhost:8080/graphql.
* Try it!  
For example: `{
                          bookById(id: "book-1"){
                            id
                            name
                            pageCount
                            author {
                              firstName
                              lastName
                            }
                          }
                        }`
