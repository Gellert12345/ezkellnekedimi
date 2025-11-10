aniamtion.css
---
.heart
{
    width: 100px;
    height: 100px;
    background-color: red;
    position: relative;
    transform: rotate(45deg) translate(10px, 10px);
    animation: ani 1s linear infinite;
}

.center
{
    width: 100px;
    margin-left: auto;
    margin-right: auto;
    margin-top: 20%;
}

.heart:before
{
    content:'';
    width: 100px;
    height: 100px;
    background-color: red;
    position: absolute;
    top: -50px;
    left: 0px;
    border-radius: 50%;
}

.heart:after
{
    content:'';
    width: 100px;
    height: 100px;
    background-color: red;
    position: absolute;
    bottom: 0px;
    right: 50px;
    border-radius: 50%;
}

@keyframes ani
{
   0%{
    transform: rotate(45deg) translate(10px, 10px) scale(1.0);
   }
   25%{
    transform: rotate(45deg) translate(10px, 10px) scale(1.0);
   }
   30%{
    transform: rotate(45deg) translate(10px, 10px) scale(2.0);
   }
   50%{
    transform: rotate(45deg) translate(10px, 10px) scale(1.2);
   }
   70%{
    transform: rotate(45deg) translate(10px, 10px) scale(2.0);
   }
   90%{
    transform: rotate(45deg) translate(10px, 10px) scale(1.0);
   }
   100%{
    transform: rotate(45deg) translate(10px, 10px) scale(1.0);
   }
}
---
animation.html
---
<!DOCTYPE html>
<html lang="hu">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>11a1 HTML Projekt 20226</title>
    <link rel="stylesheet" href="main.css">
    <link rel="stylesheet" href="animation.css">
</head>

<body>
    <!--Kecskés Gellért 2026-->
    <header>
        <div id="logo">
            <a href="index.html"><img src="kép2.png" alt="Premo logo" title="Premo logo" width="190"></a>
        </div>
        <div id="banner-content">
            <a href="index.html" title="11a1 HTML projekt 2025">
                <h1>11a1 HTML projekt 2025</h1>
            </a>
        </div>
        <h2>«header»</h2>
    </header>
    <div class="container">
        <nav>
            <h2>«nav»</h2>
            <div id="menu">
                <ul>
                    <li><a href="index.html">Főoldal</a></li>
                    <li><a href="#nogo">HTML/CSS Demo</a>
                        <ul>
                            <li><a href="animation.html">CSS animation</a></li> <!--listán belüli lista(almenu)-->
                            <li><a href="form.html">HTML Űrlap</a></li>
                            <li><a href="table.html">HTML Táblázat</a></li>
                            <li><a href="gallery.html">Képgaléria</a></li>
                            <li><a href="media.html">Média</a></li>
                        </ul>
                    </li>

                </ul>
            </div>
        </nav>
        <section>
            <h2>«section»</h2>
            <article>
                <h2>«css animáció»</h2>
                <div class="center">
                    <div class="heart"></div>
                </div>
            </article>
        </section>
    </div>
    <footer>
        <h2>«footer» <br>
        ©2025/26 Kecskés Gellért All rights reserved</h2>
    </footer>
</body>

</html>
---
index.html
---
<!DOCTYPE html>
<html lang="hu">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>11a1 HTML Projekt 20226</title>
    <link rel="stylesheet" href="main.css">
</head>

