{% capture my_include %}{% include wiki/intro.md %}{% endcapture %}
{{ my_include | markdownify }}
