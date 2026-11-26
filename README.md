# # CodeAlpha Jenkins Remoting

## Overview
This project demonstrates Jenkins Remoting by connecting a Linux remote agent to a Jenkins controller.

## Tools Used
- Jenkins 2.580.2
- Ubuntu 22.04 LTS
- Java OpenJDK 21
- Jenkins WebSocket Agent

## Implementation
1. Created a Jenkins node named `CodeAlpha-Agent`.
2. Configured the node with a remote workspace.
3. Connected the Ubuntu agent using Jenkins agent JAR and WebSocket.
4. Created a Freestyle job named `CodeAlpha-Remote-Build`.
5. Configured shell commands to execute on the remote agent.

## Verification
The remote build successfully displayed:
- Hello from CodeAlpha Remote Agent!
- Hostname
- Operating System
- Current User

**Build Result: SUCCESS**

## Conclusion
Successfully configured Jenkins Remoting and executed a build on a connected remote Linux agent.
Jenkins Remoting with a connected Linux agent and remote build execution

## Project Screenshots

### 1. Jenkins Agent Connection
![Agent Connection](Status%20check.png)

### 2. Remote Build Console Output
![Console Output](Console%20Output.png)

### 3. Additional Build Console Output
![Additional Console Output](Console%20Output%20%232.png)
