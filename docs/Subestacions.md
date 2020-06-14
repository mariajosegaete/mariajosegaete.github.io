## 11 Subestacions

<br/>

>  Grup: Sistemes Tramviaris · Número elements: 10

<br/>

Emplaçaments, soterrats o en superfície, que reben l'energia elèctrica i la transformen i rectifiquen per als diferents consums del sistema tramviari.

<br/>

### 001 Obra Civil

> `Identificador: 11001 | Codi: OBC | Geometria: POLÍGON`

<br/>

Emplaçament de la subestació. La subestació de tracció transforma i rectifica l'energia elèctrica proveïda de companyia a unes condicions de voltatge, corrent i freqüència adients per als diferents consums del tramvia. En aquest cas, l'element obra civil contempla el perímetre del conjunt.

<br/>

<center>![110011](img/110011.jpg)</center>

<br/>
Foto de detall:
<br/>

<center>![110012](img/110012.jpg)</center>

<br/>

**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| CODI_SUBESTACIO | Indica el codi intern de la subestació. | [String (20)] |
| NOM_SUBESTACIO | Indica el nom complert de la subestació. | [String (30)] |
| DOCUMENT_ASSOCIAT | Nom d'un o més documents associats amb plànols de diversos detalls de l'element en qüestió. | [String (80)]|


<br/>

**Representació GIS:**

<br/>
<center>![110013](img/110013.jpg)</center>
<br/>

    Nom capa element: Subestacions-obra civil
    Nom taula DB: atmgis_11_obra_civil
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.5', dasharray: 'continua', color: '#434343', fillcolor: '#6e6e6e', fillstyle: 'trama en x', labelby: '@nom_subestacio + @codi_subestacio']

<br/><br/>

### 002 Transformadors

> `Identificador: 11002 | Codi: TRA | Geometria: POLÍGON`

<br/>

Transformador de tensió elèctrica. Màquina elèctrica d’inducció electromagnètica que permet convertir els valors de tensió d’entrada en valors diferents de sortida, sense modificar la potència.

<br/>
<center>![110021](img/110021.jpg)</center>
<br/>


**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| CODI_SUBESTACIO | Indica el codi intern de la subestació. | [String (20)] |
| NOM_SUBESTACIO | Indica el nom complert de la subestació. | [String (30)] |
| POTENCIA | Potencia del transformador. | [String (10)]|

<br/>

**Representació GIS:**

<br/>
<center>![110022](img/110022.jpg)</center>
<br/>

    Nom capa element: Subestacions-trafos
    Nom taula DB: atmgis_11_transformadors
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.3', dasharray: 'continua', color: '#434343', fillcolor: '#eaeaea', fillstyle: 'solid', labelby: 't']


<br/><br/>

### 003 Cel·les MT 25 kV

> `Identificador: 11003 | Codi: CEL | Geometria: POLÍGON`

<br/>

Cel·les de mitja tensió. Conjunt de seccions verticals on es troben ubicats diferents equips - de maniobra (interruptors de potència, seccionadors,...) de mesura (transformadors de tensió i de corrent,...) i de protecció/control – muntats en uns compartiments amb una estructura metàl·lica externa, amb la funció de rebre i distribuir l'energia elèctrica.

<br/>

<center>![110031](img/110031.jpg)</center>

<br/>

**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| CODI_SUBESTACIO | Indica el codi intern de la subestació. | [String (20)] |
| NOM_SUBESTACIO | Indica el nom complert de la subestació. | [String (30)] |

<br/>

**Representació GIS:**

<br/>
<center>![110032](img/110032.jpg)</center>
<br/>

    Nom capa element: Subestacions-cel·les
    Nom taula DB: atmgis_11_cel·les_mt_25_kv
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.3', dasharray: 'continua', color: '#434343', fillcolor: '#eaeaea', fillstyle: 'solid', labelby: 'mt25']

<br/><br/>


### 004 Rectificadors 900 kW

> `Identificador: 11004 | Codi: REC | Geometria: POLÍGON`

<br/>

Rectificador de corrent elèctric. Dispositiu elèctric que converteix el corrent altern en corrent continu.

<br/>

<center>![110041](img/110041.jpg)</center>

<br/>
Foto de detall:
<br/>

<center>![110042](img/110042.jpg)</center>

<br/>

**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| CODI_SUBESTACIO | Indica el codi intern de la subestació. | [String (20)] |
| NOM_SUBESTACIO | Indica el nom complert de la subestació. | [String (30)] |

<br/>

**Representació GIS:**

<br/>
<center>![110043](img/110043.jpg)</center>
<br/>

    Nom capa element: Subestacions-rectificadors
    Nom taula DB: atmgis_11_rectificadors_900_kw
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.3', dasharray: 'continua', color: '#434343', fillcolor: '#eaeaea', fillstyle: 'solid', labelby: 'r']
        [symbol: 'armari.svg', angle: '90', size: '3', weight: '0.3', color: '#a02c41', fillcolor: '#966770']

<br/><br/>

### 005 Carregadors i bateries

> `Identificador: 11005 | Codi: RCT | Geometria: POLÍGON`

<br/>

Acumuladors d'energia. Aparells acumuladors d'energia elèctrica que funcionen coma reservori.

<br/>

<center>![110051](img/110051.jpg)</center>

<br/>

