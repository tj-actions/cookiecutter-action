{{ cookiecutter.project_name }}
{% for _ in cookiecutter.project_name %}-{% endfor %}

{{ cookiecutter.project_short_description }}

```yaml
...
    steps:
      - uses: actions/checkout@v2
      - name: {{ cookiecutter.action_name }}
        uses: {% if cookiecutter.org_name %}{{ cookiecutter.org_name }}/{% endif %}{{ cookiecutter.project_name }}@{{ cookiecutter.version|default("master", true) }}
```

* Free software: {{ cookiecutter.open_source_license }}

Features
--------

* TODO


Credits
-------

This package was created with Cookiecutter.



Report Bugs
-----------

Report bugs at https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your workflow that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.
