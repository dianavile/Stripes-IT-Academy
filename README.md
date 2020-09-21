# SASS- ITAcademy Stripes

## Set up SASS Project

Build with Live Sass Compiler in Visual Studio Code

## ITERATION 1: Build 5 blocks

1. Print on screen 5 blocks (20% of screenwidth) with the word "IT A CA DE MY" and font "Lato"
2. Give each block a different background-color:
   Block 1: #244F75; Block 2: #60BFBF; Block 3: #8C4B7E; Block 4: #F8BB44; Block 5: #F24B4B;

## ITERATION 2: Build the stripes

1. Create :before with skew()

```
.strips .strip__content:before {
  content: "";
  position: absolute;
  z-index: 1;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: white;
  opacity: 0.05;
  -webkit-transform-origin: center center;
          transform-origin: center center;
  -webkit-transform: skew(30deg) scaleY(1) translate(0, 0);
          transform: skew(30deg) scaleY(1) translate(0, 0);
  transition: all 0.6s cubic-bezier(0.23, 1, 0.32, 1);
}
```

## ITERATION 3: ADD CSS ANIMATIONS (MOUSE EVENT)

3. When hover on an element with the mouse, change the screen with an CSS overlay effect.

## ITERATION 4: ADD CSS ANIMATIONS TO ALL ELEMENTS

4.  Add animation, when the block elements enter the screen (on load):

```
@keyframes stripe1 {
0% {
-webkit-transform: translate3d(-100%, 0, 0);
transform: translate3d(-100%, 0, 0);
}
100% {
-webkit-transform: translate3d(0, 0, 0);
transform: translate3d(0, 0, 0);
}
}
```

### RESOURCES

#### Videos:

- [Aprende Sass en 20 minutos](https://www.youtube.com/watch?v=xu0lVyrA8Y0)

#### Articles:

- [CSS animations](https://www.creativebloq.com/inspiration/css-animation-examples)
- [CSS Content](https://css-tricks.com/css-content/)
- [CSS Animations & Keyframes](https://www.youtube.com/watch?v=f1WMjDx4snI)
- [Before](https://www.w3schools.com/cssref/sel_before.asp)
- [Skew](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/skew)
- [Line-height](https://stackoverflow.com/questions/2040788/whats-the-difference-between-line-height1-5-and-line-height150-in-css)
- [PixeltoRem-converter](https://www.ninjaunits.com/converters/pixels/pixels-rem/)
- [Media Queries-SASS/SCSS](https://www.youtube.com/watch?v=r9fZZpcfdXg&feature=youtu.be)
- [SASS Extend](https://www.youtube.com/watch?v=is87ILGUQWU&feature=youtu.be)
- [Before-After](https://www.youtube.com/watch?v=zGiirUiWslI)
- [Screensizes-Mediaqueries](https://screensiz.es/)
- [EM, REM](https://www.programandoamedianoche.com/2018/02/como-funcionan-em-y-rem/)
- [Sizing-value-elements](hhttps://developer.mozilla.org/ca/docs/Learn/CSS/Building_blocks/Valors_i_unitats_CSS)
- [Security issue CSS stylesheet-Google Chrome](https://stackoverflow.com/questions/48753691/cannot-access-cssrules-from-local-css-file-in-chrome-64/49160760#49160760)
- [Organizing Sass](https://www.youtube.com/watch?v=qUnIReTCsZY&feature=youtu.be)
- [SASS-Intro, Installacion](https://www.youtube.com/watch?v=Nro1WwTdCK4)
- [SASS mixins](https://www.youtube.com/watch?v=eazZiFtmGPE)
- [Striped background animation](https://css-tricks.com/striped-background-gradients/)
