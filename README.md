# Amazon App Runner (amazon-app-runner)
AWS App Runner is a fully managed container application service that lets you build, deploy, and run containerized web applications and API services without prior infrastructure or container experience. Start with your source code or a container image.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-app-runner/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, CI/CD, Containers, Deployment, Managed Service, Serverless, Web Applications

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon App Runner API
The AWS App Runner API enables programmatic management of App Runner services, including creating and managing services, auto scaling configurations, custom domains, VPC connectors, and observability configurations for containerized web applications.

**Human URL:** [https://aws.amazon.com/apprunner/](https://aws.amazon.com/apprunner/)

#### Tags:

 - Containers, Deployment, Serverless, Web Applications

#### Properties

- [Documentation](https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html)
- [OpenAPI](openapi/amazon-app-runner-openapi.yaml)
- [Pricing](https://aws.amazon.com/apprunner/pricing/)
- [Getting Started](https://aws.amazon.com/apprunner/getting-started/)
- [FAQ](https://aws.amazon.com/apprunner/faqs/)
- [User Guide](https://docs.aws.amazon.com/apprunner/latest/dg/what-is-apprunner.html)
- [API Reference](https://docs.aws.amazon.com/apprunner/latest/api/Welcome.html)
- [CLI Reference](https://docs.aws.amazon.com/cli/latest/reference/apprunner/)
- [Security](https://docs.aws.amazon.com/apprunner/latest/dg/security.html)
- [JSONSchema](json-schema/amazon-app-runner-apprunnerresourcearn-schema.json)
- [JSONSchema](json-schema/amazon-app-runner-asconfigmaxconcurrency-schema.json)
- [JSONSchema](json-schema/amazon-app-runner-asconfigmaxsize-schema.json)
- [JSONSchema](json-schema/amazon-app-runner-asconfigminsize-schema.json)
- [JSONSchema](json-schema/amazon-app-runner-associatecustomdomainrequest-schema.json)
- [JSONStructure](json-structure/amazon-app-runner-apprunnerresourcearn-structure.json)
- [JSONStructure](json-structure/amazon-app-runner-asconfigmaxconcurrency-structure.json)
- [JSONStructure](json-structure/amazon-app-runner-asconfigmaxsize-structure.json)
- [JSONLD](json-ld/amazon-app-runner-context.jsonld)

## Common Properties

- [Portal](https://console.aws.amazon.com/)
- [Website](https://aws.amazon.com/apprunner/)
- [Documentation](https://docs.aws.amazon.com/apprunner/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/containers/category/compute/aws-app-runner/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/apprunner)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [Service Status](https://status.aws.amazon.com/)
- [Knowledge Center](https://repost.aws/knowledge-center)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/aws-app-runner)
- [Contact](https://aws.amazon.com/contact-us/)
- [Security](https://aws.amazon.com/security/)
- [Compliance](https://aws.amazon.com/compliance/)
- [SpectralRules](rules/amazon-app-runner-spectral-rules.yml)
- [NaftikoCapability](capabilities/app-runner-management.yaml)
- [Vocabulary](vocabulary/amazon-app-runner-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Service Management | Create, update, and delete App Runner services that deploy containerized or source-code-based web applications without managing infrastructure. |
| Auto Scaling Configuration | Configure auto scaling policies to automatically scale App Runner services in and out based on traffic demand. |
| Custom Domain Support | Associate custom domains with App Runner services for branded URLs with automatic SSL certificate provisioning. |
| VPC Connector Integration | Connect App Runner services to VPC resources using VPC connectors for secure access to databases and internal services. |
| Deployment Automation | Configure automatic deployments triggered by source code changes or image push events for continuous delivery. |

## Use Cases

| Name | Description |
|------|-------------|
| Containerized API Deployment | Deploy REST APIs and microservices as containers on App Runner with automatic scaling and zero infrastructure management. |
| Web Application Hosting | Host web applications built from source code or container images with built-in load balancing and HTTPS. |
| CI/CD Integration | Integrate App Runner with CI/CD pipelines for automated service deployments triggered by repository changes. |
| Startup Companies | Quickly launch and scale web backends without DevOps expertise using App Runner managed infrastructure. |

## Integrations

| Name | Description |
|------|-------------|
| AWS ECR | Deploy App Runner services directly from container images stored in Amazon ECR with automatic image updates. |
| AWS CodeBuild | Use CodeBuild for source code building and integrate with App Runner for automated deployment pipelines. |
| Amazon RDS | Connect App Runner services to RDS databases using VPC connectors for secure private network access. |
| AWS CloudWatch | Monitor App Runner service metrics, request counts, and latency using CloudWatch dashboards and alarms. |

## Artifacts

### OpenAPI

- [Amazon App Runner API OpenAPI](openapi/amazon-app-runner-openapi.yaml)

### JSON Schema (180 files)

- [amazon-app-runner-apprunnerresourcearn-schema.json](json-schema/amazon-app-runner-apprunnerresourcearn-schema.json)
- [amazon-app-runner-asconfigmaxconcurrency-schema.json](json-schema/amazon-app-runner-asconfigmaxconcurrency-schema.json)
- [amazon-app-runner-asconfigmaxsize-schema.json](json-schema/amazon-app-runner-asconfigmaxsize-schema.json)
- [amazon-app-runner-asconfigminsize-schema.json](json-schema/amazon-app-runner-asconfigminsize-schema.json)
- [amazon-app-runner-associatecustomdomainrequest-schema.json](json-schema/amazon-app-runner-associatecustomdomainrequest-schema.json)
- [amazon-app-runner-associatecustomdomainresponse-schema.json](json-schema/amazon-app-runner-associatecustomdomainresponse-schema.json)
- [amazon-app-runner-authenticationconfiguration-schema.json](json-schema/amazon-app-runner-authenticationconfiguration-schema.json)
- [amazon-app-runner-autoscalingconfiguration-schema.json](json-schema/amazon-app-runner-autoscalingconfiguration-schema.json)
- [amazon-app-runner-autoscalingconfigurationname-schema.json](json-schema/amazon-app-runner-autoscalingconfigurationname-schema.json)
- [amazon-app-runner-autoscalingconfigurationstatus-schema.json](json-schema/amazon-app-runner-autoscalingconfigurationstatus-schema.json)
- ... and 170 more

## Capabilities

- [Amazon App Runner API](capabilities/shared/amazon-app-runner.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [App Runner Management](capabilities/app-runner-management.yaml) | Amazon App Runner API | 1 | Backend Developer, DevOps Engineer |

## Vocabulary

- [Amazon App Runner API Vocabulary](vocabulary/amazon-app-runner-vocabulary.yaml)

## Rules

- [Amazon App Runner API Spectral Rules](rules/amazon-app-runner-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
