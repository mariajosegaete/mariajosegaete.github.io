## 17 Tallers i Cotxeres

<br/>

>  Grup: Sistemes Tramviaris · Número elements: 2

<br/>

Es tracta de les instal·lacions, clarament delimitades i fora de l'abast públic general, que acullen activitats de manteniment i neteja a més de disposar d'espai per a l'estacionament de la flota. També s'hi troben instal·lacions com el Centre de Control i altres locals d'explotació.

<br/>

### 001 Emplaçament

> `Identificador: 17001 | Codi: TCU | Geometria: POLÍGON`

<br/>

Emplaçament de les Cotxeres i tallers. Són els límits del recinte de Tallers i Cotxeres.

<br/>

<center>![170011](img/170011.jpg)</center>

<br/>
Foto de detall:
<br/>

<center>![170012](img/170012.jpg)</center>

<br/>


**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| DOCUMENT_ASSOCIAT | Nom d'un o més documents associats amb plànols de diversos detalls de l'element en qüestió. | [String (80)] |


<br/>

**Representació GIS:**

<br/>
<center>![170013](img/170013.jpg)</center>
<br/>

    Nom capa element: Tallers i Cotxeres-ubicació
    Nom taula DB: atmgis_17_emplacament
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.35', dasharray: 'continua', color: '#434343', fillcolor: '#fcf9ea', fillopacity: '56', fillstyle: 'solid']

<br/><br/>

### 002 Edificis

> `Identificador: 17002 | Codi: TCE | Geometria: POLÍGON`

<br/>

Edificacions dins del recinte de Cotxeres. Són edificis o construccions amb funcions concretes dins del recinte de Cotxeres.

<br/>
<center>![170021](img/170021.jpg)</center>
<br/>


**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| NOM | Nom descriptiu de l'edifici o element. | [String (80)] |
| DOCUMENT_ASSOCIAT | Nom d'un o més documents associats amb plànols de diversos detalls de l'element en qüestió. | [String (80)] |

<br/>

**Representació GIS:**

<br/>
<center>![170022](img/170022.jpg)</center>
<br/>

    Nom capa element: Tallers i Cotxeres-edificis
    Nom taula DB: atmgis_17_edificis
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.4', dasharray: 'continua', color: '#688592', fillcolor: '#9ab5c1', fillstyle: 'solid']
