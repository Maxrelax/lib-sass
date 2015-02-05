![maxrelax-icon]

# powpow Sass Library

Common Sass mixins, functions, and resets for internal + external projects at **Maxrelax**.

### Installation

##### option a) as a simple git checkout

```bash
# replace 'app/styles/vendor' with a directory of your choice
cd app/styles/vendor
git clone https://github.com/maxrelax/powpow.git
```

##### option b) as a submodule

```bash
# replace 'app/styles/vendor/powpow' with a directory of your choice
git add submodule https://github.com/maxrelax/powpow.git app/styles/vendor/powpow
git submodule init
git submodule update
```

If changes to the submodule have `git` bothering you with warnings, you can
add a special `ignore` flag to your `.gitmodules` file:

```
[submodule "assets/sass/vendor/powpow"]
    path = assets/sass/vendor/powpow
    url = https://github.com/maxrelax/powpow.git
    ignore = dirty
```


### Usage

Import powpow into your project from another sass file (ie: `app/styles/main.sass`)

```sass
@import vendor/powpow/powpow
```

<br>


### Contact
* [maxrelax.co][]
* [hello@maxrelax.co][]

### License

MIT

[maxrelax.co]: https://maxrelax.co "Maxrelax"
[hello@maxrelax.co]: mailto:hello@maxrelax.co "Email hello@maxrelax.co"
[maxrelax-icon]: http://i.imgur.com/VEgmzp5.png "Maxrelax - Hey girl, wanna take a nap?"
