
![](https://img.shields.io/badge/Built%20by-DSC%20FUTO-brightgreen.svg)
[![Build Status](https://travis-ci.org/kelvinkamau/Vibranium.svg?branch=master)](https://travis-ci.org/kelvinkamau/Vibranium)
![](https://img.shields.io/github/forks/dscfuto/website.svg?style=social)
![](https://img.shields.io/github/issues/kelvinkamau/Vibranium.svg)
![](https://img.shields.io/maintenance/yes/2019.svg)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/02646f76a26242e3b483fc44e41d9e00)](https://www.codacy.com/manual/dscfuto/website?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=dscfuto/website&amp;utm_campaign=Badge_Grade)

## Usage 🛠
* Fork repository and clone it locally
* Customize the content inside the following files only ```index.html```, ```learn.html```, ```project.html``` & ```manifest.json```
* Publish your site
* Share the goodness of this awesome web template by sharing it & leaving a star on the repo

# Running it locally 🔩
* You might need to have [NPM](https://nodejs.org/en/download/) or [yarn](https://yarnpkg.com/en/docs/install)
* In the project directory, run `npm install` or `yarn install` depending on which you have
* Then run `npm run dev` and open your browser to `http://localhost:8080` to start working on the project
* To build the project run `npm run build`

## Improvements

* <s>Mobile site enhancements</s> ✔
* <s>Add tutorials page</s> ✔
* <s>Add projects showcase page</s> ✔
* <s>Progressive Web App support</s> ✔
* Push notifications support 📢

## Updating
Here is a git workflow for updating your fork (or downloaded copy) to the latest version:
```git
git remote add upstream https://github.com/dscfuto/website.git
git fetch upstream
git merge upstream/website
# resolve the merge conflicts in your editor
git add . -u
git commit -m 'Updated to the latest version'
```

## Contributing
Project DSCFUTO-website is an open source software project and I encourage developers to contribute patches and code for us to include in the main package of this Project. All contributions will be fully credited.

All contributions to this project are done inside the src folder, ensure to make use of gulp to build out the project.

## Using GitHub Issues
* Feel free to use GitHub issues for questions, bug reports, and feature requests
* Use the search feature to check for an existing issue
* Include as much information as possible and provide any relevant resources (Eg. screenshots)
* For bug reports ensure you have a reproducible test case
    * A pull request with a breaking test would be super preferable here but isn't required

## Versioning
This project uses [semver](https://semver.org) for versioning. Current version: v2.0.0
