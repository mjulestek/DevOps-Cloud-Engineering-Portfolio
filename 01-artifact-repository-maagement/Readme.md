
# 📦 Artifact Repository Management with Nexus

## Overview

This project demonstrates setting up a centralized artifact repository using Nexus and integrating it with Java build tools to manage and publish application artifacts.

Nexus is deployed on an AWS EC2 instance and used as the single source for storing and distributing build outputs.

---

## Architecture

![Architecture](diagrams/architecture.png)

---

## Implementation

* Provisioned an EC2 instance and configured secure access (SSH, restricted IP)
* Installed and configured Nexus Repository Manager
* Created repositories and managed access permissions
* Built Java applications using:

  * Gradle
  * Maven
* Published JAR artifacts to Nexus repositories

---

## Workflow

```text
Build → Package → Publish → Store → Retrieve
```

---

## Tech Stack

* Nexus Repository Manager
* AWS EC2
* Linux
* Java
* Gradle
* Maven

---

## Outcome

Established a working artifact management system that integrates build tools with a centralized repository, enabling consistent and reliable artifact storage and distribution.
