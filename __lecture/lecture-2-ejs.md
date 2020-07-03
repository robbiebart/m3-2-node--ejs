# 3.2.2 - Module Spotlight: EJS

---

EJS is a **templating language**

---

# What is a templating language?

---

EJS is:

- Superset of HTML
- allows you to "mix" JS to create dynamic HTML

---

### Example

```html
<ol>
  <% friends.forEach((name) => { %>
  <li><%= name %></li>
  <% }); %>
</ol>
```

---

We **compile** a template to plain HTML.

---

```html
<ol>
  <% names.forEach((name) => { %>
  <li><%= name %></li>
  <% }); %>
</ol>
```

```js
let names = ['Anjula', 'Bouchard', 'Chad'];

ejs.render(str, names);
// => Rendered HTML string
```

```html
<ol>
  <li>Anjula</li>
  <li>Bouchard</li>
  <li>Chad</li>
</ol>
```

---

This is just scratching the surface.

You will want to _use the docs_ for today's workshop.

---

https://ejs.co/#docs

https://expressjs.com/en/guide/routing.html

---

You are going to see _lots_ of `EJS` in today's workshop.

Let's go over the workshop file together.

---
