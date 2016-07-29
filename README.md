# Easy BEM Structure

This Repository contains the structure necessary to work in a BEM envirepment. It doesn't include any build to compile and run an App (such as Gulp, Grunt, Webpack, etc).

#### Requirements
- Sass
- Jade
- BEM

Please see the doc links at the end of the readme.

### Instructions
Clone the Repo into your project and include the following files:
- `easylib/sass/easysass.scss`: Include this file in your main scss file. In case you're compiling each sass to css separatelly, include it in each sass file you're using BEM
- `easylib/bemto/easybem.jade`: Include this file in each Jade file you want to use BEM

### File Structure
- easylib
    - bemto: Jade structure
    - sass: Sass structure
- demos

### Jade vs Pug
Jade is changing the name to `Pug` (legal resons), but there are no any differences between Jade and Pug, BUT, if your file extension is Pug you cannot include Jade files. In this structure, I use Jade and I didn't create a new version based on Pug (for now).

# Documentation

### BEM:
[https://en.bem.info/methodology/key-concepts/](https://en.bem.info/methodology/key-concepts/)

### Jade:
[http://jade-lang.com/](http://jade-lang.com/)

### Sass:
[http://sass-lang.com/](http://sass-lang.com/)

### EasyBEM (based on BEMTO)
[https://github.com/kizu/bemto](https://github.com/kizu/bemto)

### EasySASS
I'm working on this section right now. Please see Demos.


-----

# Thanks
Thank to [https://github.com/kizu](Kizu) who creates BEMTO, a BEM lib I'm using in this structure.
