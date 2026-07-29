Part 3 – CI/CD

"For CI/CD, I would use GitHub Actions."

Trigger on every push.
Install project dependencies.
Run lint checks.
Run automated tests.
Build the project.
Deploy automatically to the staging environment after merging into the main branch.

Secrets

I would never hardcode API keys in the code. Instead, I would store them in GitHub Secrets and access them as environment variables during deployment.

Rollback

If a deployment breaks production, my first priority is reducing user impact. I would stop further deployments, roll back to the last working version, check the logs to identify the issue, fix it, test it in staging, and then deploy again.