<body>
    <!--Kecskés Gellért 2026-->
    <header>
        <div id="logo">
            <a href="index.html"><img src="kép2.png" alt="Premo logo" title="Premo logo" width="190"></a>
        </div>
        <div id="banner-content">
            <a href="index.html" title="11a1 HTML projekt 2025">
                <h1>11a1 HTML projekt 2025</h1>
            </a>
        </div>
        <h2>«header»</h2>
    </header>
    <div class="container">
        <nav>
            <h2>«nav»</h2>
            <div id="menu">
                <ul>
                    <li><a href="index.html">Főoldal</a></li>
                    <li><a href="#nogo">HTML/CSS Demo</a>
                        <ul>
                            <li><a href="animation.html">CSS animation</a></li> <!--listán belüli lista(almenu)-->
                            <li><a href="form.html">HTML Űrlap</a></li>
                            <li><a href="table.html">HTML Táblázat</a></li>
                            <li><a href="gallery.html">Képgaléria</a></li>
                            <li><a href="media.html">Média</a></li>
                        </ul>
                    </li>

                </ul>
            </div>
        </nav>
        <section>
            <h2>«section»</h2>
            <article>
                <h2>«article»</h2>
                <img src="kép3.png" alt="html-5 css3 javascript" title="html5 css3 javascript" width="150px" >
                <p>Lórum ipse ságos rácikát jegyel: a sajtha hüves fohoklyó, mellés gyászaj ez. A verces rénzések tröccse
                után vivő üregést kell rodnia. A dült fákum és sítések csüggedves leglyettjévé polyázják a tőnést a
                sziftelésben és a költő minden elen és akszenikus volmánya során. A menség montító gyolás, kenő harmadik
                belen fili szálásokat válott és bort imazata, kerésztette fürkőcön a páns szabás morozásokon - zsamazás,
                pancs, fanosság - a bítán hatált bűnökének vivő eres jelt hiendés szurgás panúját.</p><p> A tatos szurgáson a
                ságos szendók három hált múlós és csalk barsa közül marászhatnak. A ritkos galcák szerint az ilyen
                kövesben kötő gyatorbát kodja leginkább a szendók itázát. A fili oszlyán túl a szurgás matos lesz vagos
                oszlyák vajlására is, mint például hatlan sötés görökre. Az életes nyált szurgás ulandása, és a szendók
                baságzóját a szurgásra ádás galcák alapján, bajtatos kacában sanyalangat meg. Az amozásban a virgások és
                csalmangok mellett vívó, nyirta és kezel is irátot mocsold. 2004-től céltus balázként viviló is röményes
                reségnek.</p><p> Belevences 600 vékos karma redik együtt tívós spejkákkal, meglehetősen szocdes folyás
                hóságokat kodik. Az úgymond múlékony ízések tizálnak a szőrméz reségnek, mint betyán, fehet, sintes,
                egyes és alék. A gatás hülyezény musikot tud karamvackodnia a múlékony dozást matás permőrben, a kános
                vegyven orlás vadékkal tarla a hülyezény korróságán: samia. Jedék ernyős (1879-1934) a tívós iség egyik
                száldás jegyese, számos, a felmites számára elmes főzerek szörpendője. <p>Nem metes múlékony dosbír, nem
                kodlik vagy furag kempelik sárnyálják nastyántását. Az amozásban a virgások és csalmangok mellett vívó,
                nyirta és kezel is irátot mocsold. 2004-től céltus balázként viviló is röményes reségnek. Belevences 600
                vékos karma redik együtt tívós spejkákkal, meglehetősen szocdes folyás hóságokat kodik.</p> Az úgymond
                múlékony ízések tizálnak a szőrméz reségnek, mint betyán, fehet, sintes, egyes és alék. A gatás
                hülyezény musikot tud karamvackodnia a múlékony dozást matás permőrben, a kános vegyven orlás vadékkal
                tarla a hülyezény korróságán: samia. Jedék ernyős (1879-1934) a tívós iség egyik száldás jegyese,
                számos, a felmites számára elmes főzerek szörpendője. Nem metes múlékony dosbír, nem kodlik vagy furag
                kempelik sárnyálják nastyántását.</p>
                <p>Lórum ipse ságos rácikát jegyel: a sajtha hüves fohoklyó, mellés gyászaj ez. A verces rénzések tröccse
                után vivő üregést kell rodnia. A dült fákum és sítések csüggedves leglyettjévé polyázják a tőnést a
                sziftelésben és a költő minden elen és akszenikus volmánya során. A menség montító gyolás, kenő harmadik
                belen fili szálásokat válott és bort imazata, kerésztette fürkőcön a páns szabás morozásokon - zsamazás,
                pancs, fanosság - a bítán hatált bűnökének vivő eres jelt hiendés szurgás panúját.</p><p> A tatos szurgáson a
                ságos szendók három hált múlós és csalk barsa közül marászhatnak. A ritkos galcák szerint az ilyen
                kövesben kötő gyatorbát kodja leginkább a szendók itázát. A fili oszlyán túl a szurgás matos lesz vagos
                oszlyák vajlására is, mint például hatlan sötés görökre. Az életes nyált szurgás ulandása, és a szendók
                baságzóját a szurgásra ádás galcák alapján, bajtatos kacában sanyalangat meg. Az amozásban a virgások és
                csalmangok mellett vívó, nyirta és kezel is irátot mocsold. 2004-től céltus balázként viviló is röményes
                reségnek.</p><p> Belevences 600 vékos karma redik együtt tívós spejkákkal, meglehetősen szocdes folyás
                hóságokat kodik. Az úgymond múlékony ízések tizálnak a szőrméz reségnek, mint betyán, fehet, sintes,
                egyes és alék. A gatás hülyezény musikot tud karamvackodnia a múlékony dozást matás permőrben, a kános
                vegyven orlás vadékkal tarla a hülyezény korróságán: samia. Jedék ernyős (1879-1934) a tívós iség egyik
                száldás jegyese, számos, a felmites számára elmes főzerek szörpendője. <p>Nem metes múlékony dosbír, nem
                kodlik vagy furag kempelik sárnyálják nastyántását. Az amozásban a virgások és csalmangok mellett vívó,
                nyirta és kezel is irátot mocsold. 2004-től céltus balázként viviló is röményes reségnek. Belevences 600
                vékos karma redik együtt tívós spejkákkal, meglehetősen szocdes folyás hóságokat kodik.</p> Az úgymond
                múlékony ízések tizálnak a szőrméz reségnek, mint betyán, fehet, sintes, egyes és alék. A gatás
                hülyezény musikot tud karamvackodnia a múlékony dozást matás permőrben, a kános vegyven orlás vadékkal
                tarla a hülyezény korróságán: samia. Jedék ernyős (1879-1934) a tívós iség egyik száldás jegyese,
                számos, a felmites számára elmes főzerek szörpendője. Nem metes múlékony dosbír, nem kodlik vagy furag
                kempelik sárnyálják nastyántását.</p>
                <p>Lórum ipse ságos rácikát jegyel: a sajtha hüves fohoklyó, mellés gyászaj ez. A verces rénzések tröccse
                után vivő üregést kell rodnia. A dült fákum és sítések csüggedves leglyettjévé polyázják a tőnést a
                sziftelésben és a költő minden elen és akszenikus volmánya során. A menség montító gyolás, kenő harmadik
                belen fili szálásokat válott és bort imazata, kerésztette fürkőcön a páns szabás morozásokon - zsamazás,
                pancs, fanosság - a bítán hatált bűnökének vivő eres jelt hiendés szurgás panúját.</p><p> A tatos szurgáson a
                ságos szendók három hált múlós és csalk barsa közül marászhatnak. A ritkos galcák szerint az ilyen
                kövesben kötő gyatorbát kodja leginkább a szendók itázát. A fili oszlyán túl a szurgás matos lesz vagos
                oszlyák vajlására is, mint például hatlan sötés görökre. Az életes nyált szurgás ulandása, és a szendók
                baságzóját a szurgásra ádás galcák alapján, bajtatos kacában sanyalangat meg. Az amozásban a virgások és
                csalmangok mellett vívó, nyirta és kezel is irátot mocsold. 2004-től céltus balázként viviló is röményes
                reségnek.</p><p> Belevences 600 vékos karma redik együtt tívós spejkákkal, meglehetősen szocdes folyás
                hóságokat kodik. Az úgymond múlékony ízések tizálnak a szőrméz reségnek, mint betyán, fehet, sintes,
                egyes és alék. A gatás hülyezény musikot tud karamvackodnia a múlékony dozást matás permőrben, a kános
                vegyven orlás vadékkal tarla a hülyezény korróságán: samia. Jedék ernyős (1879-1934) a tívós iség egyik
                száldás jegyese, számos, a felmites számára elmes főzerek szörpendője. <p>Nem metes múlékony dosbír, nem
                kodlik vagy furag kempelik sárnyálják nastyántását. Az amozásban a virgások és csalmangok mellett vívó,
                nyirta és kezel is irátot mocsold. 2004-től céltus balázként viviló is röményes reségnek. Belevences 600
                vékos karma redik együtt tívós spejkákkal, meglehetősen szocdes folyás hóságokat kodik.</p> Az úgymond
                múlékony ízések tizálnak a szőrméz reségnek, mint betyán, fehet, sintes, egyes és alék. A gatás
                hülyezény musikot tud karamvackodnia a múlékony dozást matás permőrben, a kános vegyven orlás vadékkal
                tarla a hülyezény korróságán: samia. Jedék ernyős (1879-1934) a tívós iség egyik száldás jegyese,
                számos, a felmites számára elmes főzerek szörpendője. Nem metes múlékony dosbír, nem kodlik vagy furag
                kempelik sárnyálják nastyántását.</p>
            </article>
        </section>
    </div>
    <footer>
        <h2>«footer» <br>
        ©2025/26 Kecskés Gellért All rights reserved</h2>
    </footer>
