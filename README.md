{% capture my_include %}
{% include ../wiki/intro.md %}
{% include workbench.md %}
{% include soldering.md %}
{% include multimeter.md %}
{% include microscopes-magnification.md %}
{% include oscilloscope.md %}
{% include logic-analyzer.md %}
{% include oscope-vs-logic-analyzer.md %}
{% include clips-and-probes.md %}
{% include power-supplies.md %}
{% include jtag-swd.md %}
{% include flash-extraction.md %}
{% include single-board-computers.md %}
{% include fault-injection.md %}
{% include other.md %}
{% include conclusion.md %}
{% endcapture %}
{{ my_include | markdownify }}
