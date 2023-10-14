{% capture my_include %}
{% include intro.md %}
{% include workbench.md %}
{% endcapture %}
{{ my_include | markdownify }}
