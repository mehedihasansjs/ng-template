# Angular Application Boilerplate
This is a boilerplate for Angular applications. It includes a basic structure for an Angular application,
with a few components, services, and a routing module.

## Features

- Angular 18
- Industry-standard folder structure
- Configured with Tailwind CSS
- Configured with ESLint
- Configured with Prettier
- Configured with Husky
- Integrated with GitHub Actions
- Enfored Conventional Commits for commit messages
- Integrated Semantic Versioning

## Create your own Angular application using this boilerplate

### Using GitHub CLI

Create a new repository using the GitHub CLI:

```bash
gh repo create <repository-name> --public --template="mehedihasansjs/ng-template"
```

### By Cloning the Repository

Clone the repository (SSH):

```bash
git clone git@github.com:mehedihasansjs/ng-template.git
```

Clone the repository (HTTPS):

```bash
git clone https://github.com/mehedihasansjs/ng-template.git
```

Clone the repository (GitHub CLI):

```bash
gh repo clone mehedihasansjs/ng-template
```

Then navigate to the cloned repository and remove the `.git` directory:

```bash
cd ng-template
rm -rf .git
```

Then initialize a new Git repository:

```bash
git init
```

Then add the remote repository:

```bash
git remote add origin <remote-repository-url>
```

## Getting Started
To get started, clone the repository and run `npm install` to install the dependencies.
Then, run `npm start` to start the development server.