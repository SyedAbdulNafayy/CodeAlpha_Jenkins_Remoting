# CodeAlpha Jenkins Remoting
Overview
This project demonstrates Jenkins Remoting by connecting a Linux remote agent to a Jenkins controller.

Tools Used
Jenkins 2.580.2
Ubuntu 22.04 LTS
Java OpenJDK 21
Jenkins WebSocket Agent
Implementation
Created a Jenkins node named CodeAlpha-Agent.
Configured the node with a remote workspace.
Connected the Ubuntu agent using Jenkins agent JAR and WebSocket.
Created a Freestyle job named CodeAlpha-Remote-Build.
Configured shell commands to execute on the remote agent.
Verification
The remote build successfully displayed:

Hello from CodeAlpha Remote Agent!
Hostname
Operating System
Current User
Build Result: SUCCESS

Conclusion
Successfully configured Jenkins Remoting and executed a build on a connected remote Linux agent. Jenkins Remoting with a connected Linux agent and remote build execution

Project Screenshots
1. Jenkins Agent Connection
Agent Connection

2. Remote Build Console Output
Console Output

3. Additional Build Console Output
Additional Console Output
