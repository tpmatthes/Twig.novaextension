This is a _Markdown_ **File**!

Map “.md” to “Twig-Markdown” in settings to activate syntax highlighting for Twig inside Markdown files (Grav CMS).

```css
html {
	font-size: 1rem;
}
```

{% set test = 'This should be highlighted!' %}

```twig
{% set test = 'Hello Grav CMS!' %}
{{ test }}
```
