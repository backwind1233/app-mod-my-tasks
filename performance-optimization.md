---
id: performance-optimization-task
name: Java Application Performance Optimization
type: task
---

**Prompt:**

Analyze and optimize the performance of a Java application by identifying bottlenecks and implementing improvements.

## Analysis Phase

1. **Performance Profiling**
   - Run application profiler (JProfiler, YourKit, VisualVM)
   - Identify CPU hotspots and memory leaks
   - Analyze database query performance
   - Review thread utilization and concurrency

2. **Metrics Collection**
   - Measure response times and throughput
   - Monitor JVM heap and garbage collection
   - Track database connection pool usage
   - Analyze external API call latencies

## Optimization Strategies

3. **Code Optimization**
   - Optimize algorithms and data structures
   - Reduce object creation and GC pressure
   - Implement caching where appropriate
   - Use parallel processing for CPU-bound tasks

4. **Database Optimization**
   - Add appropriate indexes
   - Optimize slow queries
   - Implement connection pooling
   - Use batch operations where possible
   - Consider read replicas for scalability

5. **Infrastructure Improvements**
   - Tune JVM parameters (heap size, GC settings)
   - Configure thread pools appropriately
   - Implement caching layers (Redis, Caffeine)
   - Set up CDN for static content

## Key Considerations

- **Measurement**: Always measure before and after changes
- **Trade-offs**: Balance memory vs CPU, latency vs throughput
- **Scalability**: Consider horizontal vs vertical scaling
- **Caching**: Implement cache invalidation strategy

## Output Format

Provide:
- Performance analysis report with metrics
- Identified bottlenecks and root causes
- Prioritized optimization recommendations
- Code changes with performance impact
- JVM tuning parameters
- Before/after performance comparison
