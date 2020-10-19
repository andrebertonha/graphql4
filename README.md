#GRAPHQL project

+ download the project

    - run npm install to install project dependencies
    - run the project with: node index.js
    - the project should be running on the localhost
    - execute the browser to use graphql queries in the host:  http://localhost:3000/graphql

+ Graphql queries examples

    # register user
    - mutation {
        createUser(
            name: "André Martins 2",
            repo: "https://github.com/andrebertonha/netninja-nodejs",
            age: 34    
        ) {
            id
        }
    }

    # list 
        {
           users {
              name
              repo
           }
        }


