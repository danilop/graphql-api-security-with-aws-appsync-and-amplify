Authentication and Authorization
================================

Possible ways to authenticate and authorize access to GraphQL APIs managed by AppSync:
- API keys
- Amazon Cognito user pool
- OpenID Connect provider
- AWS Identity and Access Management (IAM) permissions

How to add/manage authentication and authorization:
- amplify add auth
- amplify import auth # Import an existing Cognito user pool
- amplify update auth

Other things to consider:
- Admin queries API
- Lambda Triggers for Cognito
- Multifactor authentication (MFA) user login 

Amplify API (GraphQL) Setup authorization rules
https://docs.amplify.aws/cli/graphql-transformer/auth

GraphQL API Security with AWS AppSync and Amplify
https://aws.amazon.com/blogs/mobile/graphql-security-appsync-amplify/

Using Auth0 as an Identity Provider for GraphQL APIs with AWS AppSync
https://aws.amazon.com/blogs/mobile/appsync-auth0/