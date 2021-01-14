# cookiecutter-action
[Cookiecutter](https://github.com/cookiecutter/cookiecutter) for github actions

# Usage

```shell script
$ pip install "cookiecutter>=1.7.0"
```

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
action_icon [check-square]: hard-drive
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