**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| CODI_SUBESTACIO | Indica el codi intern de la subestació. | [String (20)] |
| NOM_SUBESTACIO | Indica el nom complert de la subestació. | [String (30)] |

<br/>

**Representació GIS:**

<br/>
<center>![110052](img/110052.jpg)</center>
<br/>

    Nom capa element: Subestacions-carregador i bateries
    Nom taula DB: atmgis_11_carregadors_i_bateries
    Nom camp geometria DB: geom
    Representació gràfica:

        Simbologia no definida

<br/><br/>

### 006 Quadre BT

> `Identificador: 11006 | Codi: QUB | Geometria: POLÍGON`

<br/>

Quadre de baixa tensió. És el conjunt de mòduls que reben el circuit principal de BT del transformador i el distribueixen en diversos circuits individuals que alimenten diferents elements de la subestació.

<br/>

<center>![110061](img/110061.jpg)</center>

<br/>
Foto de detall:
<br/>

<center>![110062](img/110062.jpg)</center>

<br/>

**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| CODI_SUBESTACIO | Indica el codi intern de la subestació. | [String (20)] |
| NOM_SUBESTACIO | Indica el nom complert de la subestació. | [String (30)] |

<br/>

**Representació GIS:**

<br/>
<center>![110063](img/110063.jpg)</center>
<br/>

    Nom capa element: Subestacions-quadre bt
    Nom taula DB: atmgis_11_quadre_bt
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.3', dasharray: 'continua', color: '#434343', fillcolor: '#eaeaea', fillstyle: 'solid', labelby: 'bt']

<br/><br/>

### 007 Quadre de control

> `Identificador: 11007 | Codi: QUC | Geometria: POLÍGON`

<br/>

Quadre de control. Quadre que conté els comandaments per al control de la subestació.

<br/>

<center>![110071](img/110071.jpg)</center>

<br/>
Foto de detall:
<br/>

<center>![110072](img/110072.jpg)</center>

<br/>

**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| CODI_SUBESTACIO | Indica el codi intern de la subestació. | [String (20)] |
| NOM_SUBESTACIO | Indica el nom complert de la subestació. | [String (30)] |

<br/>

**Representació GIS:**

<br/>
<center>![110073](img/110073.jpg)</center>
<br/>

    Nom capa element: Subestacions-quadre de control
    Nom taula DB: atmgis_11_quadre_de_control
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.3', dasharray: 'continua', color: '#434343', fillcolor: '#eaeaea', fillstyle: 'solid', labelby: 'qc']

<br/><br/>

### 008 Quadre de seccionadors 750 VCC

> `Identificador: 11008 | Codi: QUS | Geometria: POLÍGON`

<br/>

Quadre de seccionadors. Quadre que conté el comandament per al control dels seccionadors de catenària.

<br/>

<center>![110081](img/110081.jpg)</center>

<br/>


**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| CODI_SUBESTACIO | Indica el codi intern de la subestació. | [String (20)] |
| NOM_SUBESTACIO | Indica el nom complert de la subestació. | [String (30)] |

<br/>

**Representació GIS:**

<br/>
<center>![110082](img/110082.jpg)</center>
<br/>

    Nom capa element: Subestacions-quadre de seccionadors
    Nom taula DB: atmgis_11_quadre_de_seccionadors_750_vcc
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.3', dasharray: 'continua', color: '#434343', fillcolor: '#eaeaea', fillstyle: 'solid', labelby: 'qs750']

<br/><br/>

### 009 Disjuntor 750 VCC

> `Identificador: 11009 | Codi: DIS | Geometria: POLÍGON`

<br/>

Disjuntors de la subestació Un disjuntor o interruptor automàtic és un dispositiu capaç d'interrompre o obrir un circuit elèctric quan la intensitat del corrent elèctric que hi circula excedeix d'un determinat valor o, en el cas que es produeixi un curtcircuit, amb l'objectiu de no causar danys a la instal·lació elèctrica.

<br/>

<center>![110091](img/110091.jpg)</center>

<br/>


**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| CODI_SUBESTACIO | Indica el codi intern de la subestació. | [String (20)] |
| NOM_SUBESTACIO | Indica el nom complert de la subestació. | [String (30)] |

<br/>

**Representació GIS:**

<br/>
<center>![110092](img/110092.jpg)</center>
<br/>

    Nom capa element: Subestacions-disjuntors
    Nom taula DB: atmgis_11_disjuntor_750_vcc
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.3', dasharray: 'continua', color: '#434343', fillcolor: '#eaeaea', labelby: 'd750']

<br/><br/>

### 010 SAA

> `Identificador: 11010 | Codi: SAA | Geometria: POLÍGON`

<br/>

Seccionador d'Aïllament Automàtic. Seccionador que permet aïllar una subestació de la xarxa de tracció per incidència o manteniment.

<br/>

<center>![110101](img/110101.jpg)</center>

<br/>


**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| CODI_SUBESTACIO | Indica el codi intern de la subestació. | [String (20)] |
| NOM_SUBESTACIO | Indica el nom complert de la subestació. | [String (30)] |

<br/>

**Representació GIS:**

<br/>
<center>![110102](img/110102.jpg)</center>
<br/>

    Nom capa element: SAA
    Nom taula DB: atmgis_11_saa
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.3', dasharray: 'continua', color: '#434343', fillcolor: '#eaeaea', fillstyle: 'solid', labelby: 'saa']
