# Jenkins_dynamic_slaves
Step by step configuration for cloud based jenkins master and dynamic slave containers.

Below configuration gives insight in to a Jenkins master which is running on container and spin up slave container as agent for executing a job in remote Docker host. The ephemeral model aims to leverage the autonomous and isolated nature of Docker containers to scale a Jenkins build farm to meet any demand placed upon it. Instead of the traditional array of pre-allocated slaves or at-the-ready virtual machines, this model treats the entire container itself as a slave.
