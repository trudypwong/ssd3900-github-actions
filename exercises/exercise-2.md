# Exercise 2: Working with Node.js Setup

In this exercise, you'll learn about using GitHub Marketplace actions and configuring inputs by modifying the Node.js setup workflow.

## Tasks:

1. Open `.github/workflows/02-node-setup.yml` in your editor
2. Change the Node.js version
   - Find the `node-version` input under the "Set up Node" step
   - Change the version from 18 to 20
3. Add a step to print the npm version
   - Add a new step after the "Print Node Version" step
   - Name it "Print npm Version"
   - Use the run command: `npm -v`
4. Experiment with action removal
   - Make a copy of the file first so you can restore it later if needed
   - Remove the entire "Set up Node" step that uses `actions/setup-node@v3`
   - Push the changes and check if `node -v` still works
   - What does this teach you about action dependencies?

## Expected Outcomes:

- Learn how to configure action inputs using the `with:` syntax
- Understand how to use multiple related steps in a workflow
- Learn about dependencies between actions and commands

## How to Run:

After making each change, commit and push to your repository. Then go to the Actions tab in your GitHub repository to view the workflow runs and their outputs. 