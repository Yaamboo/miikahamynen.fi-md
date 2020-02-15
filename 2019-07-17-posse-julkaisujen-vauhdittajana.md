---
title: "POSSE julkaisujen vauhdittajana"
date: "2019-07-17"
datetime: "2019-07-17 12:29:59"
tags: ["atk,posse,verkkojulkaiseminen", ]
category: ["atk", ]
link: "http://miikahamynen.fi/2019/07/17/posse-julkaisujen-vauhdittajana/"
status: "publish"
coverImageId: ""
---

_(Ei, ei se TV-ohjelma)_

Törmäsin hiljattain tiedon vapautta edistävään ajatusmalliin nimeltä POSSE ([publish on your own site, syndicate elsewhere](https://indieweb.org/POSSE); kääntyy joustavasti esim. julkaise omalla sivulla, jakele muuallakin).

POSSE ei ole mikä tahansa porukka, vaan sen ideana on kiinnittää julkaisu vahvemmin tekijäänsä eikä julkaisualustaan. Tällä pyritään useampaankin eri lopputulokseen, joista tärkeimmät ovat mielestäni nämä:

- Teos säilyy täysin tekijänsä käsissä, eikä ole riippuvainen ulkopuolisista palveluntarjoajista jotka saattavat muuttaa käyttöehtojaan minä päivänä hyvänsä.
- Hakukoneet löytävät alkuperäisen verkkosivun paremmin.
- Käyttäjät voivat valita, mitä alustaa käyttävät julkaisun lukemiseen.

Perusajatus on yksinkertainen. Mediasisällön tuottaja (blogaaja, valokuvaaja, videontekijä jne.) julkaisee tuotoksensa ensimmäisenä omalla verkkosivullaan. Tämän jälkeen hän julkaisee teoksen toistamiseen jollain muulla sivustolla (Facebook, Wordpress.com, Medium, Puheenvuoro…) tai vaikka useammassakin palvelussa, jos niin haluaa.

Onnistunut POSSEaminen on kiinni sivun metatiedoista, joiden avulla hakukoneet ja muut indeksoijat tietävät, mikä on alkuperäinen julkaisu ja mikä kopio. Avaimena tähän on [rel=canonical -määre](https://yoast.com/rel-canonical/), joka osoittaa jokaisessa kopiossa alkuperäiseen lähteeseen:

<link rel="canonical" href="http://example.com /> 

Kaikki julkaisupalvelut eivät kuitenkaan valitettavasti päästä muokkaamaan ko. metaelementtiä. Alkuperäiseen julkaisuun tulisi joka tapauksessa aina linkittää, mahdollisuuksien mukaan `rel=canonical` -määreen avulla (vaikka [hakukoneet saattavatkin jättää sen huomiotta](https://www.mattcutts.com/blog/rel-canonical-html-head/)):

<a rel="canonical" href="http://example.com">alkuperäinen julkaisu</a>

Jotkin palvelut ovat ottaneet POSSEamisen osaksi perusajatustaan ja tarjoavat erikseen helpon mahdollisuuden täydentää metatietoja tai jopa sallivat julkaisun suoraan RSS-syötteestä.

![](https://miikahamynen.fi/wp-content/uploads/2019/07/Kuvakaappaus-2019-07-17-15-10-34.png)

Metatietojen muokkaamista dev.to -palvelussa

Alkuperäisen lähteen yhteyteen täydennetään toki myös [lista tiedossa olevista kopioista](https://indieweb.org/posts-elsewhere) joko automaattisesti tai käsipelillä.

Ideaa on viety pidemmällekin. Ihannemaailmassa tieto omaan julkaisuun liittyvästä sisällöstä voisi valua alkuperäisen yhteyteen. Erilaisia esimerkkejä onnistuneesta integraatiosta muuhun Internetiin on olemassa, mutta valitettavasti etenkin suuret sosiaalisen median palvelut rajoittavat rajapintojensa käyttöä tai tekevät tiedon viemisestä ulos muulla tavalla hankalaa.

POSSE on loistava ajatus, olkoonkin että sen syvällisempi hyödyntäminen vaatii jo enemmän teknistä hahmotuskykyä. Pienelläkin vaivalla saa kuitenkin suuren hyödyn ja omat ajatukset leviämään paremmin Internetissä.
