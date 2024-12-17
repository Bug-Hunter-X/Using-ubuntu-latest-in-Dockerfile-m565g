This repository contains an example of a Dockerfile that uses the `ubuntu:latest` tag, which is not a recommended practice because it can cause inconsistencies in builds. This can lead to unexpected behavior and makes the container harder to reproduce. 

The `Dockerfile_fixed` shows how to fix the problem by specifying a specific version of Ubuntu.