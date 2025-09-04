# project-template
Template for a data analysis project.

## How to start a new project with this template

1. Create a new repository. Go to the [GitHub website of this template](https://github.com/masashi-CU/project-template). Press the upper-right button `Use this template`, then `Create a new repository`.
Set an repository name. Always **choose visibility `Private`**.

1. Download the repository to the HPC cluster or your laptop.

    ```$ git clone https://github.com/YOUR_GIT_USERNAME/NEW_REPO_NAME.git```

1.  Grant access to the project folder to the people in the same group.

    ```$ find NEW_REPO_NAME -type d -exec chmod g+ws {} ';'```

## Contents

`data`: folder for data to be analyzed in this project (e.g., CellRanger count matrix, clinical traits of patients.) The contents of this folder will not be uploaded to GitHub.

`scripts`: folder for analysis scripts. Only files with specific extensions will be uploaded to GitHub (.R, .Rmd, .py, ipynb, .sh, .pl, .cpproj, .cppipe)
