#Trousers.css#

###SCSS Essentials you shouldn't leave home without.###

Trousers is a lightweight foundation for any SCSS based project. Yes, it is similar to bootstrap; only simpler and less opinionated.

You should be familiar with how SASS (specifically SCSS) works. If not, more info can be found on the [SASS site](http://sass-lang.com/).

##Installation & Usage##
To wear Trousers you will first need to install SASS (3.3+) and a your choice of compiler, I recommend compass(1.0.1+).

####Install via bower:####
`bower install trousers`

####Install manually:####
To install Trousers simply include it in your project by cloning into your app's scss directory (e.g. /assets/scss/trousers).

####Usage####
To wear Trousers import `_trousers.scss` on the first line of your app's main scss file like so:
`@include /path/to/trousers/_trousers.scss`

##Features##
- Normalise.css and sensible tag presets.
- Helper classes (such as clearfix, floats etc).
- Common page layouts sets and simple grid system.
- Generic components such as buttons, switches, form styles, pagination, modals and more.
- Extendable Sass configuration & variables (overwrite Trouser settings in your own app to customise presets, mixins or components).

##Roadmap##
####Components####
- Notifications.
- Blockquotes (abstract from existing content_article).
- Lists (ul/ol).
- Nav lists.

####Syntax & Tools####
- Convert to BEM syntax method.
- Apply `SCSSLint`.
- Run through `SASSDOCS` to generate docs.
- Document usage autoprefix recommendation.

####Misc####
- Reduce nesting in CSS blocks (for selector performance inprovement).
- Abstract app specific styles (Trousers was originally a by-product of an app I created. Some of this app's remnants still exist as defaults & styles within Trousers.