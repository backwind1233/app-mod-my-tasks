---
id: azure-migration-task
name: Migrate Java Application to Azure
type: task
---

**Prompt:**

Migrate a Java application to Azure by analyzing the current architecture and creating an Azure deployment plan.

## Analysis Phase

1. **Application Assessment**
   - Identify application type (Spring Boot, Jakarta EE, standalone, etc.)
   - Review current infrastructure and dependencies
   - Identify database and storage requirements
   - List external service integrations

2. **Azure Service Selection**
   - Choose appropriate Azure compute service (App Service, AKS, Container Apps, etc.)
   - Select Azure database service (Azure SQL, PostgreSQL, MySQL, Cosmos DB)
   - Identify required Azure services (Key Vault, Storage, Service Bus, etc.)

## Migration Planning

3. **Architecture Design**
   - Design Azure architecture diagram
   - Define network topology and security groups
   - Plan for high availability and disaster recovery
   - Determine scaling strategy

4. **Code Modifications**
   - Update configuration for Azure services
   - Implement Azure SDK integrations
   - Add Azure authentication and authorization
   - Configure application insights and monitoring

5. **Deployment Strategy**
   - Choose deployment method (Azure DevOps, GitHub Actions, Azure CLI)
   - Create deployment pipelines
   - Set up staging and production environments
   - Plan for blue-green or canary deployments

## Key Considerations

- **Cost Optimization**: Select appropriate service tiers
- **Security**: Implement Azure Key Vault, Managed Identity
- **Monitoring**: Set up Application Insights and Log Analytics
- **Compliance**: Ensure data residency and compliance requirements

## Output Format

Provide:
- Azure architecture diagram (Markdown/ASCII)
- Service selection justification
- Step-by-step migration guide
- Required code changes with examples
- Deployment pipeline configuration
- Cost estimation and optimization tips
