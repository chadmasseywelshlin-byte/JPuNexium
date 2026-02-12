<div class="sidebar">
  {% capture sidebar_content %}{% include _sidebar.md %}{% endcapture %}
  {{ sidebar_content | markdownify }}
</div>
