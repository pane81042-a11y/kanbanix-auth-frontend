# Kanbanix Auth Frontend

Kanbanix Auth Frontend is the centralized authentication microfrontend for the Kanbanix platform.

It integrates with Amazon Cognito for secure user authentication and session management.

## Features

- User registration
- User login
- JWT token retrieval
- Session validation
- Logout functionality
- Secure token storage
- Protected route integration

## Architecture

Built with:

- React
- Amazon Cognito (User Pools)
- AWS Amplify or Cognito SDK
- Webpack Module Federation
- Shared UI library components

This microfrontend is loaded dynamically by the Kanbanix Shell and provides authentication context across the platform.

## AWS Always Free Tier Deployment

Authentication is fully serverless:

Frontend:
- Amazon S3 (static hosting)
- Amazon CloudFront (CDN delivery)

Backend Authentication:
- Amazon Cognito User Pools
- Cognito JWT authorization for API Gateway

CI/CD:
- GitHub Actions for automated deployment

## Security Model

- JWT based authentication
- API Gateway secured with Cognito Authorizer
- Role based access control support
- Secure user scoped operations

## Scalability

- Fully managed authentication
- No custom auth server required
- Independent deployment
- Production ready security architecture

## Portfolio Value

Demonstrates:

- Enterprise authentication architecture
- Serverless security model
- Cognito JWT integration
- Microfrontend based auth isolation
