---
description: Containerize Go apps using Docker
keywords: docker, getting started, go, golang, language, dockerfile
title: What will you learn in this module?
toc_min: 1
toc_max: 2
---

The Go getting started guide teaches you how to create a containerized Go application using Docker.

Why Go? According to its authors, [Go is an open source programming language that makes it easy to build simple, reliable, and efficient software][golang]. Whatever are the true reasons behind a wide-scale adoption of Go, it is undeniable that it is a major player in the modern Cloud ecosystem. In fact, Docker, as well as Kubernetes, are written in Go.

[golang]: https://golang.org/

In this guide, you’ll learn how to:

* Create a new `Dockerfile` which contains instructions required to build a Docker image for a simple Go program;
* Run the newly built image as a container;
* Set up a local development environment to connect a database to the container;
* Use Docker Compose to run your Go application and other services it requires;
* Configure a CI/CD pipeline for your application using [GitHub Actions](https://docs.github.com/en/actions){:target="_blank" rel="noopener" class="_"}.

After completing the Go getting started modules, you should be able to containerize your own Go application based on the examples and instructions provided in this guide and the resources that it refers to.

Let's get started!

[Build your Go image](build-images.md){: .button .outline-btn}

<br />
