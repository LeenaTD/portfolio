---
Title: Load
Description: This is analysis of load
Template: analys
---

# Laddningstider

Urval
-----------------------
Följande webbplatser valdes:<br>
[ICA](https://handla.ica.se/) <br>
[Power](https://www.power.se/) <br>
[Aftonbladet](https://www.aftonbladet.se/) <br>

![ica2](%assets_url%/img/ica2.png){.ica2}

![power2](%assets_url%/img/power2.png){.power2}

![aftonbladet2](%assets_url%/img/aftonbladet2.png){.aftonbladet2}


Metod
------------------------
Metoden för denna analys kommer att vara att först använda oss av verktyget PageSpeed Insights för att kunna jämföra värden av de olika webbsidorna i både mobil och destopsläge. Sedan kommer även nedladdningshastigheter och datasmängd jämföras med hjälp av devstool. 


Resultat
-----------------------

<iframe style="width:50%; height:500px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTVPbQ919u_4x9bCdJzqvmLycEIsucCUSr9fvLQBtf1w2T6bhjzPLODPPmiaHR8z-2gq2wMaxrHMe7-/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>



Analys
-----------------------
Vi börjar med att se över LCP för våra valda sidor och här kan vi se att de mobila webbsidorna tar längre tid för att ladda i jämförelse med webbsidor på desktop, med Power som hade sämst laddningstid. Vi kan även se ett liknande resultat för FCP, och även här är det Power som tar längst tid. Gällande TTFB, får vi samma resultat där destop är mer optimerat än mobil.<br>

Fortsättningsvis, när vi ser över resultat med hjälp av devtool visar det att både Aftonbladet och ICA har liknande i deras transferred datamängd medan Power skickar en mindre datamängd till servern. För laddningstiden, kan vi se stor skillnad mellan ICA och de två andra webbsidorna, då ICA laddar in på ungefär en tredjedel av tiden.<br>

Slutligen när vi ser på prestanda genom PageSpeed Insights visar verktyget att ICA får ett bättre betyg i jämnförelse med de andra två sidorna. Det visar även att i rekommenderingarna om vad som kan förbättras att i ICA var det endast problem med optimering av storlek i bilderna på webbsidan. För Power och Aftonbladet var det dock körtiden för JavaScript som skapade problem för webbsidorna. Ytterligare verkar det vara viss problematik med både Aftonbladet och Power i deras div om cookies där det har skett layoutförskjutningar.<br>

För att rangordna webbsidorna skulle ICA webbsidan vara nummer 1 med tanke på laddningshastighet och optimering. Sedan kommer Aftonbladet som plats 2 och slutligen Power på plats 3 på grund av att den har visat sämre resultat i alla kategorier.<br>

Personligen skulle jag uppfatta en snabb webbsida är en webbsida som har en laddningstid under en sekund, medan en långsam webbsida är över två sekunder. I fallet med mitt urval av webbsidor skulle jag säga att alla får ett godkänt betyg trots att Power kan ta lite längre tid än de andra webbsidorna. 


Övrigt
-----------------------

Leena Thuy Dung
