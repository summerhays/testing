Well well!

test1: {% include {{ site.en.link }} %}

{% capture pagey %}{{ site.en.link }}{% endcapture %}

test 2: {% include {{ pagey }} %}
