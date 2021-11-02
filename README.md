<!--
title: Jak psát moderní učebnice
theme: gaia
class:
 - invert
headingDivider: 2 
paginate: true
-->

<!--
_class:
 - lead
 - invert
-->

# Jak psát moderní učebnice

[Miroslav Suchý](mailto:msuchy@redhat.com), [Sergei Petrosian](mailto:spetrosi@redhat.com), [Lukáš Růžička](mailto:lruzicka@redhat.com)

## Učebnice je klasika

![bg right](img/slabikar.jpg)

## Učebnice je klasika?

![bg right fit](img/baltik.jpg)

## Učebnice je klasika?

![bg right fit](img/not-found.png)

## Jenže...

Napsat učebnici trvá rok.

Vydat učebnici trvá taky rok.

## Takže...

V den vydání je učebnice prakticky dva roky stará.

## Errata

*Drobné aktualizace v kapitole 29 – Patologie GIT*

*Str. 509 a dále. Po odevzdání podkladů pro učebnici byla vydána nová WHO klasifikace nádorů trávicího systému, ve které byl „sesilní serrated adenom“ (SSA) přejmenován na „sesilní serrated lézi“ (SSL). Praktický dopad to má ten, že opět (po přibližně desetiletém intermezzu) platí staré pravidlo „každý adenom obsahuje dysplázie“ (protože SSA byl v tomto výjimkou).*

## Chuť k opravám

Různé formáty: Rukopis -> Nakladatelství -> Tiskárna

HTML, PDF a online publikace zpravidla nejsou původní zdroj.

Nízká bariéra pro opravy a úpravy.

## Komunitní dílo (+)

Jeden člověk vše neobsáhne.

Možnost použít jenom část díla.

Online přítomnost a aktuálnost.

## Komunitní dílo (-)

Autorské poplatky.

Neukážete to babičce.

## <!--fit--> Jak na to?

<!--
Tady si předáme slovo
-->

Je mnoho možností.

Ukážeme si jednu z mnoha.

## <!--fit--> Psaní dokumentace ve formátu "Docs as Code"

Principy Docs as Code:

- Správa verzí (Git)
- Open-source (Není nutné)
- Kontrola změn
- Automatické testování
- Automatické vygenerování a publikace materiálů
- Psání v značkovacích jazycích namísto .docx (Markdown, AsciiDoc, LateX, atd.)

## Vlastností jazyka Markdown

```md
# Název
## Kapitola 1. Tučné písmo, kurzíva, a monospace
Tento řádek obsahuje **tučné písmo**, *kurzívu*, a `monospace`

## Podkapitola 1.1. Číslovaný seznam pomoci čisel
1. Řádek 1
2. Řádek 2

## Kapitola 2. Seznam odrážek pomoci pomlček
- Řádek 1
 - Podřádek 1.1
- Řádek 2

## Kapitola 3. Okdazy
[Seznam.cz](https://www.seznam.cz/)
```

## Konverze souboru v rozšíření Markdown

Na konverzí textových souboru lze použit speciálně nástroje, jako například následující:
- `pandoc`
- `kramdoc`
- `marp`

<!--
Tady bude ukázka konverze příkladu do HTML pomocí pandoc
-->

## Jak je tato prezentace vytvořena

Tato prezentace je vytvořena pomocí [Marp](https://marp.app/) a [Marp Action](https://github.com/ralexander-phi/marp-action), které umožňují automatické nasazení prezentace na [GitHub Pages](https://pages.github.com/).

Tato prezentace je zároveň [webová stránka](https://spetrosi.github.io/jak_psat_moderni_ucebnice/) a [README.md](https://github.com/spetrosi/jak_psat_moderni_ucebnice/blob/master/README.md) soubor.

<!--
Tady bude ukázka konverze slajdů z README.md do HTML a PDF pomocí marp
-->

## Co když Markdown pro moje účele nestačí?

AsciiDoc je další značkovací jazyk který má větší funkcionalitu a je schopen plnit následující úkoly:
- Pomoci `include::` lze přidávat obsah souborů přímo do nynějšího textu
- AsciiDoc poskytuje sofistikovaněji strukturu dokumentů.
- Lze využit proměnné pro opakované použití stejného obsahu
- Lze použit HTML poznámky a upozornění
- Lze vytvořit obsah automatické

## Příklad dokumentace v AsciiDocu

Dokumentace __The Foreman__ je psána v AsiiDocu.

- Cílová stránka: https://docs.theforeman.org/.
- Zdroj dokumentace nahází na GitHubu: https://github.com/theforeman/foreman-documentation.

<!--
Tady bude ukázka jak Foreman docs používají AsciiDoc pro generace své dokumentace
-->

<!--
Tady si předáme slovo
-->

# 🎉
<!--
_class:
 - lead
 - invert
-->
### Otázky a odpovědi
