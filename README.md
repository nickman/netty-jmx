netty-jmx
=========

JMX management classes for Netty and a Netty based JMXConnectionServer and Client supporting an asynchronous JMX API.

To Do:
=========
  - Providers and service META-INF entries
  - Standard MBeanServer Ops  (Synchronous)
  - Define asynch API
  - Implement client and server asynch api.
  - Custom serializers
  - ChannelFactory and Pipelines for 
    - Client
    - Server
  - Client side notification listener
  - Load test and perf comparison to RMI
  - Security ?
  - Environment:
    - notification listener port
    - compression option
    - credentials
  - Transports
    - TCP
    - [UDP]
    - Local
    - [WebSockets]
    - HTTP Tunneling