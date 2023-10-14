{% capture my_include %}{% include intro.md %}{% endcapture %}
{% capture my_include %}{% include workbench.md %}{% endcapture %}
{% capture my_include %}{% include soldering.md %}{% endcapture %}
{% capture my_include %}{% include multimeter.md %}{% endcapture %}
{% capture my_include %}{% include microscopes-magnification.md %}{% endcapture %}
{% capture my_include %}{% include oscilloscop.md %}{% endcapture %}
{% capture my_include %}{% include logic-analyzer.md %}{% endcapture %}
{% capture my_include %}{% include oscope-vs-logic-analyzer.md %}{% endcapture %}
{% capture my_include %}{% include power-supplies.md %}{% endcapture %}
{% capture my_include %}{% include clips-and-probes.md %}{% endcapture %}
{% capture my_include %}{% include flash-extraction.md %}{% endcapture %}
{% capture my_include %}{% include jtag-swd.md %}{% endcapture %}
{% capture my_include %}{% include single-board-computers.md %}{% endcapture %}
{% capture my_include %}{% include fault-injection.md %}{% endcapture %}
{% capture my_include %}{% include other.md %}{% endcapture %}
{% capture my_include %}{% include conclusion.md %}{% endcapture %}
{{ my_include | markdownify }}
