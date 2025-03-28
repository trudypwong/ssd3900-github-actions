# Exercise 1: Understanding the Minimal Workflow

In this exercise, you'll learn the basic components of a GitHub Actions workflow by modifying the minimal example.

## Tasks:

1. Open `.github/workflows/01-minimal.yml` in your editor
2. Modify the workflow to print your name
   - Change the echo command to include your name: `echo "Hello from GitHub Actions, YOUR_NAME!"`
3. Add a second step to print today's date
   - Add a new step after the "Say Hello" step
   - Name it "Print Date" 
   - Use the run command: `date`
4. Delete the `name:` field from the top of the file
   - What happens when you push this change?
   - Check the Actions tab in your GitHub repository to see how the workflow is labeled now

## Expected Outcomes:

- Learn how to modify text output in GitHub Actions
- Understand how to add steps to a workflow
- See how the workflow name affects display in the GitHub UI

## How to Run:

After making each change, commit and push to your repository. Then go to the Actions tab in your GitHub repository to view the workflow runs and their outputs. 