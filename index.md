Well well!

test1: {% include {{ site.hi.link }} %}

{% capture pagey %}{{ site.hi.link }}{% endcapture %}

test 2: {% include {{ pagey }} %}
