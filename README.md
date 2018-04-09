A basic way to make bidirectional graphql schema on top of json data hosted by json-server and queried by graphiql

Schema:

Company{
    id,
    name,
    description,
    users{
        id,
        firstName,
        age,
        companyId
    }
}

User{
    id,
    firstName,
    age,
    companies{
        id,
        name,
        description
    }
}

And Mutation:
Add User
Delete User
Edit User

Run On
    localhost:4000/graphql



