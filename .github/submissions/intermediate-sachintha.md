# Task 04

I created a custom GitHub Actions workflow that runs on pushes to the develop branch. The workflow sets up Node.js 18, installs dependencies, and runs tests inside the sample-app directory to verify the application

![Task 4](https://github.com/sachilz/github-actions-learning/blob/working-intermediate-sachintha/.github/submissions/Proof/1.png)

# Task 05

I added job-level environment variables to the build and test workflow and verified their values by printing them in the workflow logs. This helped me understand how environment variables are defined and accessed across steps in GitHub Actions

![Task 5](https://github.com/sachilz/github-actions-learning/blob/working-intermediate-sachintha/.github/submissions/Proof/2.png)

![Task 5](https://github.com/sachilz/github-actions-learning/blob/working-intermediate-sachintha/.github/submissions/Proof/2-1.png)

![Task 5](https://github.com/sachilz/github-actions-learning/blob/working-intermediate-sachintha/.github/submissions/Proof/2-2.png)

# Task 06

I created a test GitHub secret and accessed it inside a workflow using the secrets context. I verified that the secret value was masked in the workflow logs, which helped me understand how GitHub securely manages sensitive information

![Task 6](https://github.com/sachilz/github-actions-learning/blob/working-intermediate-sachintha/.github/submissions/Proof/3.png)

# Task 07

I used GitHub Actions matrix strategy to run the same build and test workflow in parallel across multiple Node.js versions (16.x, 18.x, and 20.x). This helped verify application compatibility across different runtime environments

![Task 7](https://github.com/sachilz/github-actions-learning/blob/working-intermediate-sachintha/.github/submissions/Proof/4.png)
