---
title: "My First Post"
date: 2017-12-24T10:04:05-05:00
draft: true
---
## Hi there

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo, amet praesentium. Quas tempore magni numquam culpa similique assumenda quod nisi impedit in dolorum expedita cumque, ipsum quasi excepturi odit officiis?

```html
<section id="main">
  <div>
    <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```