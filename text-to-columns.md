---
description: Izuzetno korisna stvar
---

# Text to columns

Nalazi se na Data tab -&gt; Data Tools, pre upotrebe potrebno je selektovati celiju ili kolonu. 

{% hint style="info" %}
Ne funkcionise na vise kolona. Ukoliko hoces ovo da primenis na vise kolona moras nazalost jednu po jednu selektovati.
{% endhint %}

Precicu nauci napamet koristices ovo cesto \(pritiskas ih u sekvenci jednu za drugom\):

```text
ALT+A+E
```

Koristi se za: 

* Razdvajanje podataka u celiji
* Promenu tipa podatka

### Razdvajanje podataka

Moze biti sa delimiterom ili fixed width.

Izaberi delimiter po kome hoces da razdvojis podatke 

{% tabs %}
{% tab title="Step1" %}
![Prvi korak, selekcija kako hocemo da delimo kolonu](.gitbook/assets/text_to_column.png)
{% endtab %}

{% tab title="Step 2 delimiter" %}
![Drugi korak](.gitbook/assets/text_to_columns2.png)

Ukoliko nije ni jedan od navedenih delimitera, napisi svoj u other, u ovom slucaju stavi \(-\) kao other. Takodje mozes selektovati i vise delimitera.
{% endtab %}

{% tab title="Step 2 fixed" %}
![Selektovali smo fixed width](.gitbook/assets/text_to_column_fixed_w.png)

U ovom slucaju mozemo mu reci da podeli kolonu gde god dodamo liniju. 
{% endtab %}

{% tab title="Step 3" %}
![Treci korak sa Advanced ekranom](.gitbook/assets/text_to_column_third.png)

Ovaj je isti nezavisno od prethodnog. U donjem prozorcicu vidimo kako nam izgledaju podaci. Selektuj kolonu po kolonu i izaberi gore Data format koji ces primeniti samo na tu kolonu. Default je General koji kao sto pise koristi Excelovu logiku za prepoznavanje sta se nalazi u koloni. 
{% endtab %}
{% endtabs %}

