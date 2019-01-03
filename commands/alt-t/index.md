---
title: <span class='keypress'>alt-t</span>/<span class='keypress'>alt-T</span>
lang: pl
ref: commands-alt-t
author: Craig Stuart Sapp
translator: Marcin Konik
creation_date: 16 Oct 2017
translation_date: 3 Jan 2019
last_updated: 16 Oct 2017
tags: [all, commands]
sidebar: main_sidebar
keywords: polecenia interfejsu zapisywanie pliku pdf
summary: "Skróty <span class='keypress'>alt-t</span>/<span class='keypress'>alt-T</span> spowodują zapisanie aktualnego widoku strony lub całej partytury do pliku w formacie PDF."
permalink: /commands/alt-t/index.html
---

## Zapisywania aktualnie widocznej strony

Naciśnięcie <span class = "keypress"> alt-t </ span> spowoduje pobranie pliku PDF zawierającego aktualnie
wyświetlaną muzykę na stronę partytury. Jeśli zapis muzyczny jest szerszy niż wyższy, pobrany plik PDF będzie
w formacie leżącym; w przeciwnym razie plik PDF będzie miał orientację pionową.

Pliki będą zapisywane w miejscu, w którym przeglądarka domyślnie przeglądarka zapisuje pobrane pliki.
Poniżej demonstracja działania polecenia <span class="keypress">alt-t</span> zapisującego plik pdf i otwarcia do w przeglądarce.

{% include image.html
	file="save-pdf.gif"
	alt="zapisywanie aktualnego widoku do pdf"
	caption="Zapisywanie aktualnego widoku strony partytury do pliku PDF."
%}

## Zapisywanie całej partytury do pliku PDF

Pressing <span class="keypress">alt-shift-T</span> will download a PDF
containing the entire score. The layout in VHV will not be used but
rather the music will be typeset for letter-sized paper in portrait
orientation:

{% include image.html
	file="save-full-pdf.gif"
	alt="zapisywanie całej partytury do pliku PDF"
	caption="Zapisywanie całej partytury do pliku PDF."
%}
