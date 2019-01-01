---
title: <span class='keypress'>alt-f</span>
lang: pl
ref: commands-alt-f
author: Craig Stuart Sapp
translator: Marcin Konik 
creation_date: 5 Mar 2017
translation_date: 1 Jan 2019
last_updated: 5 Mar 2017
tags: [all, commands]
sidebar: main_sidebar
keywords: polecenia interfejsu blokowanie renderowania notacji
summary: "Skrót <span class='keypress'>alt-f</span> blokuje/odblokowuje dynamiczne renderowanie notacji muzycznej."
permalink: /commands/alt-f/index.html
---

Pressing <span class="keypress">alt-f</span> will toggle between
freezing/unfreezing dynamic notation rendering.  Normally any change
in the text editor's content will trigger a re-rendering of the
graphical notation.  For large files, this takes an increasingly
longer and longer time with the current architecture.  In order to
speed up data entry in the text editing window, the notation can
be frozen with the <span class="keypress">alt-f</span> command.

While the notation generation is frozen, any changes made in the text
editor will not trigger an update in the notation.  After changes have been
made, pressing <span class="keypress">alt-f</span> will unfreeze the notation
and it will be updated to match the current contents of the text editor.

When the notation is frozen, the background of the notation turns white.  Unfreezing
the notation will return the background color to off-white:

{% include image.html
	file="freeze-unfreeze.gif"
	alt="freezing and unfreezing notation."
	caption="Freezing and unfreezing notation while typing in the text editor."
%}




