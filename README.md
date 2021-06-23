Handlebars.js: "Your code will be so simple!"

Handlebars.js Reality:

```html
{{#each value.Reactant}}
{{nullCheck this.$.LocalizedCompoundRef}}
{{#if (greater ../this.Reactant.length (add 1 @index))}}
+
{{/if}}
{{/each}}
```
