# Node Backend
## Introduction

This repo contains the Node.js backend server code which by default runs locally on the port 5000.

## Deployed Link
https://webevaluator.onrender.com/api/status

## Pre-requisites

Your machine should have Npm(or Yarn), Node.js and MongoDb installed to use it locally.

## Setting up the repository locally

1. Fork the repo to your account.

2. Clone your forked repo to your local machine:
Replace `<YOUR_GITHUB_USERNAME>` with your actual GitHub username in the below command. This will clone the code to your local machine.
```
git clone https://github.com/<YOUR_GITHUB_USERNAME>/nodebackend.git (https)
```
or
```
git clone git@github.com:<YOUR_GITHUB_USERNAME>/nodebackend.git (ssh)
```

3. Change directory to `nodebackend`.
```
cd nodebackend
```

4. Check the remote of your local repo by:
```
git remote -v
```
It should output the following:
```
origin	https://github.com/<YOUR_GITHUB_USERNAME>/nodebackend.git (fetch)
origin	https://github.com/<YOUR_GITHUB_USERNAME>/nodebackend.git (push)
```
or
```
origin	git@github.com:<YOUR_GITHUB_USERNAME>/nodebackend.git (fetch)
origin	git@github.com:<YOUR_GITHUB_USERNAME>/nodebackend.git (push)
```

5. Add remote upstream by running the below command:
```
git remote add upstream https://github.com/webevaluator/nodebackend.git (https)
```
or
```
git remote add upstream git@github.com:webevaluator/nodebackend.git (ssh)
```

6. Running `git remote -v` should then print the following:
```
origin	https://github.com/<username>/nodebackend.git (fetch)
origin	https://github.com/<username>/nodebackend.git (push)
upstream	https://github.com/webevaluator/nodebackend.git (fetch)
upstream	https://github.com/webevaluator/nodebackend.git (push)
```
or
```
origin	git@github.com:<username>/nodebackend.git (fetch)
origin	git@github.com:<username>/nodebackend.git (push)
upstream	git@github.com:webevaluator/nodebackend.git (fetch)
upstream	git@github.com:webevaluator/nodebackend.git (push)
```

## Run locally

- For installing dependencies run
```
npm install
```

- For starting the server run:
```
npm run dev
```

- Go to: http://localhost:5000/api/status