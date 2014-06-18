Maxrelax Sass Library
---

Common Sass mixins, functions, and resets for internal + external projects.

- - -

### Usage

Clone into your vendor styles directory.

```bash
cd app/styles/vendor
git clone git@github.com:Maxrelax/lib-sass.git maxrelax
```

Import everything into your project from another sass file (ie: `main.sass`)

```sass
@import vendor/maxrelax/all
```

Or only specific libs:
```sass
@import vendor/maxrelax/vars/_colors // imports only our color variables
@import vendor/maxrelax/mixins/__all // imports all mixins
```
- - -

### Contact

* [maxrelax.co][]
* [hello@maxrelax.co][]

### License

MIT

[maxrelax.co]: http://maxrelax.co "Maxrelax"
[hello@maxrelax.co]: mailto:hello@maxrelax.co "Email hello@maxrelax.co"
