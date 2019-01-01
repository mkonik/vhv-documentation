---
title: Verovio Humdrum Viewer 
lang: pl
author: Craig Stuart Sapp
translator: Marcin Konik
creation_date: 3 Mar 2017
translation_date: 1 Jan 2019
last_updated: 4 Mar 2017
tags: [getting_started]
sidebar: main_sidebar
keywords: homepage
permalink: index.html
summary: 
---

Verovio Humdrum Viewer (VHV) to edytor muzyczny działający online w przeglądarce
internetowej. VHV za pomocą swojego interfejsu pozwala na interaktywne renderowanie 
partytury na podstawie pliku w formacie Humdrum znajdujacych się na stronie
[http://verovio.humdrum.org](http://verovio.humdrum.org). Zobacz także
stronę [Jak zacząć](/interface/getting_started) aby zapoznać się z samouczkami
dotyczącymi używania interfejsu VHV, lub przewertuj strony dokumentacji
za pomocą menu bocznego lub nawigacji na górze strony. Strony pomocy 
zostały ułożonwe według tematów:

<style>

dl {
	margin-left: 10%;
	margin-right: 10%;

}

dd {
	margin-top: 0 !important;
}

</style>

Interfejs użytkownika
: Opis interfejsu VHV oraz sposobów jego używania.

Komendy
: Lista skrótów klawiaturowych pozwalających na interakcję z interfejsem VHV.

Edytowanie graficzne
: Opis działań pozwalających na edytowanie notacji muzycznej w edytorze graficznym.

Filtry
: Filtry, które po zastosowaniu modyfikują dane.

Zasoby
: Opis muzycznych zasobów dostępnych online, które mogą być użyte w VHV.

Kodowanie Humdrum
: Tematy związane z różnymi aspektami zapisu muzycznego w składni Humdrum,
w większości bezpośrednio powiązane z możliwościami VHV. Zobacz stronę [Jak zacząć](/humdrum/getting_started) 
aby zapoznać się z interaktywnym samouczkiem dotyczącym kodowania muzyki w formacie Humdrum.
Bardziej szczególowa dokumentacja formatu znajduje się na stronie [Humdrum documentation](http://www.humdrum.org).

mojeVHV
: Instrukcje i przykładowe użycia programu [Verovio](http://www.verovio.org)
i [Humdrum](http://www.humdrum.org) w Twoich własnych projektaach.

Utrzymanie
: Tematy związane z tworzeniem i utrzymaniem tej strony. 

Indeksy
: Lista stron według kategorii tagów.


## Współtwórcy ##

<style>

ul.brief li {
	color: #aaa;
	padding: 0 !important;
	margin: 0 !important;
}

</style>

<dl>
<dt>Craig Stuart Sapp</dt>
<dd>Twórca</dd>
<dt>Alex Morgan</dt>
<dd>
<ul class="brief"> <li> algorytmy do oznaczania dysonansów za pomocą filtra <i><a href="/filters/dissonant">dissonant</a></i> </li> <li> definicje zawieszeń kadencyjnych w filtrze <i><a href="/filters/cint">cint</a></i> </li> </ul>
</dd>
<dt>Piotr Szyngiera</dt>
<dd>
<ul class="brief">
<li> walidacja poprawności składni Humdrum w edytorze ace</li>
<li> <a href="/interface/edit_modes">Podświetlanie składni Humdrum</a> </li> 
</ul>
</dd>
</dl>

Nie-programiści mogą uczestnoczyć w projekcie poprzez zgłaszanie
<a href="https://github.com/humdrum-tools/verovio-humdrum-viewer/issues">błędów
oraz próśb o nowe opcje</a> dla interfejsu VHV. Raport błędów dla
<a href="/filters">filtrów</a> powinny być zgłaszane do <a
href="https://github.com/craigsapp/humlib/issues">humlib</a>, a raporty
błędów oraz poprawki do edytora graficznego do
<a href="https://github.com/rism-ch/verovio/issues">verovio</a>.
Większa część stron dokumentacji VHV posiada przyciski, które mogą
być użyte w celu poprawiania literówek lub dodawania treści, przez osoby
posiadająceo konto na <a href="https://github.com">Githubie</a>.

### Główne składniki oprogramowania ###

<dl>

<dt> <a href="http://www.verovio.org">verovio</a></dt>
<dd> Music notation rendering in C++ (using MEI, with data imports from Humdrum and MusicXML and exports into SVG and MIDI)</dd>

<dt> <a href="http://humlib.humdrum.org">humlib</a></dt>
<dd> Musical data conversion and analysis tools in C++ (using Humdrum, with imports from MusicXML and MEI and exports into MEI and MIDI)</dd>

<dt> <a href="https://ace.c9.io">ace editor</a></dt>
<dd> JavaScript text editor</dd>

</dl>



## Institutional/Project Supporters ##

<style>

.logo {
	padding-top: 20px;
	padding-right: 20px;
}

.shadow {
	-webkit-filter: drop-shadow(3px 3px 2px rgba(0,0,0,0.2));
	drop-shadow(3px 3px 2px rgba(0,0,0,0.2));
}

</style>

<div style="margin-left: 100px">

<a class="logo" href="http://www.packhum.org"><img class="logo shadow" style="width:300px"  src="/images/phi-logo.png"></a>
<a class="logo" href="http://wiki.ccarh.org"><img class="logo shadow" style="width:300px" src="/images/ccarh-logo.png"></a>
<a class="logo" href="http://en.chopin.nifc.pl"><img class="logo shadow" style="width:350px" src="/images/nifc-logo.png"></a>
<a class="logo" href="https://simssa.ca/"><img class="logo shadow" style="width:250px" src="/images/simssa-logo.png"></a>

</div>

## Projects utilizing VHV ##

<div style="margin-left: 100px">

<a class="logo" href="http://www.tassomusic.org"><img class="logo shadow" style="width:300px" src="/images/tmp-logo.png"></a>
<a class="logo" href="http://josquin.stanford.edu"><img class="logo shadow" style="width:419px" src="/images/jrp-logo.png"></a>


</div>

After preparing music in VHV, it should be suitable for use with
music analysis and processing tools, such as <a target="_blank"
href="https://github.com/humdrum-tools/humdrum-tools">Humdrum
Tools</a>, and for easy display on webpages with the <a target="_blank"
href="https://plugin.humdrum.org">Humdrum notation plugin</a>.

For example, the Josquin Research Project (JRP) uses both the
Humdrum notation plugin to display musical incipits on <a target="_blank"
href="http://josquin.stanford.edu/work/?id=Jos2721">work pages</a> as well
as a random sample of the JRP score database displayed on the <a target="_blank"
href="http://josquin.stanford.edu">homepage</a>. In addition, some
analysis tools are implemented online through VHV.  An example
of this is the <a href="/filters/dissonant">dissonant</a>
tool.  Work pages, such as <a target="_blank"
href="http://josquin.stanford.edu/work/?id=Jos2721">this
one</a> have an analysis tool button labeled "Dissonant"
which links to VHV, loading the data from the website,
and doing the dissonance analysis <a target="_blank"
href="http://verovio.humdrum.org/?k=ey&filter=dissonant&file=jrp:Jos2721">within VHV</a>.

Files from other websites can be automatically be loaded into VHV by
giving a URL as the filename in the *file* CGI parameter.  For example,
this link to VHV:

<a target="_blank" href="https://verovio.humdrum.org/?file=https://raw.githubusercontent.com/craigsapp/beethoven-piano-sonatas/master/kern/sonata14-1.krn">https://verovio.humdrum.org/?file=https://raw.githubusercontent.com/craigsapp/beethoven-piano-sonatas/master/kern/sonata14-1.krn</a>

Embeds this URL to the Humdrum data for the first movement of Beethoven's <i>Moonlight</i>
sonata:

<a target="_blank" href="https://raw.githubusercontent.com/craigsapp/beethoven-piano-sonatas/master/kern/sonata14-1.krn">https://raw.githubusercontent.com/craigsapp/beethoven-piano-sonatas/master/kern/sonata14-1.krn</a>

This score is part of a Github repository of Beethoven piano sonatas:

<a target="_blank" href="https://github.com/craigsapp/beethoven-piano-sonatas">https://github.com/craigsapp/beethoven-piano-sonatas</a>

which is accessible from the bottom of the help menu in the VHV interface
(the question mark icon on the top left corner of the VHV page).





