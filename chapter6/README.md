# Chapter 6 readme

This chapter is all about monitoring and logging of ML project

## Critical Thinking Discussion Questions

### Why might it be desirable to log to multiple sources at the same time?

It might be desirable to log to multiple sources at the same time for redundancy and fault tolerance. If one of the logging sources fails or becomes unavailable, the other sources can still capture and store the log data. This ensures that essential information is not lost and allows for easier troubleshooting and analysis.

### Why is it critical to monitor data drift?

It is critical to monitor data drift because it helps in ensuring data quality and accuracy over time. Data drift refers to the gradual and unexpected changes in the statistical properties of data, which can occur due to various factors. By monitoring data drift, organizations can identify and address potential data issues, such as changes in data sources, data schema changes, or data corruption, before they lead to significant problems or inaccuracies in analysis or decision-making processes.

### Name three advantages of using logging facilities versus print() or echo statements.

Three advantages of using logging facilities over print() or echo statements are:

- Flexibility and configurability: Logging facilities provide various configuration options, allowing the developer to define log levels, log messages, log formats, and destination sources. This flexibility enables efficient troubleshooting, debugging, and analysis of log information based on specific requirements.
- Scalability: Logging facilities are designed to handle a large volume of log messages efficiently. They can manage logging for complex systems, distributed applications, or multiple threads, providing better scalability compared to simple print() or echo statements.
- Performance and maintenance: Logging facilities are typically optimized for performance and minimize the impact on system resources. They allow for efficient log storage, retrieval, and analysis. Additionally, using a dedicated logging framework or library helps in maintaining a standardized approach to logging across the codebase and simplifies maintenance tasks.

### List the five most common log levels, from least to most verbose.

The five most common log levels, from least to most verbose, are:

- DEBUG: Detailed information, typically used for troubleshooting and debugging during development.
- INFO: General information about the program's execution, such as startup messages, important events, or milestones.
- WARNING: Indication of potential issues or situations that might lead to problems but do not immediately impact the program's functionality.
- ERROR: Indicates errors or exceptions that prevent the program from continuing an operation or performing as intended.
- CRITICAL: The most severe level, indicates critical errors or failures that could lead to system crashes, data loss, or significant disruptions.

### What are three common metric types found in metric-capturing systems?

Three common metric types found in metric-capturing systems are:

- Counter: Represents a numeric value that continuously increases over time. Counters are useful for monitoring and measuring the frequency of events, like the number of requests, the number of errors, or the number of processed records.
- Gauge: Represents a specific value at a particular moment in time. Gauges are useful for measuring instantaneous states or levels, such as current memory usage, CPU load, or network latency.
- Timer: Measures the time taken to perform a specific operation or task. Timers are useful to track the duration of operations and identify potential performance bottlenecks or improvements. They can provide statistical information like minimum, maximum, average, or percentile values for the measured times.
