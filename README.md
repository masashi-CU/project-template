# project-template
Template for a data analysis project.

To start a new project with this template:
```
# Create a repository for a new analysis project
$ gh repo create NEW_REPO_NAME --private -p masashi-CU/project-template

# Download the repository
$ gh repo clone YOUR_GITHUB_USERNAME/NEW_REPO_NAME

# Change permission
$ chmod -R g+ws NEW_REPO_NAME
```

- `data`: data to be analyzed in this project (e.g., CellRanger count matrix, clinical traits of patients.) The contents of this folder should not be uploaded to GitHub.
- `scripts`: scripts (e.g., R, Python, Bash) for analysis.
 
