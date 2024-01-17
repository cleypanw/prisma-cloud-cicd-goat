# Build, scan and deploy a docker image securely with Prisma Cloud and GitHub Action.

#### Build Status

#### Objectifs

Based on the docker image buil pipeline from https://github.com/cleypanw/prisma-cloud-secures-ci-image-build

We are going to exploit the vulnerabilities of a badly secured pipeline to discover all the documents in the repository through pipeline command injection ([Top OWASP 10 CICD RISK CICD-SEC-4 Poisoned Pipeline Execution (PPE)](https://owasp.org/www-project-top-10-ci-cd-security-risks/CICD-SEC-04-Poisoned-Pipeline-Execution))

