# Práctica intro2sd

## Kanban Project creado

## Reconfiguración de _config.yml
```
baseurl: "/intro2sd-template/" # the subpath of your site, e.g. "/blog"

demo:
    output: true
    permalink: /:collection/:path/

# _portfolio
  - scope:
      path: ""
      type: portfolio
    values:
      layout: single
      author_profile: false
      share: true
```
## Uso de liquid

```html
<ul>
{% for discipline in site.data.disciplines %}
  <li>
    <h3>{{ discipline.title }}</h3>
    <p>{{ discipline.content }}</p>
  </li>
{% endfor %}
</ul>
```

## Uso de _data
```js
    //_data/disciplinmes.json
[
    {
        "title": "Project management",
        "content": "If a systems development project is to be successful, technical expertise is not enough; effective project management is also required. The project manager plans the undertaking, mobilises the resources required and controls and coordinates the work"
    },
    {
        "title": "Business analysis",
        "content": "Business analysis is concerned with investigating the business situation and finding out what are the problems to be solvedor opportunities to be exploited."
    },
    {
        "title": "Project management",
        "content": "If a systems development project is to be successful, technical expertise is not enough; effective project management is also required. The project manager plans the undertaking, mobilises the resources required and controls and coordinates the work"
    },
```
## Despliegue en github pages

## Despliegue en netlify
