# dofunthings
Do Fun Things

## Deploying to GitHub Pages

We have automated the deployment process to GitHub Pages using GitHub Actions. Now, every push to the `main` branch will trigger a deployment, making manual setup through repository settings unnecessary.

The website will be accessible at `https://bekahwhittle.github.io/dofunthings`.

**Note:** Ensure the `index.html` file is in the root directory of your branch to allow GitHub Pages to serve your website correctly.

## Running Lint Tests

To ensure the quality of the code, lint tests have been set up. You can run these tests using the following commands:

- To check for lint errors, run `npm run lint`.
- To automatically fix lint errors, run `npm run lint:fix`.
