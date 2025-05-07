### A sötét lovag🦇
Ez a weboldal "A sötét lovag" című filmről tartogat érdekességeket.
**HTML** és **CSS** segítségével készült. 

#### A weboldal ezt nyújtja🤓
- A film értékelésének megtekintése
- Egy ismertető a filmről 
- Szereplők megtekintése
- A film előzetesének megtekintése 

#### Betekintő a HTML-be🤩
```html
 <!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A sötét lovag</title>
    <link rel="icon" type="image/x-icon" href="batman logo.ico">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.cdnfonts.com/css/lato" rel="stylesheet">
```

#### CSS Stílusok💫💫💫
```css
body {
    background-color: black;
    color: white;
    font-family: 'Lato', sans-serif;
    margin: 0;
    padding: 20px;
}

h1 {
    text-align: center;
    font-size: 3rem;
    margin-bottom: 10px;
    color: #ffcc00;
    text-shadow: 2px 2px #000;
}

h2 {
    color: #ffcc00;
    border-bottom: 2px solid #444;
    padding-bottom: 5px;
    margin-top: 40px;
}

p {
    max-width: 800px;
    margin: 0 auto 20px auto;
    font-size: 1.1rem;
    text-align: justify;
    line-height: 1.6;
}

ul {
    max-width: 800px;
    margin: 0 auto 20px auto;
    font-size: 1.1rem;
}

a {
    color: #ffcc00;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

#batman_poster {
    display: block;
    margin: 20px auto;
    width: 250px;
    height: 350px;
    border: 3px solid #ffcc00;
    box-shadow: 0 0 20px rgba(255, 204, 0, 0.3);
}

#tizenhatkarika {
    width: 25px;
    vertical-align: middle;
    margin-right: 8px;
}

```

#### Fejlesztési lehetőségek👀
-Galéria hozzáadása a filmhez kapcsolódó képekkel


# Murder Drones

Az oldal a **Murder Drones** című sorozatról tartalmaz kritikát, amelyet a 2000-es évek stílusában igyekszik átadni.

## 📂 Fájlok:

* `.gitattributes`
* `film-poster.jpg`
* `letöltés.gif`
* `maxresdefault.jpg`
* `MD.html`
* `MD-icon.ico`
* `MURDER DRONES [OFFICIAL TRAILER].mp4`
* `Murder-Drones.jpg`
* `styles.css`


## 🔍 Betekintő a HTML-be:
```html
<tr>
  <td class="content">
    <h1 id="c-title">Murder Drones (2021-2024)</h1>
    <h3 id="c-descp">
      "Murder Drones is a show about cute little robots that murder each other for reasons"
    </h3>
    <h1 id="rating">★★★★☆ 4.2/5</h1>
    <p><img src="film-poster.jpg" alt="" srcset=""></p>
    <p id="c-rev">
      Vélemény: Murder Drones egy sötéten humoros és látványos animációs sorozat, amely egy elhagyott bolygón rekedt robotok túléléséről szól — miközben gyilkos drónok vadásznak rájuk. A sorozat erőssége a stílusos vizuális világ, a gyors tempójú történetmesélés és a karakterek meglepően mély érzelmi fejlődése. Bár néha a humor és a komolyabb pillanatok közötti váltás kicsit hirtelennek érződik, a sorozat bátran kísérletezik a műfajok keverésével. Összességében friss és izgalmas alkotás, különösen azoknak, akik kedvelik a sötétebb témákat könnyed előadásmóddal kombinálva.
    </p>
    <video class="box" width="640" height="360" controls poster="maxresdefault.jpg">
      <source src="MURDER DRONES [OFFICIAL TRAILER].mp4" type="video/mp4">
      A böngésződ nem támogatja a videólejátszást.
    </video>
    <p id="link">További információ <a href="https://www.imdb.com/title/tt15599734/">itt</a>.</p>
  </td>
</tr>
```

## 🎨 Betekintő a CSS-be:
```css
#menu {
  font-family: "Comic Sans MS", cursive, sans-serif;
  font-size: 20px;
  text-align: center;
  border-collapse: collapse;
  background-color: red;
  border-top: red solid 8px;
  border-left: red solid 8px;
  border-right: red solid 8px;
  border-bottom: none;
}

#menu a:hover {
  color: rgb(0, 255, 76);
  text-shadow: 0px 0px 10px rgb(0, 255, 76);
  text-decoration: underline;
  padding: 10px 20px;
}

.content {
  text-align: center;
  font-family: "Comic Sans MS", cursive, sans-serif;
  font-size: 20px;
  line-height: 1.5;
  margin: 20px;
  background-image: linear-gradient(to top right, rgb(255, 238, 0), rgb(255, 255, 255));
  border-style: dashed;
  border-width: 8px;
  border-color: rgb(153, 0, 255);
  background-clip: content-box;
}
```
## ⬆️ Fejlesztési lehetőségek

- Az elosztó oldal (főoldal) lehetne részletesebben kidolgozva
- További stílusbeli elemek (pl. animációk, több színátmenet)
