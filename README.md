{% capture my_include %}{% include intro.md workbench.md %}{% endcapture %}
{{ my_include | markdownify }}
