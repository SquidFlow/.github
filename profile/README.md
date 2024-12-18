# SquidFlow Organization

Welcome to SquidFlow Organization! 👋

> SquidFlow represents the next iteration, the next possibility, and a new exploration.

## About Us

SquidFlow is an experimental project aimed at improving GitOps workflows. As platform usage within organizations evolves from initial developer-centric operations to include team members without extensive ops background, we recognized the need for a more intuitive experience.

Our goal is to enhance the self-service platform experience by:
- Making configuration fields self-explanatory
- Simplifying the GitOps workflow
- Providing better user experience for platform operations

This project serves as a proof of concept for these improvements, primarily developed using Go language.

## Main Projects

- [service](https://github.com/SquidFlow/service) - SquidFlow Core Platform Service
  - Full-stack project containing both frontend and backend components
  - Includes 2 binary executables and a web frontend
  - All components are available as Docker images in GitHub Container Registry
- [argocd-addon](https://github.com/SquidFlow/argocd-addon) - ArgoCD extension that supports hybrid rendering of Kustomize and Helm resources
  - Enables seamless integration between Kustomize and Helm deployments
  - Custom plugin for ArgoCD to enhance manifest rendering capabilities
- [gitops](https://github.com/SquidFlow/gitops) - Default GitOps metadata repository for deployment configurations
- [demo-app](https://github.com/SquidFlow/demo-app) - Sample application for deployment demonstration

## Contact Us

If you're interested in our projects or have any questions, feel free to reach out through:

- Creating Issues in specific projects
- Submitting Pull Requests to contribute

## License

This organization's projects are licensed under the BSD License unless otherwise specified
