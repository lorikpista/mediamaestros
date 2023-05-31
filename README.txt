
TITLE: 
Aesthetic - 100% Fully Responsive Free HTML5 Bootstrap Template

AUTHOR:
DESIGNED & DEVELOPED by GetTemplates.co

Website: http://gettemplates.co/
Twitter: http://twitter.com/gettemplatesco
Facebook: http://facebook.com/gettemplatesco


CREDITS:

Bootstrap
http://getbootstrap.com/

jQuery
http://jquery.com/

jQuery Easing
http://gsgd.co.uk/sandbox/jquery/easing/

Modernizr
http://modernizr.com/

Google Fonts
https://www.google.com/fonts/

Icomoon
https://icomoon.io/app/

Respond JS
https://github.com/scottjehl/Respond/blob/master/LICENSE-MIT

animate.css
http://daneden.me/animate

jQuery Waypoint
https://github.com/imakewebthings/waypoints/blog/master/licenses.txt

Owl Carousel
http://www.owlcarousel.owlgraphic.com/

jQuery countTo
http://www.owlcarousel.owlgraphic.com/

Magnific Popup
http://dimsemenov.com/plugins/magnific-popup/

Demo Images:
http://unsplash.com


style.css:
gtco-nav-toggle.active i::before, .gtco-nav-toggle.active i::after {
  background: #444;
}
.gtco-nav-toggle:hover, .gtco-nav-toggle:focus, .gtco-nav-toggle:active {
  outline: none;
  border-bottom: none !important;
}
.gtco-nav-toggle i {
  position: relative;
  display: inline-block;
  width: 25px;
  height: 2px;
  color: #252525;
  font: bold 14px/.4 Helvetica;
  text-transform: uppercase;
  text-indent: -55px;
  background: #252525;
  transition: all .2s ease-out;
}
.gtco-nav-toggle i::before, .gtco-nav-toggle i::after {
  content: '';
  width: 25px;
  height: 2px;
  background: #252525;
  position: absolute;
  left: 0;
  transition: all .2s ease-out;
}
.gtco-nav-toggle> i {
  color: #fff;
  background: #fff;
}
.gtco-nav-toggle > i::before, .gtco-nav-toggle > i::after {
  background: #fff;
}

.gtco-nav-toggle i::before {
  top: -7px;
}

.gtco-nav-toggle i::after {
  bottom: -7px;
}

.gtco-nav-toggle:hover i::before {
  top: -10px;
}

.gtco-nav-toggle:hover i::after {
  bottom: -10px;
}

.gtco-nav-toggle.active i {
  background: transparent;
}

.gtco-nav-toggle.active i::before {
  top: 0;
  -webkit-transform: rotateZ(45deg);
  -moz-transform: rotateZ(45deg);
  -ms-transform: rotateZ(45deg);
  -o-transform: rotateZ(45deg);
  transform: rotateZ(45deg);
}

.gtco-nav-toggle.active i::after {
  bottom: 0;
  -webkit-transform: rotateZ(-45deg);
  -moz-transform: rotateZ(-45deg);
  -ms-transform: rotateZ(-45deg);
  -o-transform: rotateZ(-45deg);
  transform: rotateZ(-45deg);
}

.gtco-nav-toggle {
  position: absolute;
  right: 0px;
  top: 10px;
  z-index: 21;
  padding: 6px 0 0 0;
  display: block;
  margin: 0 auto;
  display: none;
  height: 44px;
  width: 44px;
  z-index: 2001;
  border-bottom: none !important;
}
@media screen and (max-width: 768px) {
  .gtco-nav-toggle {
    display: block;
  }
}