# Gitflow Testing Project

Welcome to your new Gitflow Testing project. This repository has been initialized with the `git-flow` workflow, ready for high-level team collaboration.

## 🚀 Getting Started

To initialize the project correctly, run:
```bash
git flow init -d
```
(This has already been done for you.)

## 🧭 Gitflow Commands

- **Feature Work**: 
  - `git flow feature start feature_name`
  - `git flow feature finish feature_name`
- **Release Work**:
  - `git flow release start version`
  - `git flow release finish version`
- **Hotfix Work**:
  - `git flow hotfix start name`
  - `git flow hotfix finish name`

## 👥 Tracking Team Members

To track when your team members publish to the remote, use these commands:

1.  **Fetch Latest Updates**:
    ```bash
    git fetch --all
    ```
    This fetches all branches and their commits from the remote repo.

2.  **View All Branches (Local & Remote)**:
    ```bash
    git branch -a
    ```

3.  **Visual Log**:
    ```bash
    git log --oneline --graph --decorate --all
    ```
    This shows a compact, visual history of all branches.

## 📦 Suggested VS Code Extensions

For a visual experience in tracking your team, consider installing these extensions:

- **GitLens**: Supercharges Git with powerful features like blame, commit history, and heatmaps.
- **Git Graph**: View a Git Graph of your repository and easily perform Git actions from the graph.
- **Gitflow**: A dedicated extension to run Gitflow commands from the UI.

## 🛠 Project Structure

- `index.html`: Modern landing page for Gitflow testing.
- `style.css`: Premium styling with glassmorphism.
