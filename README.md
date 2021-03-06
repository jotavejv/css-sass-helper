# CSS helper

This scss file provides a class utilities based on **emmet** syntax with just unique purpose: manipulate static values in **margin** and **position**. There is a **font-size** manager too.

The generated values range is 1 to 100px, you can use:

| margin        | position           | font-size  | values
| ------------- |:-------------:| :-----:| :-----:|
| mt      | t |  fz  | 1 - 100px |
| mb      | b | | 1 - 100px |
| mr      | r |  | 1 - 100px |
| ml      | l |  | 1 - 100px |

## How to install
You can use the generated css file from [cdn](https://cdn.rawgit.com/jotavejv/css-helper/master/helpers.css) `https://cdn.rawgit.com/jotavejv/css-helper/master/helpers.css` or download this repo.
If you prefer using `bower` just install it `bower install css-sass-helper`.

## How to use
In your sass file import the ***_helpers.scss*** if you have downloaded it or if you are using `bower` just import from `bower_components/css-sass-helper/_helpers.scss`

```scss
@import 'helpers.scss'
```
OR
```scss
@import 'bower_components/css-sass-helper/_helpers.scss'
```
## Basic examples

```html

<p class="fz14">Lorem ipsum</p>

```
``` css
.fz14 {
  font-size: 14px;
}
```

```html

<div class="mt20">Lorem ipsum</div>

```
``` css
.mt20 {
  margin-top: 20px;
}
```

# Important
The CSS file generated from this helper is a lot of classes, so keep in mind the performance and use some *clean up css tool*. I Strongly recommend the [purify-css](https://github.com/purifycss/purifycss)

### Why?
Sometimes we don't have much time and we need make the job faster, and create new classes for simple tasks like *positions*, *margins* and *font-sizes* consume a time.This "helper" helps do these boring tasks when we are in a rush. But this it isn't the best approach, knowing that you can improve your html and css by creating custom and reusables classes.
