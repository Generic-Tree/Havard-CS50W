# Harvard CS50W Course Projects

Here you will find all my submissions of
**Harvard CS50's Web Programming with Python and JavaScript** [2020 course][1] projects.

> This repository also suits as a template for other students 
interested on an organized beginning for their projects repo structure.

[>1]: https://www.repostatus.org "Repo maintenance status"
[>2]: https://choosealicense.com/licenses/gpl-3.0/ "GPL 3.0 License description"

[1]: https://cs50.harvard.edu/web/2020/ "Havard CS50W 2020 course"
[2]: https://docs.github.com/en/actions/security-guides/encrypted-secrets "Github: Encripted secrets"
[3]: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token "Github: Creating a personal access token"

[!0]: https://github.com/artu-hnrq/havard-cs50w/generate "Github repository's template generation URL"

[B0]: https://img.shields.io/static/v1?label=create%20a%20new%20repository&message=%20&style=social "Create new repository"
[B1]: https://www.repostatus.org/badges/latest/concept.svg "Repostatus active badge"
[B2]: https://img.shields.io/github/license/artu-hnrq/havard-cs50w?color=green "License badge"

### Table of Contents
<details>
  <summary>See all</summary>

  * [Getting started](#getting-started)
    * [Development environment](#development-environment)
    * [Continuous automation](#continuos-automation)
  * [Project specifications](#project-specifications)
    * [Folder structure](#folder-structure)
  * [Maintenance](#maintenance-)
  * [License](#license-)

</details>


## Getting started
First of all, [![create a new repository][B0]][!0] from this template, \
name it accordingly and place where it best fits for you. \
Remember to check in all desired branches before confirm!

### Development environment
Make sure you have `Git` installed, as wel as `Python` will also be needed:

```bash
$ git --version
git version 2.25.1
$ python3 --version
Python 3.10.6
```

Thus, clone the recent-created repository locally,
and you'll be ready to start developing your projects.

### Continuos automation
Project submission is automated through a *submit-on-push* GitHub Action.
It takes in account the branch name to forward the released code to Harvard's `me50/{GITHUB-USERNAME}` repository,
as required.

For it to work you first need to *Authorize cs50*, as specified on *How to Submit* section of project's statements.
Then, register a `PERSONAL_ACCESS_TOKEN` [secret][2] to your repo, as described [here][3]. And you'll be setup!

After that, every push to a branch which name starts with `web50/projects/2020/x/` will be submitted accordingly. 


## Project specifications
[Harvard CS50W][1] is divided into **9 lectures**, summing up **6 projects**.

Each project has an associated initial *distribution code*, available for download along with its description,
which are already placed in each equivalent branch of this repo. Check them out:

|   #   | Project statement |            Branch            |
|:-----:|:-----------------:|:----------------------------:|
|   0   |   [Search][P0]    |     [0-search][0-search]     |
|   1   |    [Wiki][P1]     |       [1-wiki][1-wiki]       |
|   2   |  [Commerce][P2]   |   [2-commerce][2-commerce]   |
|   3   |    [Mail][P3]     |       [3-mail][3-mail]       |
|   4   |   [Network][P4]   |    [4-network][4-network]    |
| Final |  [Capstone][P*]   | [final-capstone][*-capstone] |

[P0]: https://cs50.harvard.edu/web/2020/projects/0/search/ "Project 0: statement"
[P1]: https://cs50.harvard.edu/web/2020/projects/1/wiki/ "Project 1: statement"
[P2]: https://cs50.harvard.edu/web/2020/projects/2/commerce/ "Project 2: statement"
[P3]: https://cs50.harvard.edu/web/2020/projects/3/mail/ "Project 3: statement"
[P4]: https://cs50.harvard.edu/web/2020/projects/4/network/ "Project 4: statement"
[P*]: https://cs50.harvard.edu/web/2020/projects/final/capstone/ "Final Project: statement"

[0-search]: https://github.com/artu-hnrq/havard-cs50w/tree/0-search "Project 0: initial code"
[1-wiki]: https://github.com/artu-hnrq/havard-cs50w/tree/1-wiki "Project 1: initial code"
[2-commerce]: https://github.com/artu-hnrq/havard-cs50w/tree/2-commerce "Project 2: initial code"
[3-mail]: https://github.com/artu-hnrq/havard-cs50w/tree/3-mail "Project 3: initial code"
[4-network]: https://github.com/artu-hnrq/havard-cs50w/tree/4-network "Project 4: initial code"
[*-capstone]: https://github.com/artu-hnrq/havard-cs50w/tree/final-capstone "Project 5: initial code"

### Folder structure
For this **main** template branch,
beside the most essential files of an open-source repository,
there's also a project submission automation configured.

```
.
├── .git/                       Version control system folder
├── .github/                    Repo continuous automation 
├── .gitignore                  VCS ignored files manifest
├── CHANGELOG.md                Release notes description
├── LICENSE                     License file
└── README.md                   Repo readme document
```


## Maintenance [![][B1]][>1]
This project is maintained by the author, [@artu-hnrq](https://github.com/artu-hnrq). \
Though, minimal or no implementation has been done yet,
it's only intended to be a limited example, demo, or proof-of-concept.


## License [![][B2]][>2]
This project is published under the permissions established by [GNU General Public License v3.0][>2].
