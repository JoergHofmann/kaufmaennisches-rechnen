---
lang: $(Projekt.lang)
title: $(Projekt.title) 
pagetitle: $(Projekt.pagetitle) 
subtitle: $(Projekt.subtitle)
shorttitle: $(Projekt.shorttitle) 
cover: $(Projekt.cover)
author: $(Autor['name'])
date: '$(Monat[heute.month].MMMM) $(heute.year)'
git: $(GetShortGITHash "")
$(when (target~="moodle") [[header: true]])
...

:(Autor['mail']="joerg.hofmann@pecunia-non-olet.com")

$(include "kap01.md")
