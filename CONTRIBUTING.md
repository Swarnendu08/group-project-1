# Contributing

## Before starting

Check existing issues, then create a task with a clear goal and acceptance criteria. The owner can assign the task to an invited collaborator.

## Make a change

1. Update your local `main` with `git pull --ff-only`.
2. Create a branch such as `feature/login` or `fix/navigation`.
3. Make a focused change and check it using the project's documented commands. Until application code is added, review documentation and validate any configuration you change.
4. Commit and push the branch.
5. Open a pull request to `main`, describe the result, and record how you checked it.
6. Request a teammate's review when one is available, resolve feedback, and merge the pull request.

GitHub can automatically delete a merged branch. Update `main` before starting the next change.

## Keep shared work current

Commit and push work you want available to teammates. To resume uncommitted work on another device, reopen the same Codespace. Never put credentials in commits; use local environment variables or Codespaces secrets when the application needs them.

## Project decisions

Track the application goal, language, and dependencies in an issue. Update the README with install, run, and test commands when application code is introduced.
