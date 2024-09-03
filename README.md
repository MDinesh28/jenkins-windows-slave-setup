# Setting Up a Windows Slave for Jenkins

## Overview
This guide will walk you through the steps to set up a Windows slave for Jenkins, including enabling JNLP agents, connecting the slave, and installing Maven.

## Prerequisites
- Jenkins Master Server
- Windows Machine with Admin Access

## Steps

### 1. Enable TCP Port for JNLP Agents in Jenkins
- Navigate to `Manage Jenkins > Configure Global Security`.
- Enable the TCP port for JNLP agents.
- Note down the port number for use in the next steps.
  
### 2. Connect the Windows Slave
- Create a folder on your Windows machine, e.g., `C:\jenkins-agent`.
- Open Command Prompt as Administrator in this folder.
- Run the commands provided by Jenkins to start the agent.

### 3. Install and Configure Maven on Windows
- Download the Maven Binary from the official [Maven website](https://maven.apache.org/download.cgi).
- Extract the archive to `C:\maven`.
- Set up environment variables for `M2_HOME` and `MAVEN_HOME`.
- Add Maven to your system's PATH.

## Screenshots


