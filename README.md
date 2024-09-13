# GitHub-Actions
---------------------------------------------

When working with GitHub Actions, it's essential to understand its core components: Workflows, Jobs, and Steps.

Workflows: These are the automation pipelines tied to your GitHub repository. You can have multiple workflows in a repository, and they contain jobs.

Jobs: A workflow is composed of jobs, and each job runs independently. You can configure jobs to run sequentially or in parallel.

Steps: Each job consists of steps, which define the specific tasks to execute, like running scripts or commands.

Workflows also rely on triggers/events to specify when they should run, such as after pushing new commits. Jobs run within environments called runners, which can be predefined (Linux, Mac OS, Windows) or custom. With these components, you can build flexible automation pipelines tailored to your project’s needs.
![image](https://github.com/user-attachments/assets/aa8aada1-e1da-42e7-9232-b5e7ba1750e5)
