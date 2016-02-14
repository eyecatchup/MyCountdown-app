# MyCountdown

Erstelle deine eigenen Countdown-_"Apps"_ im Handumdrehen.  
Create your custom Countdown-_"Apps"_ with ease.

## How-To (DE)..

> **NOTE:** EN version below.

[Unter folgender URL ist die Countdown-App erreichbar][appbase]:

    https://eyecatchup.github.io/MyCountdown-app/
    
Ohne weitere Parameter aufgerufen, zeigt die Seite den Countdown bis zum jeweils kommenden Silvester an.

Durch zusätzliche Parameter kann die Countdown-App individualisiert _(und dann z.B. als Lesezeichen auf deinem Smartphone-Homescreen gespeichert)_ werden.

---

### Eigenes Event

**1.)** Kopiere folgende URL

    https://eyecatchup.github.io/MyCountdown-app/?name={$name}&date={$date}&lang=DE

**2.)** Ersetze `{$name}` mit dem Namen deines Events.

**3.a)** Ersetze `{$date}` mit dem Termin des Events (Format: `mm/dd/YYYY`).  
**3.b)** *Optional:* Um Uhrzeiten mit anzugeben, verwende das amerikanische <nobr>12-Stunden-Format</nobr>: `mm/dd/YYYY H:i:s (AM|PM)`.

##### Beispiele:

1. [https://eyecatchup.github.io/MyCountdown-app/?name=Weihnachten&date=12/24/2016&lang=DE][ex1de]
2. [https://eyecatchup.github.io/MyCountdown-app/?name=zum Eröffnungsspiel WM 2018&date=06/14/2018&lang=DE][ex2de]

---

### Hintergrundbild ändern

**1.)** Kopiere folgende URL

    https://eyecatchup.github.io/MyCountdown-app/?img={$img}

**2.a)** Ersetze `{$img}` mit `2.jpg` um das (einzige) Alternativbild zu verwenden.  
**2.b)** *ODER:* Ersetze `{$img}` mit einer beliebigen Bild-URL um dein eigenes Alternativbild zu verwenden.

##### Beispiele:

1. [https://eyecatchup.github.io/MyCountdown-app/?img=2.jpg][ex3de]
2. [https://eyecatchup.github.io/MyCountdown-app/?img=https://i.imgur.com/pWNgnmO.jpg][ex4de]

Das ganze kannst du natürlich auch in Kombination mit allen anderen Optionen verwenden. Zum Beispiel:

1. [https://eyecatchup.github.io/MyCountdown-app/?name=zum Eröffnungsspiel WM 2018&date=06/14/2018&img=https://i.imgur.com/sRQDi8L.jpg&lang=DE][ex5de]

---

## How-To (EN)..

[The base URL of the Countdown-App is][appbase_en]:

    https://eyecatchup.github.io/MyCountdown-app/?lang=EN
    
Without additional parameters, it will show you the countdown to next New Year's eve. Note: as soon as you set your custom event (see below), the `lang` parameter can be ommited (you *could* have the rest of the texts in German by setting `lang=DE`)!

There're several options to customize the countdown to fit your needs _(so you save the final Link as a bookmark on your smartphone's home screen, for example)_.

---

### Custom event

**1.)** Copy the following URL

    https://eyecatchup.github.io/MyCountdown-app/?name={$name}&date={$date}

**2.)** Replace `{$name}` with the name of your event.

**3.a)** Replace `{$date}` with the date of your event (Format: `mm/dd/YYYY`).  
**3.b)** *Optional:* To use not only a date but also a specific time, use the format: `mm/dd/YYYY H:i:s (AM|PM)`.

##### Examples:

1. [https://eyecatchup.github.io/MyCountdown-app/?name=christmas&date=12/24/2016][ex1en]
2. [https://eyecatchup.github.io/MyCountdown-app/?name=kickoff of FIFA WC 2018&date=06/14/2018][ex2en]

---

### Custom backgound image

**1.)** Copy the following URL

    https://eyecatchup.github.io/MyCountdown-app/?img={$img}

**2.a)** Replace `{$img}` with `2.jpg` to use the (only) alternative background image.  
**2.b)** *OR:* Replace `{$img}` with any custom image URL to use it as a background image.

##### Examples:

1. [https://eyecatchup.github.io/MyCountdown-app/?img=2.jpg][ex3de]
2. [https://eyecatchup.github.io/MyCountdown-app/?img=https://i.imgur.com/pWNgnmO.jpg][ex4de]

Of course, you can also combine all the options. For example:

1. [https://eyecatchup.github.io/MyCountdown-app/?name=kickoff of FIFA WC 2018&date=06/14/2018&img=https://i.imgur.com/sRQDi8L.jpg][ex5en]

---

Viel Spaß / enjoy!

(c) 2016 Stephan Schmitz  
License: MIT

[appbase]: https://eyecatchup.github.io/MyCountdown-app/ "MyCountdown App"  
[appbase_en]: https://eyecatchup.github.io/MyCountdown-app/?lang=EN "MyCountdown App"  
[ex1de]: https://eyecatchup.github.io/MyCountdown-app/?name=Weihnachten&date=12/24/2016&lang=DE "Beispiel 1 (DE): Eigenes Event"  
[ex2de]: https://eyecatchup.github.io/MyCountdown-app/?name=zum%20Er%C3%B6ffnungsspiel%20der%20WM%202018&date=06/14/2018&lang=DE "Beispiel 2 (DE): Eigenes Event"  
[ex3de]: https://eyecatchup.github.io/MyCountdown-app/?img=2.jpg "Beispiel: Alternatives Hintergrundbild / Example: alternative background image"  
[ex4de]: https://eyecatchup.github.io/MyCountdown-app/?img=https://i.imgur.com/pWNgnmO.jpg "Beispiel: Eigenes Hintergrundbild / Example: custom background image"  
[ex5de]: https://eyecatchup.github.io/MyCountdown-app/?name=zum%20Er%C3%B6ffnungsspiel%20der%20WM%202018&date=06/14/2018&img=https://i.imgur.com/sRQDi8L.jpg&lang=DE "Beispiel: Eigenes Event + Bild"  
[ex1en]: https://eyecatchup.github.io/MyCountdown-app/?name=christmas&date=12/24/2016 "Example 1 (EN): Custom Event"  
[ex2en]: https://eyecatchup.github.io/MyCountdown-app/?name=kickoff%20of%20FIFA%20WC%202018&date=06/14/2018 "Example 2 (EN): Custom Event"  
[ex3en]: https://eyecatchup.github.io/MyCountdown-app/?img=2.jpg&lang=EN "Example: alternative background image"  
[ex4en]: https://eyecatchup.github.io/MyCountdown-app/?img=https://i.imgur.com/pWNgnmO.jpg&lang=EN "Example: custom background image"  
[ex5en]: https://eyecatchup.github.io/MyCountdown-app/?name=kickoff%20of%20FIFA%20WC%202018&date=06/14/2018&img=https://i.imgur.com/sRQDi8L.jpg "Example: Custom Event + background image"  
