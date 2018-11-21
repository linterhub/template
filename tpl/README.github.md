# {{ name }}

> {{ description }}

## Table of Contents
{% block toc %}
- [Contribute](#contribute)
- [License](#license)
{% endblock %}
{% block readme %}
## Contribute

There are many ways to contribute to this project, please follow
[Contributing Guidelines][contributing].

## License

[MIT][license].

[contributing]: {{ github.contributing }}
[license]: {{ github.license }}
{% endblock %}
