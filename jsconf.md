# JSConf in 10 minuten

Rick en Michel van ilionx Interactive Marketing waren het hele vorige weekend in Berlijn voor CSSconf en JSConf EU 2019. 
Eerder las je al een kort verslag van [CSSconf](cssconf). Hieronder volgen korte samenvattingen van een paar presentaties van 
JSConf. Met de zoektermen kun je zelf meer informatie vinden.

## [Laurie Voss - JavaScript: who, what, where, why and next](https://2019.jsconf.eu/laurie-voss/javascript-who-what-where-why-and-next.html)

Laurie Voss, Chief Data Officer van npm, presenteerde de trends voor JavaScript en plugde nog even zijn eigen product
npm enterprise. Serverless is populair. React is alomtegenwoordig. Vue groeit enorm snel. Op de backend is Express 
verreweg het grootst, maar Gatsby groeit. En TypeScript wordt steeds populairder.

*Zoektermen: [React](https://www.google.com/search?q=react);  [Vue JS](https://www.google.com/search?q=vue+js);
[Express JS](https://www.google.com/search?q=express+js); [Gatsby](https://www.google.com/search?q=gatsby);
[TypeScript](https://www.google.com/search?q=typescript)*


## [Tara Z. Manicsic - ES2019 Features: What even are they?](https://2019.jsconf.eu/tara-z-manicsic/es2019-features-what-even-are-they.html)

Nadat het 6 jaar geduurd had voordat EcmaScript 6 (of "JavaScript 6") uitkwam, is er nu weer
een werkend proces en komt er elk jaar een nieuwe EcmaScript-standaard uit. Tara Manicsic gaf een overzicht van de
nieuwe features in 2019. Nieuwe operators zijn String.trimStart (in plaats van trimLeft, omdat niet alle talen van
links naar rechts schrijven), catch zonder variabele binding, Array.flat, Array.flatMap en 
Object.fromEntries (tegengestelde van Object.entries). Array.sort wisselt geen items meer om als ze identiek zijn.

*Zoektermen: [What's new in es 2019](https://www.google.com/search?q=what%27s+new+in+es+2019); 
[tc39 process](https://www.google.com/search?q=tc39+process)*

## [Shwetank Dixit - Block, unblock, block!: how ad blockers are being circumvented, and how they are fighting back](https://2019.jsconf.eu/shwetank-dixit/block-unblock-block-how-ad-blockers-are-being-circumvented-and-how-they-are-fighting-back.html)

Sinds de introductie van ad blockers is er een hele industrie ontstaan die aanbiedt om ad blockers te omzeilen. Shwetank
Dixit vertelt over de smerige trucs die worden toegepast, en de antwoorden van ad blockers daarop. Een voorbeeld is een
techniek die advertenties ongewenst toont, maar de advertenties snel weghaalt zodra je de developer tools opent om te
kijken waar ze vandaan komen. Het antwoord: een script dat de advertenties doet denken dat de developer tools open 
staan, zodat de advertenties niet getoond worden.

*Zoektermen: [ad blocker circumvention](https://www.google.com/search?q=ad+blocker+circumvention)*

## [Amanda Sopkin - What JS Developers can learn from medieval coats of arms about accessibility](https://2019.jsconf.eu/amanda-sopkin/what-js-developers-can-learn-from-medieval-coats-of-arms-about-accessibility.html)

Amanda Sopkin legt regels voor accessibility uit aan de hand van wapenschilden. Wapenschilden moeten gemakkelijk
uit elkaar te houden zijn, een goed kleurcontract hebben, heldere thema's hebben, en herkenbaar zijn door mensen
van verschillende achtergronden. Haar lessen zijn: wees voorzichtig met symbolen zoals handgebaren (die
kunnen in een andere taal iets heel anders betekenen), ontwikkel een consequent raamwerk en houd je aan Jakobs
law of the internet user.

*Zoektermen: [Jakob's law](https://www.google.com/search?q=jakob%27s+law)*


## [Manu Martinez-Almeida - Stencil: A built-time approach to the web](https://2019.jsconf.eu/manu-martinez-almeida/stencil-a-built-time-approach-to-the-web.html)

Stencil is een framework waarmee je zelf gemakkelijk en snel web components ontwikkelt. Het is van de makers van Ionic,
die het ontwikkeld hebben omdat ze niet alleen Angular, maar alle frameworks wilden ondersteunen. Waar frameworks goed
zijn voor het maken van apps, kun je voor herbruikbare componenten beter webcomponents ontwikkelen. Stencil ondersteunt
zowel nieuwere als oudere browsers, en bepaalt zelf wanneer polyfills meegeladen moeten worden. Web components gemaakt
met Stencil hebben standaard geen dependencies.

*Zoektermen: [Stencil JS](https://www.google.com/search?q=stencil+js)*

## [C J Silverio - The economics of open source](https://2019.jsconf.eu/c-j-silverio/the-economics-of-open-source.html)

C J Silverio, ex CTO van npm, hield een betoog waarom het geen goed idee is als we al onze open source code in handen
geven van een commercieel bedrijf (npm) en ons volledig van dat bedrijf afhankelijk maken. Ze kondigde een open en
gedistribueerde repository aan (nog in ontwikkeling), en kreeg een staande ovatie.

*Zoektermen: [Entropic package manager](https://www.google.com/search?q=entropic+package+manager)*


## [Nick Kreeger - Tensorflow.JS: Bringing machine learning to the web and beyond](https://2019.jsconf.eu/nick-kreeger/tensorflowjs-bringing-machine-learning-to-the-web-and-beyond.html)

Tensorflow.js is een library waarmee je in de browser machine learning kunt toepassen. Dat kan real time in de browser, 
dus zonder dat je data naar derden hoeft te sturen. Gebruiksgemak is een belangrijk onderdeel en er zijn een aantal
al getrainde algoritmes beschikbaar die je zo kunt gebruiken, zoals voor het herkennen van lichamen in video, of het
herkennen van het sentiment van een tekst.

*Zoektermen: [Tensorflow JS](https://www.google.com/search?q=tensorflow+js); [ml5 js](https://www.google.com/search?q=ml5+js)*

## [Maxim Koretskyi - A sneak peek into super optimized code in JS frameworks](https://2019.jsconf.eu/maxim-koretskyi/a-sneak-peek-into-super-optimized-code-in-js-frameworks.html)

Max Koretskyi leest als hobby broncode van Angular en React en legde een aantal technieken uit waarmee deze frameworks
supergeoptimaliseerde JavaScript schrijven. Met monomorphisms zorg je ervoor dat verschillende objecten dezelfde shape
(interface) hebben, waardoor JavaScript dezelfde shapes steeds kan hergebruiken. Met bloom filters kun je heel snel
uitsluiten dat een element in een verzameling zit, en Angular gebruikt dit om snel te checken of een injector de 
beschikking heeft over een specifieke dependency.

*Zoektermen: [ng wizard](https://www.google.com/search?q=ng+wizard); 
[shape memory javascript](https://www.google.com/search?q=shape+memory+javascript);
[bit fields](https://www.google.com/search?q=bit+fields);
[bloom filters](https://www.google.com/search?q=bloom+filters)*


## [Maximiliano Firtman - The modern PWA Cheat Sheet](https://2019.jsconf.eu/maximiliano-firtman/the-modern-pwa-cheat-sheet.html)

Apps volgen je op allerlei manieren. Eigenlijk zouden we allemaal PWA's moeten schrijven. Maximiliano Firtman gaf tips
bij het schrijven van PWA's. Bijvoorbeeld dat je voor iOS altijd zelf een back-button moet toevoegen, omdat die er anders
niet is. Hij vertelde over de web share API en het kunnen maken van foto's. Android maakt van een PWA acht een APK, 
zodat die echt als een native app werkt. En iOS heeft dan weer GEEN documentatie over PWA's. De stappen voor het maken
van een PWA: schrijf een web app manifest, voeg je eigen "installeer als app"-button toe (werkt alleen op Android),
voeg iOS metadata toe, en maak een app launcher.

*Zoektermen: [@shouldbepwa](https://www.google.com/search?q=%40shouldbepwa);
[progressive web app](https://www.google.com/search?q=progressive+web+app)*


## [Max Bittker - Simulating Sand: Building interactivity with webassembly](https://2019.jsconf.eu/max-bittker/simulating-sand-building-interactivity-with-webassembly.html)

Max Bittker ontwikkelde een website met een zandspel. Code die goed moet performen heeft hij geschreven in Rust en
vertaald naar WebAssembly. De rest van de code is geschreven in JavaScript. De twee combineren goed, en web assembly
is geschikt om vandaag te gaan gebruiken. Met wasm-pack compileer je je Rust code gemakkelijk naar web assembly.

*Zoektermen: [sandspiel](https://www.google.com/search?q=sandspiel);
[Rust lang](https://www.google.com/search?q=rust+lang)* 
