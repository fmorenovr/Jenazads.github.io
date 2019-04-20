<!DOCTYPE html>
<html lang="{{ site.lang | default: "en-US" }}">
  {% include head.md %}
  {% include mathjax.md %}
  <body>
    {% include mainbar.md %}
    {% include beginpage.md %}
    <div class="main-content">
      {{ content }}
    </div>
    {% include footer.md %}
  </body>
</html>
