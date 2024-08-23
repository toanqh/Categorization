# Page 3

Page 3

```{include}
```

\{{ page-1.md "\*page-3.md\*" \}}

import "./page-1.md" }

include: static/page-1.md

[page-1.md](page-1.md "mention")

```
{% raw %}
{% content-ref url="./" %} . {% endcontent-ref %}
{% endraw %}


```

[page-2.md](page-2.md "mention") [page-1.md](page-1.md "mention")



![](<.gitbook/assets/screenshot\_1722259348 (1).png>)





{% content-ref url="page-2.md" %}
[page-2.md](page-2.md)
{% endcontent-ref %}
