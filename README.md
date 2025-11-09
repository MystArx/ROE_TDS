DevOps Challenge: Matrix Build

This repository contains a GitHub Actions workflow to demonstrate a multi-platform matrix build strategy.

Workflow

The workflow is defined in .github/workflows/matrix-build.yml.

It performs the following actions:

Triggers on push to the main branch or when manually dispatched.

Uses a matrix strategy to run parallel jobs for Python versions 3.9, 3.10, and 3.11.

Each job generates a unique text file (build-output.txt) containing build information.

Each job uploads its text file as a build artifact named build-6d84116-py<version>.

Contact

For any questions about this repository or workflow, please contact:
ops-manager@world-courier-example.com
