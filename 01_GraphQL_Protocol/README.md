GraphQL Protocol
================

GraphQL Schema
------

To start, see blog.graphql

GraphQL Operations
----------

To operate on data, you need to define operations: queries, mutations, subscriptions.

Client -> GraphQL Endpoint -> Resolvers -> Data Source

Resolvers can become a bottleneck for DoD attacks.

Avoid complex operations on data source for common APIs, for example avoid DynamoDB scans.

GraphQL Transform
-----------------

To simplify adding operations to a GraphQL schema, you can use:

GraphQL Schema Definition Language (SDL) -> AWS CloudFormation templates

With Amplify:
- amplify add api
- amplify update api
- amplify api gql-compile
