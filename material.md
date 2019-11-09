# Foundation

## Sisällysluettelo

---

## Mitä käydään läpi

- Foundation lyhyesti
- Asennus
- Foundation for Sites
- HTML / CSS komponentteja
- Grid

## Mikä on Foundation

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

  - Koodi snippetteja

- Funktionaalisuutta JavaScript lisäosilla

Foundation hyödyntää CSS lisäosaa nimeltä [Sass](https://sass-lang.com/).

Sass tuo paljon hyödyllisiä asioita mukanaan:

- Variables
- Nesting
- Partials
- Modules
- Mixins
- Extend/Inheritance
- Operators

## Foundationin hyötyjä

- Mahdollistaa nopeaan UI/UX kehittämiseen.

- Puhdasta ja siistiä koodia.

- Responsiivisuus

- Optimoitu kaikille näytöille

- Johdonmukainen

- Räätälöitävyys

## Foundation vs Bootstrap

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

## Asentaminen

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

## Muokkaaminen

Foundation on tehty muokattavaksi. Virallinen [dokumentaatio](https://foundation.zurb.com/sites/docs/global.html) kertoo muun muassa miten globaaleja muuttujia voidaan muokata omaan projektiin sopivaksi.

## Komponentteja

Käydään läpi erilaisia komponentteja, kuten XY Grid, Buttons, Menu, Tabs ja Forms. Kaikki alempana mainitut komponentit ovat nimetty englanniksi, jotta alkuperäisen [dokumentaation](https://foundation.zurb.com/sites/docs/) lukeminen on helpompaa.

## General

### Typography

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


### Forms

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

### Visibility Classes

---

## Grid

### XY Grid

---

## Controls

### Buttons

    <!-- Anchors (links) -->
    <a href="about.html" class="button">Learn More</a>
    <a href="#features" class="button">View All Features</a>

    <!-- Buttons (actions) -->
    <button type="button" class="success button">Save</button>
    <button type="button" class="alert button">Delete</button>

### Close Button

### Button Group

### Slider

### Switch

---

## Navigation

### Menu

### Dropdown Menu

### Top Bar

### Breadcrumbs

### Pagination

---

## Containers

### Dropdown

### Off Canvas

### Tabs

### Table

---

## Media

### Responsive Embed

### Label

### Orbit

### Progress Bar

### Tooltip

---

## Icons

Ladataan erikseen [täältä](https://zurb.com/playground/foundation-icon-fonts-3).

---

## Plugins

### Toggler

### Smooth Scroll

### Sticky

---

## Tehtävät

### Tehtävä 1

### Tehtävä 2
