---
layout: "default"
description: ""
id: "yhdyskuntateknisen-huollon-alue"
status: "Ehdotus"
---
# Kaavamääräyslajit - yhdyskuntatekninen huolto
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/yhdyskuntateknisenHuollonAlue>

1. 
{:toc}


## Alin painovoimainen viemäröintitaso
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/alinPainovoimainenViemarointitaso>

{% include common/clause_start.html type="req" id="prof-ak/vaat-alin-painovoimainen-viemarointitaso-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeuspiste" title="Korkeuspiste" %} joka kertoo alimman painovoimaisen viemäröintitason korkeuden sovitun pystysuuntaisen koordinaatiston arvona. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-alin-painovoimainen-viemarointitaso-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Aurinkokennojen alin sijoittumistaso
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1202>

{% include common/clause_start.html type="req" id="prof-ak/vaat-alin-aurinkokennojen-sijoittumistaso-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeuspiste" title="Korkeuspiste" %} joka kertoo alimman aurinkokennojen sijoittumistason korkeuden sovitun pystysuuntaisen koordinaatiston arvona. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-alin-alin-aurinkokennojen-sijoittumistaso-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Vaatimus hulevesisuunnitelman laatimisesta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1203>

{% include common/clause_start.html type="req" id="prof-ak/vaat-hulevesisuunnitelma-laadittava-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolle on laadittava hulevesisuunnitelma.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-hulevesisuunnitelma-laadittava-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-hulevesisuunnitelma-laadittava-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Liitettävä kaukolämpöverkkoon
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1204>

{% include common/clause_start.html type="req" id="prof-ak/vaat-liitettava-kaukolampoverkkoon-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, joka on liitettävä kaukolämpöverkkoon.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-liitettava-kaukolampoverkkoon-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-liitettava-kaukolampoverkkoon-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}