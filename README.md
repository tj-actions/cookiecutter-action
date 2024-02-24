[![Codacy Badge](https://app.codacy.com/project/badge/Grade/936bc00f3b854bcca04dee87c68fff21)](https://app.codacy.com/gh/tj-actions/cookiecutter-action/dashboard?utm_source=gh\&utm_medium=referral\&utm_content=\&utm_campaign=Badge_grade)
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
[![CI](https://github.com/tj-actions/cookiecutter-action/actions/workflows/test.yml/badge.svg)](https://github.com/tj-actions/cookiecutter-action/actions/workflows/test.yml)

# cookiecutter-action

[Cookiecutter](https://github.com/cookiecutter/cookiecutter) for github actions

# Installation

```shell script
$ pip install "cookiecutter>=1.7.0"
```

# Usage

```shell script
$ cookiecutter https://github.com/tj-actions/cookiecutter-action.git
```

Answer the provided questions to create a default shell script Docker action.

### Sample answer

```shell script
$ cookiecutter https://github.com/tj-actions/cookiecutter-action.git
full_name [Tonye Jack]: 
email [jtonye@ymail.com]: 
github_username [Enter the github user/organization name (e.g 'test')]: tj-actions
project_name [Enter the project name (e.g 'test-project')]: test-project
project_slug [test-project]: 
project_short_description [Enter a short description (e.g 'Test Description')]: Test Description
default_branch [master]: main
action_name [Enter a descriptive action name (e.g 'My Test Action']: My Test Action
version [Enter the initial version (e.g: 'v1')]: v1
branding_icon [check-square]: hard-drive
Select action_color:
1 - white
2 - yellow
3 - blue
4 - green
5 - orange
6 - red
7 - purple
8 - gray-dark
Choose from 1, 2, 3, 4, 5, 6, 7, 8 (1, 2, 3, 4, 5, 6, 7, 8) [1]:
Select open_source_license:
1 - MIT license
2 - BSD license
3 - ISC license
4 - Apache Software License 2.0
5 - GNU General Public License v3
6 - Not open source
Choose from 1, 2, 3, 4, 5, 6 [1]: 1
```

This generates a [**test-project**](test-project)

*   Free software: [MIT license](LICENSE)

If you feel generous and want to show some extra appreciation:

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

[buymeacoffee]: https://www.buymeacoffee.com/jackton1

[buymeacoffee-shield]: https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://home.boidol.dev/"><img src="https://avatars.githubusercontent.com/u/652404?v=4?s=100" width="100px;" alt="Raphael Boidol"/><br /><sub><b>Raphael Boidol</b></sub></a><br /><a href="https://github.com/tj-actions/cookiecutter-action/commits?author=boidolr" title="Documentation">📖</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!