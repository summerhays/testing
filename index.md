Well well!

test1: {{ include.site.hi }}

{% capture pagey %}{{ site.hi }}{% endcapture %}

test 2: {{ include pagey }}
