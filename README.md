# API-Testing
---
These instructions will allow you to get a working copy of the project on your local machine for development and testing purposes..

## 💻 Pre-requisites
@@ -17,3 +16,27 @@ Open the terminal and run the following commands:
git clone https://github.com/daslima/API-Testing
cd API-Testing
```

## ⚙️ Executando os testes

No report
```
newman run dummyJSON.postman_collection.json -e dummyEnvironment.postman_environment.json
```

With report
```
newman run dummyJSON.postman_collection.json -e dummyEnvironment.postman_environment.json -r htmlextra
```
## 📫 Contributing to the project

To contribute to the project, follow these steps:

1. Clone this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to original branch: `git push origin <branch_name>`
5. Create the pull request.

Alternatively, see the GitHub documentation at [how to create a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
