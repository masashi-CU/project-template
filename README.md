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

`data`: folder for data to be analyzed in this project (e.g., CellRanger count matrix, clinical traits of patients.) The contents of this folder will not be uploaded to GitHub.

`scripts`: folder for analysis scripts. Only files with specific extensions will be uploaded to GitHub (.R, .Rmd, .py, ipynb, .sh, .pl, .cpproj, .cppipe)
