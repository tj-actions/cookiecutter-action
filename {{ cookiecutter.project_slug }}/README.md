{{ cookiecutter.project_name }}
{% for _ in cookiecutter.project_name %}-{% endfor %}

{{ cookiecutter.project_short_description }}

```yaml
...
    steps:
      - uses: actions/checkout@v2
      - name: {{ cookiecutter.action_name }}
        uses: {{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}@{{ cookiecutter.version|default("master", true) }}
```


## Inputs

|   Input       |    type    |  required     |  default                      |  description  |
|:-------------:|:-----------:|:-------------:|:----------------------------:|:-------------:|
| token         |  `string`   |    `true`    | `{{ "${{ github.token }}" }}` | [GITHUB_TOKEN](https://docs.github.com/en/free-pro-team@latest/actions/reference/authentication-in-a-workflow#using-the-github_token-in-a-workflow) <br /> or a repo scoped <br /> [Personal Access Token](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/creating-a-personal-access-token)              |



* Free software: {{"["}}{{ cookiecutter.open_source_license }}{{"]"}}(LICENSE)

Features
--------

* TODO


Credits
-------

This package was created with [Cookiecutter](https://github.com/cookiecutter/cookiecutter).



Report Bugs
-----------

Report bugs at https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your workflow that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.
