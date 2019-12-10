## Change render syntax {{ }} of vuejs when using with Drupal twig

```javascript
new Vue({
  el: "#element_id",
  delimiters: ['${', '}'],
  data: {
    name : "Vuejs"
  }
  });
```

```html

<div class="item">
  <span>${ name }</span>
</div>

```
