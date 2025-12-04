---
id: microservices-refactoring-task
name: Monolith to Microservices Refactoring
type: task
---

**Prompt:**

Refactor a monolithic Java application into microservices architecture following domain-driven design principles.

## Analysis Phase

1. **Domain Modeling**
   - Identify business domains and bounded contexts
   - Map current application modules to domains
   - Define service boundaries
   - Identify shared data and dependencies

2. **Architecture Assessment**
   - Analyze current code structure
   - Identify tight coupling and dependencies
   - Review database schema and data access patterns
   - List cross-cutting concerns

## Refactoring Strategy

3. **Service Decomposition**
   - Define microservice boundaries
   - Create service APIs and contracts
   - Design inter-service communication (REST, messaging)
   - Plan data migration and decomposition

4. **Implementation Plan**
   - Extract services incrementally (strangler pattern)
   - Implement API gateway
   - Set up service discovery and configuration
   - Add distributed tracing and monitoring

5. **Data Management**
   - Decompose database schema
   - Implement database per service pattern
   - Handle distributed transactions (Saga pattern)
   - Set up event-driven architecture

## Key Considerations

- **Service Size**: Keep services focused and cohesive
- **Communication**: Choose sync vs async carefully
- **Data Consistency**: Plan for eventual consistency
- **Testing**: Implement contract testing
- **Deployment**: Set up CI/CD for each service

## Output Format

Provide:
- Service decomposition diagram
- API specifications for each service
- Data migration strategy
- Step-by-step refactoring plan
- Code structure for new services
- Testing and deployment strategy