</body>

</html>
---
form.html
---
<!DOCTYPE html>
<html lang="hu">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>11a1 HTML Projekt 20226</title>
    <link rel="stylesheet" href="main.css">
</head>

<body>
    <!--Kecskés Gellért 2026-->
    <header>
        <div id="logo">
            <a href="index.html"><img src="kép2.png" alt="Premo logo" title="Premo logo" width="190"></a>
        </div>
        <div id="banner-content">
            <a href="index.html" title="11a1 HTML projekt 2025">
                <h1>11a1 HTML projekt 2025</h1>
            </a>
        </div>
        <h2>«header»</h2>
    </header>
    <div class="container">
        <nav>
            <h2>«nav»</h2>
            <div id="menu">
                <ul>
                    <li><a href="index.html">Főoldal</a></li>
                    <li><a href="#nogo">HTML/CSS Demo</a>
                        <ul>
                            <li><a href="animation.html">CSS animation</a></li> <!--listán belüli lista(almenu)-->
                            <li><a href="form.html">HTML Űrlap</a></li>
                            <li><a href="table.html">HTML Táblázat</a></li>
                            <li><a href="gallery.html">Képgaléria</a></li>
                            <li><a href="media.html">Média</a></li>
                        </ul>
                    </li>
 
                </ul>
            </div>
        </nav>
        <section>
            <h2>«section»</h2>
            <article>
                <h2>«HTML Űrlap»</h2>
                <form action="">
                    <fieldset>
                        <legend>megrendelő adatai</legend>
                        <p>
                            <label for="">Név: <input type="text" name="nev" placeholder="név megadása..." size="17" required></label>
                            <small>Vezetéknév/Keresztnév</small>
                        </p>
                        <p>
                            <label for="">Telefon: <input type="tel" name="Telefon" id="Telefon" placeholder="telefon szám megadásas..."size="17" required></label>
                        </p>
                        <p>
                            <label for="">Szállítási cím: <input type="text" name="cim" id="cim" placeholder="Ide írd a szállítási címet..." size="17" required></label>
                        </p>
                        <p>
                            <label for="">Email Cím <input type="email" name="email" id="email" placeholder="add meg az email cimed..."size="17"></label>
                        </p>
                    </fieldset>
                    <fieldset>
                        <legend>A pizza mérete</legend>
                        <p><label for=""><input type="radio" name="meret" value="kicsi"checked>kicsi</label></p>
                        <p><label for=""><input type="radio" name="meret" value="nagy">nagy</label></p>
                    </fieldset>
                    <fieldset>
                        <legend>Feltétek</legend>
                        <p><label for=""><input type="checkbox" name="feltet1" value="sonka" checked>sonka</label></p>
                        <p><label for=""><input type="checkbox" name="feltet2" value="sajt">sajt</label></p>
                        <p><label for=""><input type="checkbox" name="feltet3" value="gomba">gomba</label></p>
                    </fieldset>
                </form>
            </article>
        </section>
    </div>
    <footer>
        <h2>«footer» <br>
        ©2025/26 Kecskés Gellért All rights reserved</h2>
    </footer>
