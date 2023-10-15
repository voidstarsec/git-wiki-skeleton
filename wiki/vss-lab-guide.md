{% capture my_include %}
{% include_relatve intro.md %}
{% include_relatve workbench.md %}
{% include_relatve soldering.md %}
{% include_relatve multimeter.md %}
{% include_relatve microscopes-magnification.md %}
{% include_relatve oscilloscope.md %}
{% include_relatve logic-analyzer.md %}
{% include_relatve oscope-vs-logic-analyzer.md %}
{% include_relatve clips-and-probes.md %}
{% include_relatve power-supplies.md %}
{% include_relatve jtag-swd.md %}
{% include_relatve flash-extraction.md %}
{% include_relatve single-board-computers.md %}
{% include_relatve fault-injection.md %}
{% include_relatve other.md %}
{% include_relatve conclusion.md %}
{% endcapture %}
{{ my_include | markdownify }}
