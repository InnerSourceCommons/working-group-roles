{% for link in site.links %}
{% unless link[1] == nil %}
[{{ link[0] }}]: {{link[1]}}
{% endunless %}
{% endfor %}
[isc calendar]: https://github.com/InnerSourceCommons/foundation-governance/blob/master/how-to/access-isc-calendar.md