</body>

</html>

main.css
---
/*Kecskés Gellért 2026*/
header, nav, section, article , footer
{
    border: 1px solid #ccc; /* mezei pocook szürke*/
}
body {
    background-image: url(kép1.png); /* ccs háttér megadása mindig  url!! */
}
h2 {
    text-align: center;
}
header {
    width: 100%;
    height: 200px;
    margin-bottom: 10px;
    background-color: white;
    border-radius: 10px;      /* legekerytés! */
}
.container{
    width: 1100px;
    height: auto;
    margin-left:auto ;
    margin-right: auto;
}
nav {
    width: 10%;
    min-width: 200px;
    height: 1100px;
    float: left;
    margin: 0 30px 0 30px;
    background-color: rgba(255, 255, 255 , 0.7);
    border-radius: 10px;
}
section {
    width: 89%;
    height: 1100px;
    max-width: 800px;
    float: left;
    background-color: rgba(255, 255, 255 , 0.7);
    border-radius: 10px;
}
article {
    width: 96%;
    max-width: 700px;
    height: 900px;
    margin-top: 20px;
    margin-left:auto ;
    margin-right: auto;
    background-color: white;
    border-radius: 10px;
    text-align: justify;    /* sorkizárt */
    line-height: 1.5em;
    padding: 20px;      /* ne csúszon ráa külsö keretere */
    font-family: Arial, Helvetica, sans-serif;
    overflow: auto;     /*görgető sáv */
}
article img {
    float: left;   /* kép szöveg körbefuttatéssa */
    margin-right: 20px;
}


