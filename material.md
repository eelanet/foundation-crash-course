# Foundation

## Sisällysluettelo

## [1 Mikä on Foundation](#1)

### [1.1 Sass](#11)

### [1.2 Foundationin hyödyt](#12)

### [1.3 Foundation vs Bootstrap](#13)

## [2 Asentaminen](#2)

## [3 Tiedostojen muokkaaminen](#3)

## [4 UI komponentit](#4)

### [4.1 General](#41)

## [4.1.1 Typography](#411)

### [4.1.2 Forms](#412)

### [4.1.3 Visibility Classes](#413)

### [4.2 Grid](#42)

### [4.2.1 XY Grid](#421)

### [4.3 Controls](#43)

### [4.3.1 Buttons](#431)

### [4.3.2 Close Button](#432)

### [4.3.3 Button Group](#433)

### [4.3.4 Slider](#434)

### [4.3.5 Switch](#435)

### [4.4 Navigation](#44)

### [4.4.1 Menu](#441)

### [4.4.2 Dropdown Menu](#442)

### [4.4.3 Top Bar](#443)

### [4.4.4 Breadcrumbs](#444)

### [4.4.5 Pagination](#445)

### [4.5 Containers](#45)

### [4.5.1 Dropdown](#451)

### [4.5.2 Off Canvas](#452)

### [4.5.3 Tabs](#453)

### [4.5.4 Table](#454)

### [4.6 Media](#46)

### [4.6.1 Responsive Embed](#461)

### [4.6.2 Label](#462)

### [4.6.3 Orbit](#463)

### [4.6.4 Progress Bar](#464)

### [4.6.5 Tooltip](#465)

### [4.7 Icons](#47)

### [4.8 Plugins](#48)

### [4.8.1 Toggler](#481)

### [4.8.2 Smooth Scroll](#482)

### [4.8.3 Sticky](#483)

## [5. Tehtävät](#5)

### [5.1 Tehtävä 1](#51)

### [5.2 Tehtävä 2](#52)

## Mitä käydään läpi

- Foundation lyhyesti
- Asennus
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

- Paketinhallinta (npm, Bower, Meteor, Composer)

        $ npm install foundation-sites

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

Sisältää erilaisia valmiiksi tehtyjä luokkia auttamaan asioissa kuten:

- text alignment
- subheader
- un-bulleted list
- typescale
- statistics

<a id='412'></a>

### 4.1.2 Forms

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

<a id='413'></a>

### 4.1.3 Visibility Classes

<a id='42'></a>

## 4.2 Grid

<a id='421'></a>

### 4.2.1 XY Grid

<a id='43'></a>

## 4.3 Controls

<a id='431'></a>

### 4.3.1 Buttons

    <!-- Anchors (links) -->
    <a href="about.html" class="button">Learn More</a>
    <a href="#features" class="button">View All Features</a>

    <!-- Buttons (actions) -->
    <button type="button" class="success button">Save</button>
    <button type="button" class="alert button">Delete</button>

<a id='432'></a>

### 4.3.2 Close Button

<a id='433'></a>

### 4.3.3 Button Group

<a id='434'></a>

### 4.3.4 Slider

<a id='435'></a>

### 4.3.5 Switch

<a id='44'></a>

## 4.4 Navigation

<a id='441'></a>

### 4.4.1 Menu

<a id='442'></a>

### 4.4.2 Dropdown Menu

<a id='443'></a>

### 4.4.3 Top Bar

<a id='444'></a>

### 4.4.4 Breadcrumbs

<a id='445'></a>

### 4.4.5 Pagination

<a id='45'></a>

## 4.5 Containers

<a id='451'></a>

### 4.5.1 Dropdown

<a id='452'></a>

### 4.5.2 Off Canvas

<a id='453'></a>

### 4.5.3 Tabs

<a id='454'></a>

### 4.5.4 Table

<a id='46'></a>

## 4.6 Media

<a id='461'></a>

### 4.6.1 Responsive Embed

<a id='462'></a>

### 4.6.2 Label

<a id='463'></a>

### 4.6.3 Orbit

<a id='464'></a>

### 4.6.4 Progress Bar

<a id='465'></a>

### 4.6.5 Tooltip

<a id='47'></a>

## 4.7 Icons

Ladataan erikseen [täältä](https://zurb.com/playground/foundation-icon-fonts-3).

<a id='48'></a>

## 4.8 Plugins

<a id='481'></a>

### 4.8.1 Toggler

<a id='482'></a>

### 4.8.2 Smooth Scroll

<a id='483'></a>

### 4.8.3 Sticky

<a id='5'></a>

## 5. Tehtävät

<a id='51'></a>

### 5.1 Tehtävä 1

<a id='52'></a>

### 5.2 Tehtävä 2
