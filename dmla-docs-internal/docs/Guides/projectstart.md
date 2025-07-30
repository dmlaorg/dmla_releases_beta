# Getting started with the DMLA3.1 project
WIP
This guide summarizes the procedure of importing/building the DMLA Kotlin project.

The guide assumes the use of IntelliJ IDEA, but the project may be developed/built with a different IDE as well.

## Prerequisites

* GraalVM 23+ is required. 
* Gradle 8+ should be installed within IntelliJ or globally

The project was developed using IntelliJ IDEA 2025.1.1.1, earlier versions may have _(even more)_ issues with Kotlin KSP. I recommend the [JetBrains Toolbox App](https://www.jetbrains.com/toolbox-app/) for updating IDEA to the latest version without a hassle.

The Gradle project should take care of any additional requirements (including building the Dokka plugin).

`org.dmla` Package prefixes will be added using Gradle later on, it is safe to ignore all related warnings!