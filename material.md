# Foundation

## [1 Mikä on Foundation](#1)

>### [1.1 Sass](#11)
>
>### [1.2 Foundationin hyödyt](#12)
>
>### [1.3 Foundation vs Bootstrap](#13)

## [2 Asentaminen](#2)

## [3 Tiedostojen muokkaaminen](#3)

## [4 UI komponentit](#4)

>### [4.1 General](#41)
>
>>### [4.1.1 Typography](#411)
>>
>>### [4.1.2 Forms](#412)
>>
>>### [4.1.3 Visibility Classes](#413)

>### [4.2 Grid](#42)
>
>>### [4.2.1 XY Grid](#421)

>### [4.3 Controls](#43)
>
>>### [4.3.1 Buttons](#431)
>>
>>### [4.3.2 Close Button](#432)
>>
>>### [4.3.3 Button Group](#433)
>>
>>### [4.3.4 Slider](#434)
>>
>>### [4.3.5 Switch](#435)

>### [4.4 Navigation](#44)
>
>>### [4.4.1 Menu](#441)
>>
>>### [4.4.2 Dropdown Menu](#442)
>>
>>### [4.4.3 Top Bar](#443)
>>
>>### [4.4.4 Breadcrumbs](#444)
>>
>>### [4.4.5 Pagination](#445)

>### [4.5 Containers](#45)
>
>>### [4.5.1 Dropdown](#451)
>>
>>### [4.5.2 Off Canvas](#452)
>>
>>### [4.5.3 Tabs](#453)

>### [4.6 Media](#46)
>
>>### [4.6.1 Responsive Embed](#461)
>>
>>### [4.6.2 Label](#462)
>>
>>### [4.6.3 Orbit](#463)
>>
>>### [4.6.4 Progress Bar](#464)
>>
>>### [4.6.5 Tooltip](#465)

>### [4.7 Icons](#47)

>### [4.8 Plugins](#48)
>
>>### [4.8.1 Toggler](#481)
>>
>>### [4.8.2 Sticky](#482)

## [5. Tehtävät](#5)

>### [5.1 Tehtävä 1](#51)

## Mitä käydään läpi

- Foundation lyhyesti
- Asennus
- Tiedostojen muokkaus
- Foundation for Sites
- HTML / CSS komponentteja
- Grid

<a id='1'></a>

## 1. Mikä on Foundation