footer{
    width: 100%;
    height: 100px;
    float: left;
    margin: 10px 0 20px 0;
    background-color: rgba(255, 255, 255 , 0.85);
}
#logo {
    float: left;
    width: 210px;
    height: 170px;
    margin: 5px 0 5px 10px;
}
#banner-content {
    text-align: center;
    margin-top: 50px;
    border-radius: 5px;  /* kerekítés  */
}
#banner-content a {
    text-decoration: none;
    color: orange;
    font-size: 1.3em;
}
/* egér követés */
#banner-content a:hover{
    text-decoration: underline;

}
#menu li {
    list-style-type: none; /* stilus kikpacsolás listában*/
}

#menu ul li a {
    text-decoration: none;
    color: black;
    border: 1px solid black;  /*sima basic keret*/
    padding: 3px;
    display: block; /*felvegye a menü teljes méretét*/
    background-color: #ccc;
    text-align: center;
}
#menu ul li a:hover {   /*a hover azt jelenti hogy azt csinalja ha fölé ért az egér!!*/
    background-color: orange;
    color: white;
}
#menu ul ul a {       /* hamburger mneu */
    position: relative;
    bottom: 20px;
    left: 100%;
    display: none;  /* ne lehesen lattni*/
}
#menu ul li:hover > ul a {
    display: block;
}
---
