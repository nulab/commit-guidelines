# commit-guidelines

A demo repository that exemplifies all techniques discussed in the **[Git commit messages for the bold and the daring](https://medium.com/nulab/git-commit-messages-for-the-bold-and-the-daring-3cc91a91e29b)** article.

# Repository 101

This repository contains four tagged versions, each corresponding to a different technique discussed in the article:


* `commit-template`
* `husky`
* `commitizen-with-conventional-changelog`
* `commitizen-with-commitlint`

To try out one specific technique just checkout the corresponding tag and you're good to go.

# Getting started

Clone the repository:
```
git clone https://github.com/CarmenPopoviciu/commit-guidelines.git
```

Change your current working directory to the repository directory:
```
cd commit-guidelines
```

Install npm dependencies:
```
npm install
```
or 

```
yarn
```

Checkout the version you're interested in and start playing around (please see below the necessary setup instructions for each available tag)

### commit-template

Checkout the `commit-template` tag:
```
git checkout commit-template
```

Change your local Git configuration to use the example template in the repository (see the `.git-message-template` file):
```
git config --local commit.template "path_to/.git-message-template"
```

Make some changes in the repository and commit them:
```
git commit
```

Rejoice \o/

![commit-template](https://cdn-images-1.medium.com/max/1600/1*onuzewnaHou0rD1fmLM1MQ.gif)

### husky

Checkout the `husky` tag:
```
git checkout husky
```

Make some changes in the repository and commit them:
```
git commit
```

Rejoice some more \o/

![husky](https://cdn-images-1.medium.com/max/1600/1*YvUZSzTZFLf591l-wzB4xg.gif)

### commitizen-with-conventional-changelog

Checkout the `commitizen-with-conventional-changelog` tag:
```
git checkout commitizen-with-conventional-changelog
```

Make some changes in the repository and commit them:
```
npm run commit
```

or
```
yarn commit
```

Happiness FTW

![commitizen-with-conventional-changelog](https://cdn-images-1.medium.com/max/1600/1*PZkku8CpI7vjUOEe8uaJOQ.gif)

### commitizen-with-commitlint

Checkout the `commitizen-with-commitlint` tag:
```
git checkout commitizen-with-commitlint
```

Make some changes in the repository and commit them:
```
npm run commit
```

or
```
yarn commit
```

Have an ice cream, you deserved it!

![commitizen-with-commitlint](https://cdn-images-1.medium.com/max/1600/1*gePp0lCoIW7RXMkLHuFGTQ.gif)