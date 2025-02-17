# 11.1 - CI/CD on a Python application

There are many linters available for Python. The most common ones include Flake8 and Pylint.
For testing, pytest is popular because of its simplicity and extensive support for plugins; allowing unit tests, integration tests, and performance tests.
Tools like setuptools or Poetry can be used in python to package the application into distributable formats, for example wheels or Docker images.

Alternatives to Jenkins and GitHub Actions:
GitLab CI/CD: Integrated directly into GitLab, allowing YAML-based configuration and easy automation.
CircleCI: Cloud-based solution offering parallel execution and integration with multiple VCS platforms.
Travis CI: Often used in open-source projects, supports GitHub repositories and automates builds and tests.
Azure DevOps Pipelines: Microsoft-backed solution with enterprise-level features and integration with Azure.
TeamCity: Flexible CI/CD solution from JetBrains, offering a high level of customization.

Self-hosted vs cloud-based CI/CD setup depends on several factors. Cloud based environment like GitHub Actions or CircleCI is better for small to medium-sized teams because it is easy to setup, great scalability, and has lower maintenance overhead. If the team has specific security requirements, needs custom hardware, or has a large number of builds, a self-hosted solution like Jenkins could be more cost-effective and flexible.