[Foundation](https://foundation.zurb.com/) on edistyksellinen ja responsiivinen frontend ohjelmistokehys. Vuonna 2011 julkaistu open source projekti, jota ylläpitää [ZURB](https://zurb.com/).

Ohjelmistokehyksen kirjoittamiseen on käytetty: HTML, CSS, Sass ja JavaScript.

Kirjoitushetkellä uusin versio on 6.5.3.

Ohjelmistokehystä käytetään nettisivujen frontendissa ja sovellusten käyttöliittymissä.

Foundation tarjoaa muun muassa:

- Foundation for sites

- Foundation for emails

- Mobile first design

- Responsiivinen grid

- HTML ja CSS UI:

  - Komponentteja

  - Templaatteja

  - Koodi snippetit

- Funktionaalisuutta JavaScript lisäosilla

<a id='11'></a>

### 1.1 Sass

Foundation hyödyntää CSS lisäosaa nimeltä [Sass](https://sass-lang.com/).

Sass tuo paljon hyödyllisiä asioita mukanaan:

- Variables
- Nesting
- Partials
- Modules
- Mixins
- Extend/Inheritance
- Operators

<a id='12'></a>

### 1.2 Foundationin hyötyjä

- Mahdollistaa nopeaan UI/UX kehittämiseen.

- Puhdasta ja siistiä koodia.

- Responsiivisuus

- Optimoitu kaikille näytöille

- Johdonmukainen

- Räätälöitävyys

<a id='13'></a>

### 1.3 Foundation vs Bootstrap

Foundation on hyvin saman tyylinen kuin [Twitter Bootstrap](https://getbootstrap.com/). Suoraan ei voi sanoa kumpi kehyksistä on parempi, mutta alla on mainittu muutamia vaikuttavia tekijöitä.

Bootstrap:

- Suositumpi
- Enemmän  tukea ja resursseja
- Helpompi saada apua
- Helpompi syntaksi
- Nopeampi käyttää
- Käyttää Less ja Sass

Foundation:

- Enemmän hyötyä kokeneemmille kehittäjille
- Enemmän muokattavuutta
- Tarjoaa palveluja nettisivujen lisäksi sähköposteille
- Käyttää Sass

[Tässä](https://blog.templatetoaster.com/bootstrap-vs-foundation/) artikkelissa on vertailtu tarkemmin kyseisiä kehyksiä.

<a id='2'></a>

## 2. Asentaminen

Foundation ohjelmistokehyksen voi asentaa monella eri tavalla. Alla on mainittu neljä yleisintä. Viralliset ohjeet löydät [täältä](https://foundation.zurb.com/sites/docs/installation.html).

- Manuaalisesti tiedostojen lataaminen

  - [Foundation lataussivu](https://foundation.zurb.com/sites/download/)

  - Helpoin vaihtoehto on valita COMPLETE-versio, joka lataa kaiken tarvittavan HTML ja JavaScriptin.

- CDN

- Foundation CLI

  - Asentaa Foundation CLI:n

          $ npm install --global foundation-cli

  - Luo uuden Foundation projektin

          $ foundation new

    [Tarkemmat ohjeet](https://github.com/foundation/foundation-cli)

- Paketinhallinta (npm, Bower, Meteor, Composer)

        $ npm install foundation-sites

  [Tarkemmat ohjeet](https://www.npmjs.com/package/foundation-sites)

<a id='3'></a>

## 3. Tiedostojen muokkaaminen

Foundation on tehty muokattavaksi. Virallinen [dokumentaatio](https://foundation.zurb.com/sites/docs/global.html) kertoo muun muassa miten globaaleja muuttujia voidaan muokata omaan projektiin sopivaksi.

<a id='4'></a>

## 4. UI komponentit

Käydään läpi erilaisia komponentteja, kuten XY Grid, Buttons, Menu, Tabs ja Forms. Kaikki alempana mainitut komponentit ovat nimetty englanniksi, jotta alkuperäisen [dokumentaation](https://foundation.zurb.com/sites/docs/) lukeminen on helpompaa.

<a id='41'></a>

## 4.1 General

<a id='411'></a>

### 4.1.1 Typography

Sisältää valmiiksi tehtyjä tyylejä perinteisen typografian elementeille ja tageille kuten:

- paragraphs
- headers
- links
- dividers
- lists
- blockquotes
- code
- keystrokes

[Dokumentit](https://foundation.zurb.com/sites/docs/typography-base.html)

Sisältää erilaisia valmiiksi tehtyjä luokkia auttamaan asioissa kuten:

- text alignment
- subheader
- un-bulleted list
- typescale
- statistics

[Dokumentit](https://foundation.zurb.com/sites/docs/typography-helpers.html)

<a id='412'></a>

### 4.1.2 Forms

Esimerkki

```
<form>
  <div class="grid-container">
    <div class="grid-x grid-padding-x">
      <div class="medium-6 cell">
        <label>Input Label
          <input type="text" placeholder=".medium-6.cell">
        </label>
      </div>
      <div class="medium-6 cell">
        <label>Input Label
          <input type="text" placeholder=".medium-6.cell">
        </label>
      </div>
    </div>
  </div>
</form>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/forms.html)

<a id='413'></a>

### 4.1.3 Visibility Classes

Esimerkkejä

```
<p>You are on a small screen or larger.</p>
<p class="show-for-medium">You are on a medium screen or larger.</p>
<p class="show-for-large">You are on a large screen or larger.</p>
```

```
<p class="hide-for-small-only">You are <em>definitely not</em> on a small screen.</p>
<p class="hide-for-medium-only">You are <em>definitely not</em> on a medium screen.</p>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/visibility.html)

<a id='42'></a>

## 4.2 Grid

<a id='421'></a>

### 4.2.1 XY Grid

XY Grid on kohtuullisen uusi, mutta se toimii kaikissa uusimmissa selaimissa.
Tämän avulla responsiivisten sivujen tekeminen on nopeaa ja helppoa.

Esimerkki Grid-X

```
<div class="grid-x">
  <div class="cell">full width cell</div>
  <div class="cell">full width cell</div>
</div>
<div class="grid-x">
  <div class="cell small-6">6 cells</div>
  <div class="cell small-6">6 cells</div>
</div>
<div class="grid-x">
  <div class="cell medium-6 large-4">12/6/4 cells</div>
  <div class="cell medium-6 large-8">12/6/8 cells</div>
</div>
```

Esimerkki Grid-Y

```
<div class="grid-y" style="height: 500px;">
  <div class="cell small-6 medium-8 large-2">
    6/8/2
  </div>
  <div class="cell small-6 medium-4 large-10">
    6/4/10
  </div>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/xy-grid.html)

<a id='43'></a>

## 4.3 Controls

<a id='431'></a>

### 4.3.1 Buttons

Esimerkkejä

```
<!-- Anchors (links) -->
<a href="about.html" class="button">Learn More</a>
<a href="#features" class="button">View All Features</a>

<!-- Buttons (actions) -->
<button type="button" class="success button">Save</button>
<button type="button" class="alert button">Delete</button>
```

```
<button class="hollow button" href="#">Primary</button>
<button class="hollow button secondary" href="#">Secondary</button>

<a class="button disabled" href="#" aria-disabled>Disabled</a>
<button type="button" class="button primary" disabled>Disabled</button>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/button.html)

<a id='432'></a>

### 4.3.2 Close Button

Esimerkki

```
<div class="callout" data-closable>
  <button class="close-button" aria-label="Close alert" type="button" data-close>
    <span aria-hidden="true">&times;</span>
  </button>
  <p>Look at this close button!</p>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/close-button.html)

<a id='433'></a>

### 4.3.3 Button Group

Esimerkki

```
<div class="button-group">
  <a class="button">One</a>
  <a class="button">Two</a>
  <a class="button">Three</a>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/button-group.html)

<a id='434'></a>

### 4.3.4 Slider

Esimerkki

```
<div class="slider" data-slider data-initial-start="50" data-end="200">
  <span class="slider-handle"  data-slider-handle role="slider" tabindex="1"></span>
  <span class="slider-fill" data-slider-fill></span>
  <input type="hidden">
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/slider.html)

<a id='435'></a>

### 4.3.5 Switch

Esimerkki

```
<div class="switch">
  <input class="switch-input" id="exampleSwitch" type="checkbox" name="exampleSwitch">
  <label class="switch-paddle" for="exampleSwitch">
    <span class="show-for-sr">Download Kittens</span>
  </label>
</div>

```

[Dokumentit](https://foundation.zurb.com/sites/docs/switch.html)

<a id='44'></a>

## 4.4 Navigation

<a id='441'></a>

### 4.4.1 Menu

Esimerkki

```
<ul class="menu align-right">
  <li><a href="#">One</a></li>
  <li><a href="#">Two</a></li>
  <li><a href="#">Three</a></li>
  <li><a href="#">Four</a></li>
</ul>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/menu.html)

<a id='442'></a>

### 4.4.2 Dropdown Menu

Esimerkki

```
<ul class="dropdown menu" data-dropdown-menu>
  <li>
    <a href="#">Item 1</a>
    <ul class="menu">
      <li><a href="#">Item 1A</a></li>
    </ul>
  </li>
  <li><a href="#">Item 2</a></li>
  <li><a href="#">Item 3</a></li>
  <li><a href="#">Item 4</a></li>
</ul>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/dropdown-menu.html)


<a id='443'></a>

### 4.4.3 Top Bar

Esimerkki

```
<div class="top-bar">
  <div class="top-bar-left">
    <ul class="dropdown menu" data-dropdown-menu>
      <li class="menu-text">Site Title</li>
      <li>
        <a href="#">One</a>
        <ul class="menu vertical">
          <li><a href="#">One</a></li>
          <li><a href="#">Two</a></li>
          <li><a href="#">Three</a></li>
        </ul>
      </li>
      <li><a href="#">Two</a></li>
      <li><a href="#">Three</a></li>
    </ul>
  </div>
  <div class="top-bar-right">
    <ul class="menu">
      <li><input type="search" placeholder="Search"></li>
      <li><button type="button" class="button">Search</button></li>
    </ul>
  </div>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/top-bar.html#)


<a id='444'></a>

### 4.4.4 Breadcrumbs

Esimerkki

```
<nav aria-label="You are here:" role="navigation">
  <ul class="breadcrumbs">
    <li><a href="#">Home</a></li>
    <li><a href="#">Features</a></li>
    <li class="disabled">Gene Splicing</li>
    <li>
      <span class="show-for-sr">Current: </span> Cloning
    </li>
  </ul>
</nav>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/breadcrumbs.html)

<a id='445'></a>

### 4.4.5 Pagination

Esimerkki

```
<nav aria-label="Pagination">
  <ul class="pagination">
    <li class="pagination-previous disabled">Previous <span class="show-for-sr">page</span></li>
    <li class="current"><span class="show-for-sr">You're on page</span> 1</li>
    <li><a href="#" aria-label="Page 2">2</a></li>
    <li><a href="#" aria-label="Page 3">3</a></li>
    <li><a href="#" aria-label="Page 4">4</a></li>
    <li class="ellipsis" aria-hidden="true"></li>
    <li><a href="#" aria-label="Page 12">12</a></li>
    <li><a href="#" aria-label="Page 13">13</a></li>
    <li class="pagination-next"><a href="#" aria-label="Next page">Next <span class="show-for-sr">page</span></a></li>
  </ul>
</nav>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/pagination.html)

<a id='45'></a>

## 4.5 Containers

<a id='451'></a>

### 4.5.1 Dropdown

Esimerkki

```
<button class="button" type="button" data-toggle="example-dropdown2">Top Aligned</button>

<div class="dropdown-pane top" id="example-dropdown2" data-dropdown>
  Just some junk that needs to be said. Or not. Your choice.
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/dropdown.html)


<a id='452'></a>

### 4.5.2 Off Canvas

Esimerkki

```
<div class="off-canvas-wrapper">
  <div class="off-canvas position-left" id="offCanvas" data-off-canvas>
    <h2>Content</h2>
  </div>
  <div class="off-canvas-content" data-off-canvas-content>
    <h2>Content</h2>
    <button type="button" class="button" data-toggle="offCanvas">Open Menu</button>
  </div>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/off-canvas.html)


<a id='453'></a>

### 4.5.3 Tabs

Esimerkki

```
<ul class="tabs" data-tabs id="example-tabs">
  <li class="tabs-title is-active"><a href="#panel1" aria-selected="true">Tab 1</a></li>
  <li class="tabs-title"><a data-tabs-target="panel2" href="#panel2">Tab 2</a></li>
</ul>

<div class="tabs-content" data-tabs-content="example-tabs">
  <div class="tabs-panel is-active" id="panel1">
    <p>Vivamus hendrerit arcu sed erat molestie vehicula. Sed auctor neque eu tellus rhoncus ut eleifend nibh
      porttitor. Ut in nulla enim. Phasellus molestie magna non est bibendum non venenatis nisl tempor. Suspendisse
      dictum feugiat nisl ut dapibus.</p>
  </div>
  <div class="tabs-panel" id="panel2">
    <p>Suspendisse dictum feugiat nisl ut dapibus. Vivamus hendrerit arcu sed erat molestie vehicula. Ut in nulla
      enim. Phasellus molestie magna non est bibendum non venenatis nisl tempor. Sed auctor neque eu tellus rhoncus
      ut eleifend nibh porttitor.</p>
  </div>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/tabs.html)

<a id='46'></a>

## 4.6 Media

<a id='461'></a>

### 4.6.1 Responsive Embed

Esimerkki

```
<div class="responsive-embed">
  <iframe width="420" height="315" src="https://www.youtube.com/embed/mM5_T-F1Yn4" frameborder="0" allowfullscreen></iframe>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/responsive-embed.html)


<a id='462'></a>

### 4.6.2 Label

Esimerkki

```
<span class="label primary">Primary Label</span>
<span class="label secondary">Secondary Label</span>
<span class="label success">Success Label</span>
<span class="label alert">Alert Label</span>
<span class="label warning">Warning Label</span>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/label.html)


<a id='463'></a>

### 4.6.3 Orbit

Esimerkki

```
<div class="orbit" role="region" aria-label="Favorite Space Pictures" data-orbit>
  <div class="orbit-wrapper">
    <div class="orbit-controls">
      <button class="orbit-previous"><span class="show-for-sr">Previous Slide</span>&#9664;&#xFE0E;</button>
      <button class="orbit-next"><span class="show-for-sr">Next Slide</span>&#9654;&#xFE0E;</button>
    </div>
    <ul class="orbit-container">
      <li class="is-active orbit-slide">
        <figure class="orbit-figure">
          <img class="orbit-image" src="https://placehold.it/1200x600/999?text=Slide-1" alt="Space">
          <figcaption class="orbit-caption">Space, the final frontier.</figcaption>
        </figure>
      </li>
      <li class="orbit-slide">
        <figure class="orbit-figure">
          <img class="orbit-image" src="https://placehold.it/1200x600/888?text=Slide-2" alt="Space">
          <figcaption class="orbit-caption">Lets Rocket!</figcaption>
        </figure>
      </li>
      <li class="orbit-slide">
        <figure class="orbit-figure">
          <img class="orbit-image" src="https://placehold.it/1200x600/777?text=Slide-3" alt="Space">
          <figcaption class="orbit-caption">Encapsulating</figcaption>
        </figure>
      </li>
      <li class="orbit-slide">
        <figure class="orbit-figure">
          <img class="orbit-image" src="https://placehold.it/1200x600/666&text=Slide-4" alt="Space">
          <figcaption class="orbit-caption">Outta This World</figcaption>
        </figure>
      </li>
    </ul>
  </div>
  <nav class="orbit-bullets">
    <button class="is-active" data-slide="0">
      <span class="show-for-sr">First slide details.</span>
      <span class="show-for-sr" data-slide-active-label>Current Slide</span>
    </button>
    <button data-slide="1"><span class="show-for-sr">Second slide details.</span></button>
    <button data-slide="2"><span class="show-for-sr">Third slide details.</span></button>
    <button data-slide="3"><span class="show-for-sr">Fourth slide details.</span></button>
  </nav>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/orbit.html)


<a id='464'></a>

### 4.6.4 Progress Bar

Esimerkki

```
<div class="progress" role="progressbar" tabindex="0" aria-valuenow="25" aria-valuemin="0" aria-valuetext="25 percent" aria-valuemax="100">
  <span class="progress-meter" style="width: 25%">
    <p class="progress-meter-text">25%</p>
  </span>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/progress-bar.html)


<a id='465'></a>

### 4.6.5 Tooltip

Esimerkki

```
The <span data-tooltip tabindex="1" title="Fancy word for a beetle.">scarabaeus</span> hung quite
clear of any branches, and, if allowed to fall, would have fallen at our feet.
```

[Dokumentit](https://foundation.zurb.com/sites/docs/tooltip.html)


<a id='47'></a>

## 4.7 Icons

Ladataan erikseen [täältä](https://zurb.com/playground/foundation-icon-fonts-3).

Lisätään linkit tiedostoihin

```
<link rel="stylesheet" href="foundation-icons/foundation-icons.css">
<link rel="stylesheet" href="foundation-icons/foundation-icons.[eot/ttf/svg/woff]">
```

Käytetään esimerkiksi seuraavasti

```
<i class="fi-social-facebook"></i>
```

<a id='48'></a>

## 4.8 Plugins

<a id='481'></a>

### 4.8.1 Toggler

Esimerkki

```
<p><a data-toggle="panel">Toggle Panel</a></p>

<div class="callout" id="panel" data-toggler data-animate="hinge-in-from-top spin-out">
  <h4>Hello!</h4>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dicta quas optio alias voluptas nobis iusto mollitia asperiores incidunt reprehenderit doloribus voluptatibus officiis minus, inventore, quasi nisi. Consequuntur, quidem. Sint, dicta?</p>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/toggler.html#)


<a id='482'></a>

### 4.8.2 Sticky

Esimerkki

```
<div class="cell small-6 right" data-sticky-container>
  <div class="sticky" data-sticky data-margin-top="0">
    <img class="thumbnail" src="assets/img/generic/rectangle-3.jpg">
    <!-- This sticky element would stick to the window, with a marginTop of 0 -->
  </div>
</div>

<div class="cell small-6 right" data-sticky-container>
  <div class="sticky" data-sticky data-anchor="foo">
    <img class="thumbnail" src="assets/img/generic/rectangle-3.jpg">
    <!-- This sticky element would stick to the window for the height of the element #foo, with a 1em marginTop -->
  </div>
</div>
```

[Dokumentit](https://foundation.zurb.com/sites/docs/sticky.html)

<a id='5'></a>

## 5. Tehtävät

Valitse toinen alla olevista tehtävistä.

<a id='51'></a>

### 5.1 Tehtävä 1

Tehtävänä on toteuttaa portfolio nettisivu Foundation ohjelmistokehyksen avulla. Tehtävät kansion Tehtävä1 kansiosta löytyy index.html -tiedosto, jonka pohjalta sivu toteutetaan. Tiedostoon on kommentoitu kohdat, joihin täytyy lisätä luokkia. Kansiosta löytyy myös kuvat eri näyttöjen kuvakaappauksista.

Vaatimuksena:

- Sivu on responsiivinen
- Sivu näyttää mahdollisimman paljon samalta, kuin valmiiden sivujen kuvakaappaukset

Tehtävä kannattaa aloittaa lisäämällä/asentamalla Foundation projektiin itse valitsemalla tavalla. Tehtävän tekeminen onnistuu ilman tyylitiedostojen muokkaamista. Riittää, kun lisäät oikeat luokat.

Palauta pakattu kansio, joka sisältää vähintään:

- index.html -tiedoston
- foundation -tiedostot (paitsi jos käytetty CDN)
- mahdolliset sivulla käytetyt kuvat


<a id='52'></a>

### 5.2 Tehtävä 2

Toteuta responsiivinen nettisivu valitsemastasi aiheesta.

Vaatimuksena:

- Tyylit on tehty pääasiassa Foundationilla
- Sivu on responsiivinen (XY Grid)
- Vähintään viittä eri Foundation komponenttia on käytetty
- Sivu näyttää kohtuullisen siistiltä

Palauta pakattu kansio, joka sisältää vähintään:

- index.html -tiedoston
- foundation -tiedostot (paitsi jos käytetty CDN)
- mahdolliset sivulla käytetyt kuvat
