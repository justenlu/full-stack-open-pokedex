# Exercise 11.1 Warming up

Let's assume that a team of about 6 people is developing a Java application and there isn't any special hardware requirements involved. What tools they could use for CI?

## Tools for linting, testing and building

For linting Java code [CheckStyle](https://checkstyle.org/) or [PMD](https://pmd.github.io/) can be used in CI pipeline. 

For testing there are [JUnit](https://junit.org) and [TestNG](https://testng.org/). JUnit is for unit testing, TestNG is capable of handling both unit, functional, end-to-end and integration tests.

For building there are for example [Apache Ant](https://ant.apache.org/), [Apache Maven](https://maven.apache.org/) and [Gradle](https://gradle.org/). To build a Java application, compiler must be used also. For that there are javac and javac OpenJDK compilers from Sun Microsystems. 

## Alternative tools to set CI

Wikipedia has an article [Comparison of continuous integration software](https://en.wikipedia.org/wiki/Comparison_of_continuous_integration_software) that 29.5.2024 lists eighteen different tools: Apache Gump, AppVeyor, Azure DevOps Server, Bamboo, Buddy, Buidbot, BuildMaster, CircleCI, GitLab, GoCD, Jenkins, OpenMake Software Meister, Semaphore, Travis CI, TeamCity, Vexor, Buildkite and Tekton. 

## Seld-hosted or cloud-based environment?

Cloud-based environment is probably the way to go because the team in our hypothetical situation is so small and there is no special hardware requirements. This way no money is spent to hardware running CI server and no time is spent configuring the server software.