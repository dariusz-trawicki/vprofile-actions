# CI/CD with GitHub Actions

Helper repository for the project:: https://github.com/dariusz-trawicki/coding-examples/tree/main/gitops-project

The **GitHub Actions** workflow `vprofile actions` runs app tests, builds a `Docker` image, pushes it to `Amazon ECR`, and deploys to `Amazon EKS`.

**Pipeline overview**
- **CI**: Build and push image to ECR
- **CD**: Deploy to EKS
