# Sveigjanleg hönnun vefs  (_Responsive Web Design_)
 
### Markmið:

Nemendur öðlast skilning á:

* hönnun svegjanlegs viðmóts (_Respnsive Web_)
* Hvernig hægt er að vinna með _Grid_ 
* hvernig hægt er að setja bakgrunnsliti í vefsíðu


Skipulag vefsíðu með 2 dálkum eða fleiri gengur ekki upp í litlum farsímaskjáum. Til að hafa áhrif á skipulag HTML síðu setjum við inn viðmið (_breakpoints_) í CSS stílsíðuna.  

Við notum **_@media screen_** skipunina til að birta mismunandi skipulag eftir skjástærðum.  

## 4.1 Sveigjanlegt dálkaskipulag 2, 3 og 4 dálkar

* Viðmið: 0 – 599px, allir dálkar með 100% breidd (1fr)
* Viðmið: 600px – 767px, 2 og 4 dálkar með 50% breidd (1fr 1fr)
* Viðmið: 768px – 959px, 2 dálkar 50% breidd (1fr 1fr), 3 dálkar 33.33% breidd (1fr 1fr 1fr) og 4 dálkar 25% breidd (1fr 1fr 1fr 1fr)

#### [**Sýnidæmi**](https://vefgrunnur.github.io/synidaemi/verkefni-3/verkefni-31/)

## 4.2 Sveigjanlegur vefur

Nú er komið að gera vefinn þinn sveigjanlegan. HTML tög eiga að hafa skiljanlega merkingu í uppsetningunni,  helstu tögin eru ` <header> <nav> <main> <section> <article> <aside> og <footer>`, [sjá öll tögin hér](https://www.w3schools.com/html/html5_semantic_elements.asp).  

Notaðu CSS Grid til að hanna eigið dálkaskipulag. Vefsíður þurfa að birtast í öllum helstu skjástærðum, búðu til viðmið (_breakpoint @media …_) til að stjórna skipulagi vefsíðunnar. 

#### [Sýnidæmi](https://vefgrunnur.github.io/synidaemi/verkefni-4/index.html)

### Námsmat 20% 

* **3% 4.1 Dálkaskipulag.** Vefsíða með 2, 3 og 4 dálkum  
    * 0 – 599px (Allir dálkar skiptast í 1fr)
    * 600px – 767px (2, 4 dálkar skiptast í 1fr 1fr)
    * 768px – + (Allir dálkar skiptast rétt, 2, 3 og 4 dálkar)
* **10% 4.2.1 Vefsíða með viðmiðum**
    * Mobile: 0 – 599px  _eins dálks hönnun_  
    * Tablet: 600px – 767px _tveggja dálka hönnun_
    * Desktop: 768px – 959px _þriggja + dálka hönnun_
    * 960px + Efni vefsíðunnar er miðjusett (_max-width_) í vafranum
*  **4% 4.2.2 Valmynd sveigjanleg og bakgrunnslitir**
    * Valmynd (nav) skal vera hönnuð sveigjanlega
    * Hlekki í valmynd skal stíla ( ekki hafa sjálfgefnar stillingar á ) og þeir skulu vera virkir
    * Mismunandi bakgrunnslitir í `header, main og footer`
*  **3% 4.2.3 Rétt notkun taga og uppsetning / framsetning á HTML og CSS**
    * Uppsetning vefsíða með réttum tögum  
    * Uppsetning á HTML
    * Uppsetning á CSS

### Verkefnaskil:  

Öllum gögnum er skilað í verkefnageymsluna þína á Github í möppuna **verkefni4**. Tengill á verkefnið er skilað í Innu.

#### Einkunn verður birt í Innu

_Gangi þér vel_
