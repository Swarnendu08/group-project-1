# group-project-1

A shared coding project stored on GitHub, with a development configuration for GitHub Codespaces.

## Access from any device

Sign in to GitHub with an account that has access to this repository.

- **View and edit files:** open [the repository](https://github.com/Swarnendu08/group-project-1). Press `.` on the repository page to open the browser editor. This editor does not run programs or provide a terminal.
- **Code and run programs in a browser:** open [Codespaces](https://github.com/Swarnendu08/group-project-1/codespaces), then create a Codespace on `main`. GitHub builds the environment from `.devcontainer/devcontainer.json`.
- **Continue on another device:** open [your Codespaces](https://github.com/codespaces) and resume the same workspace. Each collaborator uses their own Codespace.

Creating a Codespace requires Codespaces access on your GitHub account. GitHub shows applicable usage limits and billing before you select additional paid resources.

The repository is the shared copy of the project. Save, commit, and push changes so they appear in GitHub and in teammates' workspaces. Files saved only inside a Codespace are not yet committed to the repository.

## Work locally

Install Git and authenticate to GitHub, then run:

```sh
git clone https://github.com/Swarnendu08/group-project-1.git
cd group-project-1
```

## Collaborate

The owner can invite teammates in [Settings → Collaborators](https://github.com/Swarnendu08/group-project-1/settings/access). Each teammate needs a GitHub account and must accept the invitation to access a private repository.

Start changes on a branch and open a pull request:

```sh
git switch main
git pull --ff-only
git switch -c feature/short-description
# Edit files, then review the changes.
git diff
git add <files-you-changed>
git commit -m "Describe the change"
git push -u origin feature/short-description
```

Use [Issues](https://github.com/Swarnendu08/group-project-1/issues) to track tasks and problems. See [CONTRIBUTING.md](CONTRIBUTING.md) for the workflow.

## Initial setup

- `main`: shared default branch.
- `.devcontainer/devcontainer.json`: a general-purpose development environment for Codespaces, with common language runtimes available.
- `.editorconfig`: consistent text formatting.
- `.gitignore`: excludes common local environment files, dependency folders, and build output.
- `.github/`: task, bug report, and pull request templates.

The application purpose and programming language are still to be chosen. Application code, dependency installation, run commands, and automated checks will be added once those requirements are defined.
