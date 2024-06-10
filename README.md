---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# Main Page

[link to page 1](main-page/a-nice-page.md)





### Input:

```
{% raw %}
{% if Language == 'fr' %}
Salut!
{% else %}
Hello!
{% endif %}
{% endraw %}
```

{% content-ref url="main-page/a-nice-page.md" %}
[a-nice-page.md](main-page/a-nice-page.md)
{% endcontent-ref %}
