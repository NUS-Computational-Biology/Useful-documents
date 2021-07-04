# Useful-documents
A collection of useful documents

## 🤝 Contributing

Being a crowd-sourced project, everyone can contribute provided that it respects the following points:

- Before contributing any document, the author must make sure all sources are acknowledged (your name
 for original works).
- Select an open-source license which protects contributors and users. Learn about and choose an open-source
 license [here](https://choosealicense.com/).

In order to start contributing:

1. Fork this repository clicking on the "Fork" button on the upper-right area of the page.
1. Clone your just forked repository to a folder of your choosing:

    ```bash
    git clone https://github.com/your-github-username/Useful-documents.git
    ```

1. Add the main Useful-documents repository as a remote to your forked repository:

    ```bash
    git remote add Useful-documents https://github.com/NUS-Computational-Biology/Useful-documents
    ```

1. Create a new branch:

    ```bash
    git checkout -b my-new-branch
    ```

1. Add your documents to the folder and commit your changes:

    ```bash
    git commit -m 'Add/Update some document'
    ```

1. Push your commits to the branch:

    ```bash
    git push origin my-new-branch
    ```

1. Go to your forked repo and make a pull request to the main repo

    **After your pull request is successfully merged**, you can safely delete your branch.

If this is your repeat contribution, remember to synchronize the `main` branch in your forked by
 following these steps:

1. Change to your local `main` branch (in case you are not on it already):

    ```bash
    git checkout main
    ```

1. Fetch the remote changes:

    ```bash
    git fetch Useful-documents
    ```

1. Merge them:

    ```bash
    git rebase Useful-documents/main
    ```
