---
layout: post
title:  "Visitenkarte"
---

Die kleine Website "Visitenkarte" war nun mein erstes Projekt.  
Mir hat die Idee dahinter gefallen: Eine Art Visitenkarte mit verschiedenen Tabs, in jedem Tab werden andere Infos geladen. Ich war ehrlich
gesagt zu faul die ganzen Infos einzupflegen, daher der Lorem ipsum Text. Mir ging es dabei ausschließlich um die Funktion der Seite. Daher ist das Design auch keine Glanzleistung.  
Bei <code>click</code> wird auf den entsprechenden Tab ein <code>active</code> gesetzt und der dazugehörige Contentblock auf der rechten Seite bekommt ein <code>show</code>, 
die anderen Contentblöcke ein <code>hide</code>.  
Damit man noch über die direkte URL auf den jeweiligen Tab kommt, also z.B. bei <code>#portfolio</code> auf den Tab portfolio, überprüfe ich die URL auf den Link und zeige den entsprechenden Tab an:  
  
<code>if (window.location.hash == "#portfolio") {$portfolio();}</code>  
  
Alles in allem kein großer Zauber, für mein erstes Projekt eine "Leistung" die voll ok ist und es hat mir richtig Spaß gemacht hat.  
Gesamter Zeitaufwand: ca. 4-5 Stunden  
Vorlage: [blacktie demo](http://blacktie.co/demo/victoria/){:target="_blank"}  
Seite: [Visitenkarte](http://code.pbergmeir.com/business-card/index.html){:target="_blank"}