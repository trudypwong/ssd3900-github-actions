# Exercise 3: Understanding Multi-Step Jobs

In this exercise, you'll learn about step ordering and the importance of syntax in GitHub Actions workflows.

## Tasks:

1. Open `.github/workflows/03-multi-step.yml` in your editor
2. Add a new final step
   - Add a step at the end of the list
   - Name it "End"
   - Use the run command: `echo "This is the end"`
3. Experiment with step ordering
   - Reorder the steps in the workflow (e.g., move "List files" to be first)
   - Push your changes and observe the output in the Actions tab
   - Does changing the order affect the output sequence?
4. Investigate syntax errors
   - Make a copy of the file first so you can restore it later if needed
   - Remove a dash from one of the `- name:` lines (making it `name:` instead)
   - Push your changes and see what happens in the GitHub Actions tab
   - What kind of error message do you see?

## Expected Outcomes:

- Learn how step ordering affects execution
- Understand the importance of correct YAML syntax
- Get familiar with GitHub Actions error messages and debugging

## How to Run:

After making each change, commit and push to your repository. Then go to the Actions tab in your GitHub repository to view the workflow runs and their outputs. 