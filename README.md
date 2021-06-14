Handlebars.js: "Minimal templating"

Also Handlebars.js:

```html
{{#each ReactionContext}}
{{#each this.LocalizedCompoundSpec}}
{{~this.Diffusion~}}
[{{../../../this.Model.[0].ModelUnitSystem.[0].$.AreaUnit~}}
/{{../../../this.Model.[0].ModelUnitSystem.[0].$.TimeUnit}}]
{{~/each~}}
{{~/each~}}
```
