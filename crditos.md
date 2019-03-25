# Créditos

## Autoría

* {{ book.author }}

### Colaboradores:

{% for collaborator in book.collaborators %}
* {{collaborator.name}} en {{collaborator.edited}}
{% endfor %}

{% GitHubContributors %}
{% endGitHubContributors %}

___

{% include "git+https://github.com/catedu/faq-aularagon.git/imagenes_creditos.md" %}