---
id: spring-boot-migration-task
name: Spring Boot 2.x to 3.x Migration
type: task
---

**Prompt:**

Migrate a Spring Boot 2.x application to Spring Boot 3.x by following these steps:

## Analysis Phase

1. **Identify Current Version**
   - Check the `pom.xml` or `build.gradle` file
   - Note the current Spring Boot version
   - List all Spring dependencies

2. **Check for Deprecated APIs**
   - Review code for deprecated Spring Boot 2.x APIs
   - Identify usage of removed features
   - Note any third-party dependencies that may need updates

## Migration Steps

3. **Update Dependencies**
   - Update Spring Boot version to 3.x in build file
   - Update all Spring Framework dependencies
   - Update Jakarta EE dependencies (javax → jakarta namespace)

4. **Code Changes**
   - Replace `javax.*` imports with `jakarta.*`
   - Update security configuration for Spring Security 6
   - Modify any deprecated method calls
   - Update configuration properties

5. **Testing**
   - Run all unit tests
   - Run integration tests
   - Verify application starts successfully
   - Check for runtime warnings

## Key Considerations

- **Java Version**: Spring Boot 3 requires Java 17 or later
- **Jakarta EE**: The javax to jakarta namespace change is mandatory
- **Spring Security**: Configuration has changed significantly
- **Deprecations**: Review Spring Boot 3 release notes for removed features

## Output Format

Provide:
- A detailed migration plan with step-by-step instructions
- List of code changes required with file paths
- Updated dependency versions
- Testing checklist
