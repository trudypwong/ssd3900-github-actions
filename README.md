# Learn GitHub Actions: From Zero to Hero

This repository is designed to teach the fundamentals of GitHub Actions with hands-on examples and exercises. By working through these examples, you'll learn how GitHub Actions workflows are structured and how they work, from simple to moderately complex.

## What is GitHub Actions?

GitHub Actions is an automation platform built into GitHub that allows you to define custom workflows to build, test, and deploy your code. These workflows are triggered by events in your repository, and they can automate repetitive tasks, handle CI/CD processes, and much more—all directly from your GitHub repository.

## How a Workflow is Structured

- **Workflow File**: YAML files stored in `.github/workflows/` directory
- **Triggers**: Define when workflows run (e.g., `on: push`)
- **Jobs**: Groups of steps that execute on the same runner
- **Steps**: Individual tasks that run commands or actions
- **Actions**: Reusable units of code from the GitHub Marketplace
- **Runners**: Virtual machines that execute the workflow jobs

## How to Activate the Workflows

1. **Clone this repository** or create a new repository and copy these files into it:
   ```bash
   git clone https://github.com/yourusername/learn-github-actions.git
   ```

2. Make sure the `.github/workflows/*.yml` files are in your repository

3. **Push any change** to trigger the workflows:
   ```bash
   # Make a small change
   echo "# My GitHub Actions learning journey" >> my_journey.md
   
   # Commit and push
   git add my_journey.md
   git commit -m "Add learning journey file"
   git push
   ```

4. **Open the Actions tab** in your GitHub repository to view the workflow runs

5. Click on any workflow run to see its detailed logs and results

## Workflow Examples

This repository includes three progressively complex workflow examples:

1. **[01-minimal.yml](.github/workflows/01-minimal.yml)**: A minimal workflow that demonstrates basic structure
2. **[02-node-setup.yml](.github/workflows/02-node-setup.yml)**: Shows how to set up Node.js and use GitHub Marketplace actions
3. **[03-multi-step.yml](.github/workflows/03-multi-step.yml)**: Demonstrates a multi-step job with various shell commands

## Exercises

To get hands-on experience with GitHub Actions, try these exercises:

1. [Exercise 1](exercises/exercise-1.md) - Modify the minimal workflow
2. [Exercise 2](exercises/exercise-2.md) - Work with Node.js setup
3. [Exercise 3](exercises/exercise-3.md) - Understand multi-step jobs

Each exercise includes tasks, expected outcomes, and guidance on how to run and test your changes.

## Benefits of Learning GitHub Actions

- Automate repetitive tasks in your development workflow
- Implement continuous integration and delivery (CI/CD) pipelines
- Reduce manual errors and improve code quality
- Integrate with other tools and services
- Save time and increase productivity

## Additional Resources

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [GitHub Marketplace for Actions](https://github.com/marketplace?type=actions)
- [GitHub Actions Workflow Syntax](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions)

## Feedback

If you have any feedback or suggestions for improving this learning repository, please open an issue!
