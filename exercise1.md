# Exercise 1

Let us imagine a small team of six developers working on a Python application that is about to be released. Since the application is in active development, setting up Continuous Integration (CI) is important to ensure code quality and stability.

In the Python ecosystem, there are several common tools to cover the usual CI steps. For linting, the most popular choice is **Flake8** or **Pylint**, which check for style consistency and potential errors. For testing, **pytest** is widely used because it is simple to set up and supports advanced features such as fixtures and plugins. For building or packaging the application, tools like **setuptools** or **poetry** are often used, especially if the project will be distributed as a Python package.

When it comes to choosing a CI platform, there are alternatives to Jenkins and GitHub Actions. **GitLab CI/CD** is tightly integrated with GitLab repositories and provides a smooth developer experience. **CircleCI** is another cloud-based service that is popular for its speed and flexibility. Other options include **Travis CI** or even using **Azure DevOps Pipelines**.

The decision between self-hosted and cloud-based CI depends on the project’s requirements. A cloud-based system is usually easier to set up, requires less maintenance, and scales automatically. However, a self-hosted runner may be necessary if the codebase includes sensitive data, requires custom hardware, or must run inside a restricted network. To make this decision, the team would need information about budget, compliance requirements, and infrastructure constraints.
