# Kursus

Dette repository indeholder generel info relateret til [mine](#michell) kurser og foredrag. Fejl, rettelser og tilføjelser imødeses meget gerne.

## Indhold

- [Udviklingsmiljø og plugins/extensions](#udviklingsmilj%c3%b8-og-pluginsextensions)
  - [Visual Studio](#visual-studio)
  - [Visual Studio Code](#visual-studio-code)
  - [Andet](#andet)
- [Runtime](#runtime)
- [Browsere](#browsere)
- [Standarder](#standarder)
- [Web udvikling](#web-udvikling)
  - [Teknologier](#teknologier)
  - [Diverse værktøjer og ressourcer til web udvikling](#diverse-v%c3%a6rkt%c3%b8jer-og-ressourcer-til-web-udvikling)
  - [Diverse HTML/CSS/JS/WASM eksempler](#diverse-htmlcssjswasm-eksempler)
  - [Opgaver relateret til web udvikling](#opgaver-relateret-til-web-udvikling)
- [Service/API/REST](#serviceapirest)
- [Spil og 3D](#spil-og-3d)
- [Automatisering / software robotter](#automatisering--software-robotter)
- [Grundlæggende IT](#grundl%c3%a6ggende-it)
- [AI/ML](#aiml)
- [Programmering og børn](#programmering-og-b%c3%b8rn)
- [Bøger](#b%c3%b8ger)
- [Nyhedsbreve og blogs](#nyhedsbreve-og-blogs)
- [Diverse programmer](#diverse-programmer)
- [Historie](#historie)
- [Diverse](#diverse)
- [Michell](#michell)

# Udviklingsmiljø og plugins/extensions

## Visual Studio
- [Visual Studio](https://visualstudio.microsoft.com/vs/) 
  - Visual Studio Extensions
    - [Resharper](https://www.jetbrains.com/resharper/)
    - [CodeMaid](https://marketplace.visualstudio.com/items?itemName=SteveCadwallader.CodeMaid)
    - [Open Command Line](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.OpenCommandLine)
    - [Add New File](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.AddNewFile)
  - Snippets
    - [Ekstra C# snippets](https://github.com/devcronberg/kursus/blob/master/vs/readme.md)
  - [.editorconfig brugt på kurser](https://github.com/devcronberg/cskursus-editorconfig)

## Visual Studio Code      
- [Visual Studio Code](https://code.visualstudio.com/)
    - Emmet
      - [Eksempler på mest brugte Emmet funktioner](https://github.com/devcronberg/emmet#basic-emmet-abbreviations)
      - [Emmet Cheatsheet](https://docs.emmet.io/cheatsheet-a5.pdf)
    - Snippets
      - [Snippets JavaScript](https://github.com/devcronberg/kursus/blob/master/vsc/snippetsjs.md)
      - [Snippets TypeScript](https://github.com/devcronberg/kursus/blob/master/vsc/snippetsts.md)
      - [Snippets MarkDown](https://github.com/devcronberg/kursus/blob/master/vsc/snippetsmd.md)
    - [Keyboard shortcuts](https://github.com/devcronberg/kursus/blob/master/vsc/keyboard.md)
    - Plugins til VSC (søg efter dem i VSC eller på [marketplace](https://marketplace.visualstudio.com/search?target=VSCode&sortBy=Installs)). Du kan også finde en [extensions.json](https://github.com/devcronberg/kursus/blob/master/vsc/.vscode/extensions.json), og placere denne under /.vscode. Så dukker extensions op som anbefalede.
      - CSharp
      - Prettier
      - Markdown all in one
      - Auto rename tag
      - IntelliSense for CSS class names in HTML
      - ESLint
      - TSLint
      - W3C Validation
      - Live Server
      - CSSTree validator
      - Visual Studio IntelliCode
      - Bracket Pair Colorizer
      - JavaScript (ES6) code snippets
      - HTMLHint  
      - W3C Validation
## Andet
- [Rider](https://www.jetbrains.com/rider/)

# Runtime
- [Node](https://nodejs.org/en/)
- [.NET Core](https://dotnet.microsoft.com/download)
- [.NET Framework](https://dotnet.microsoft.com/download/dotnet-framework/net472)
- [Python](https://www.python.org/)

# Browsere
- [Chrome](https://www.google.com/chrome/)
  - [Validity](https://chrome.google.com/webstore/detail/validity/bbicmjjbohdfglopkidebfccilipgeif)
  - [Markdown Viewer](https://chrome.google.com/webstore/detail/markdown-viewer/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)
  - [Yet Another REST Client](https://chrome.google.com/webstore/detail/markdown-viewer/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)
  - [Web Developer](https://chrispederick.com/work/web-developer/)  
  - [json-formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en)
  - [Copy CSS selector](https://chrome.google.com/webstore/detail/copy-css-selector/kemkenbgbgodoglfkkejbdcpojnodnkg)
  - [Autofill](https://chrome.google.com/webstore/detail/autofill/nlmmgnhgdeffjkdckmikfpnddkbbfkkk)
- [Canary](https://www.google.com/chrome/canary/)
- [Brave](https://brave.com/)
- [Firefox](https://www.mozilla.org/en-US/firefox/)   
- [Microsoft Edge](https://www.microsoft.com/da-dk/windows/microsoft-edge)   
- [Opera](https://www.opera.com/da)
- [Vivaldi](https://vivaldi.com/da/)

# Standarder
- [HTML (5.1)](https://www.w3.org/TR/?tag=html#w3c_all)
  - [HTML W3C validator](https://validator.w3.org/)
  - [Validity - Chrome plugin](https://chrome.google.com/webstore/detail/validity/bbicmjjbohdfglopkidebfccilipgeif)
  - [HTML5 Boilerplate - HTML template](https://html5boilerplate.com/)
- [CSS (current work)](https://www.w3.org/Style/CSS/current-work)
  - [CSS W3C validator](https://jigsaw.w3.org/css-validator/)
  - [HTML5Up - HTML og CSS templates](https://html5up.net/)
  - [Brug eventuelt "Can I Use" for at få en ide om support](https://caniuse.com/)  
- [ECMA (2019)](https://www.ecma-international.org/publications/standards/Ecma-262.htm)
  - [ES Lint](https://eslint.org/)
- [WebAssembly (webassembly.org)](https://webassembly.org/)


# Web udvikling

## Teknologier
- [Electron - desktop udvikling](https://electronjs.org/)
- [Cordova - mobil udvikling](https://cordova.apache.org/)
  - [PhoneGap](https://phonegap.com/)  

## Diverse værktøjer og ressourcer til web udvikling
- [Front-end Developer Handbook](https://frontendmasters.com/books/front-end-handbook/2019/)
- [Fiddler - HTTP Proxy](https://www.telerik.com/fiddler)
- [Curl - HTTP via konsol](https://curl.haxx.se/)  
- [BrowserStack - UI test](https://www.browserstack.com/)
- [Awesome Blazor - A collection of awesome Blazor resources](https://github.com/AdrienTorris/awesome-blazor)
- [Lorem Ipsum - tekst](https://www.lipsum.com/)
- [Bookmarklet](http://caiorss.github.io/bookmarklets.html)
- [Flexyboxes - editor til FlexBox](https://the-echoplex.net/flexyboxes/)
- Billeder
  - [Pixabay - gratis billeder](https://pixabay.com/)  
  - [Pexels - gratis billeder og video](https://www.pexels.com/)
  - [Burst - gratis billeder](https://burst.shopify.com/)
  - [Picsum - Temp. billeder](https://picsum.photos/)
- [Google fonts](http://www.google.com/fonts)
- [SoundBible - gratis lyde](http://soundbible.com/)
- Favicon
  - [Favicon - favicon baseret på tekst](https://favicon.io/favicon-generator/)
  - [Gauger - favicon baseret på Font Awesome](https://gauger.io/fonticon/)
- "Legepladser"
  - [Code Sandbox](https://codesandbox.io/)
  - [Playcode - nem HTML/JS/CSS legeplads](https://playcode.io/)
  - [Codepen - HTML/CSS/JS (mv) legeplads](https://codepen.io/)
- Hosting
  - [Netlify - nem SPA hostning baseret på github](https://www.netlify.com/)
- CSS Frameworks
  - [Sammenligning af CSS Frameworks](http://usablica.github.io/front-end-frameworks/compare.html)
  
## Diverse HTML/CSS/JS/WASM eksempler
- [Simpel WebApp - HTML/CSS/JS/WASM](https://github.com/devcronberg/sap-webapp)   
- [Aqarium](https://webglsamples.org/aquarium/aquarium.html)
- [Sol system](https://codepen.io/juliangarnier/pen/idhuG)
- [Shapes of CSS](https://css-tricks.com/the-shapes-of-css/)
- [SpinKit](https://tobiasahlin.com/spinkit/)
- [HoverCSS](http://ianlunn.github.io/Hover)
- [AnimateCSS](https://daneden.github.io/animate.css/)
- [Periodisk tabel](https://threejs.org/examples/css3d_periodictable.html)
- [Blazor spil](https://github.com/AdrienTorris/awesome-blazor#games)

## Opgaver relateret til web udvikling
- [Opgaver til HTML](https://github.com/devcronberg/undervisning-html-opgaver)
- [Opgaver til CSS](https://github.com/devcronberg/undervisning-css-opgaver)
- [Opgaver til JS](https://github.com/devcronberg/undervisning-js-opgaver)
- [Opgaver til TS](https://github.com/devcronberg/undervisning-ts-opgaver)
- [CSS Dinner - genial måde at lære at bruge en CSS selector](https://flukeout.github.io/)

# Service/API/REST
- [Random.org - tilfældige tal via service](https://www.random.org/integers/?num=1&min=1&max=6&col=1&base=10&format=plain&rnd=new)
- [Filltext - simpel tilfældig JSON data](http://www.filltext.com/)
- [Jsonplaceholder](https://jsonplaceholder.typicode.com/)
- [jsonbox.io - JSON Storage](jsonbox.io)
- [GSX2JSON - Google Spreadsheet to JSON API service](http://gsx2json.com/)
- [OpenWeatherMap](https://openweathermap.org/api) (brug venligst egen gratis APPID)
  - [Byer](https://api.openweathermap.org/data/2.5/weather?q=Odense,dk&APPID=331058fde3cb9a6d1f0751c9fd7dacf4&units=metric)
  - [Forecast](http://api.openweathermap.org/data/2.5/forecast/daily?q=Odense,dk&cnt=5&APPID=331058fde3cb9a6d1f0751c9fd7dacf4&units=metric)
- [DAWA](https://dawa.aws.dk/)
  - [Kommuner](https://dawa.aws.dk/kommuner/)
  - [Landsdele](https://dawa.aws.dk/landsdele/)
  - [Postnumre](https://dawa.aws.dk/Postnumre)
  - [Regioner](https://dawa.aws.dk/Regioner)
  - [Byer](https://dawa.aws.dk/stednavne2?hovedtype=Bebyggelse&undertype=by)
- [My JSON Server](https://my-json-server.typicode.com/)

# Spil og 3D
- [Unity](https://unity.com/)
- [MonoGame](http://www.monogame.net/)

# Automatisering / software robotter
- [AutoHotkey](https://www.autohotkey.com/)
  - [Lille demo script](https://gist.github.com/devcronberg/9fdd58233c9482644730dc64f494598c#file-autohotkey)
- [Blue Prism](https://www.blueprism.com)
- [UI Path](https://www.uipath.com/)

# Grundlæggende IT
- [CS Demo](https://csdemo.cronberg.dk) - talsystemer, porte mv

# AI/ML
- [ML.NET](https://dotnet.microsoft.com/apps/machinelearning-ai/ml-dotnet)
- [The age of AI - YouTube](https://www.youtube.com/playlist?list=PLjq6DwYksrzz_fsWIpPcf6V7p2RNAneKc)


# Programmering og børn
- [Micro:Bit](https://microbit.org/)
- [AppInventor](https://appinventor.mit.edu/)
- [Scratch](https://scratch.mit.edu/)
- [Coding Pirates](https://codingpirates.dk/)
- [Hour of code - DK](https://hourofcode.com/dk)


# Bøger
- [Weaving the Web](https://www.amazon.com/Weaving-Web-Original-Ultimate-Destiny/dp/006251587X)
- [CODE: The hidden language of computer hardware and software](https://www.amazon.com/Code-Language-Computer-Hardware-Software/dp/0735611319)
- [Fortællingen om universet](https://www.arnoldbusck.dk/boeger/astronomi/fortaellingen-om-universet)
- [Hitchhiker's Guide to the Galaxy](https://www.amazon.com/Hitchhikers-Guide-Galaxy-Douglas-Adams/dp/0575115343)

# Nyhedsbreve og blogs
- [Hackernewsletter](https://hackernewsletter.com/)
- [W3C blog (har også nyhedsbrev)](https://www.w3.org/blog/)
- [JavaScript Weekly](https://javascriptweekly.com/)
- [Frontend Focus](https://frontendfoc.us)
- [Michells nyhedsbrev](https://nyhedsbrev.cronberg.dk/)
- [Version2](https://www.version2.dk/)
- [videnskab.dk](https://videnskab.dk/)
- [Node Weekly](https://nodeweekly.com/)

# Diverse programmer

- [AutoHotKey](https://www.autohotkey.com/)
  - [Diverse scripts](https://github.com/devcronberg/kursus/tree/master/autohotkey)
- [BareTail - god til log filer](https://www.baremetalsoft.com/baretail/)
- [Git for Windows](https://git-scm.com/download/win)


# Historie
- [IT Historie](http://ithistorie.cronberg.dk)
- [computerhistory.org](https://www.computerhistory.org/timeline/)
- [Dokumentar om opfindelsen af transitoreren](https://www.youtube.com/watch?v=U4XknGqr3Bo)
- [The mother of all demos - Douglas Engelbart (mus 32:00)](https://www.youtube.com/watch?v=yJDv-zdhzMY) ([Wikipedia](https://en.wikipedia.org/wiki/The_Mother_of_All_Demos))
- [Ikonisk billede af Margaret Hamilton/MIT/Nasa](https://www.nasa.gov/feature/margaret-hamilton-apollo-software-engineer-awarded-presidential-medal-of-freedom)
- [Ikonisk billede](https://en.wikipedia.org/wiki/Software_bug#/media/File:H96566k.jpg) af "en bug" fra en relæ computer (MARK II) i 1946. Bug fundet af [Grace Hopper] - en af pionerne bag programmeringssprog (herunder COBOL)
- Store danske videnskabsfolk (udsendelser fra DR tilgængelig til sep 2020)
  - [Tycho Brahe](https://www.dr.dk/tv/se/store-danske-videnskabsfolk-saeson-2/store-danske-videnskabsfolk/store-danske-videnskabsfolk-tycho-brahe)
  - [Niels Bohr](https://www.dr.dk/tv/se/store-danske-videnskabsfolk-saeson-2/store-danske-videnskabsfolk/store-danske-videnskabsfolk-niels-bohr)
  - [Ole Rømer](https://www.dr.dk/tv/se/store-danske-videnskabsfolk-saeson-2/store-danske-videnskabsfolk-saeson-2-2/store-danske-videnskabsfolk-ole-roemer)
- Diverse navne med links relateret til IT teknologi (primært udvikling)
  - [Joseph Marie Jacquard](https://en.wikipedia.org/wiki/Joseph_Marie_Jacquard)
  - [Herman Hollerith](https://en.wikipedia.org/wiki/Herman_Hollerith)
  - [Ada Lovelace](https://en.wikipedia.org/wiki/Ada_Lovelace)
  - [Charles Babbage](https://en.wikipedia.org/wiki/Charles_Babbage)
  - [George Boole](https://en.wikipedia.org/wiki/George_Boole)
  - [Allan Turing](https://en.wikipedia.org/wiki/Alan_Turing)
  - [Alonzo Church](https://en.wikipedia.org/wiki/Alonzo_Church)
  - [John von Neumann](https://en.wikipedia.org/wiki/John_von_Neumann)
  - [Claude Elwood Shannon](https://en.wikipedia.org/wiki/Claude_Shannon)
  - [John Bardeen](https://en.wikipedia.org/wiki/John_Bardeen)
  - [William Bradford Shockley Jr](https://en.wikipedia.org/wiki/William_Shockley)
  - [Walter Houser Brattain](https://en.wikipedia.org/wiki/Walter_Houser_Brattain)
  - [Jack St. Clair Kilby](https://en.wikipedia.org/wiki/Jack_Kilby)
  - [Douglas Engelbart](https://en.wikipedia.org/wiki/Douglas_Engelbart) 
  - [Grace Hopper](https://en.wikipedia.org/wiki/Grace_Hopper)
  - [Margaret Hamilton](https://www.nasa.gov/feature/margaret-hamilton-apollo-software-engineer-awarded-presidential-medal-of-freedom)
  - [Bill Gates](https://en.wikipedia.org/wiki/Bill_Gates)
  - [Paul Allen](https://en.wikipedia.org/wiki/Paul_Allen)
  - [Steve Wozniak](https://en.wikipedia.org/wiki/Steve_Wozniak)
  - [Steve Jobs](https://en.wikipedia.org/wiki/Steve_Jobs)
  - [Tim Berners-Lee](https://en.wikipedia.org/wiki/Tim_Berners-Lee)
  - [Henrik Frystyk Nielsen](https://en.wikipedia.org/wiki/Henrik_Frystyk_Nielsen)
  - [Håkon Wium Lie](https://en.wikipedia.org/wiki/H%C3%A5kon_Wium_Lie)
  - [Brendan Eich](https://en.wikipedia.org/wiki/Brendan_Eich)
  - [Ryan Dahl](https://en.wikipedia.org/wiki/Ryan_Dahl)

# Diverse
  - [Planetarium](https://planetarium.dk/)
  - [Danmarks Tekniske Museum](https://tekniskmuseum.dk/)
  - [SpaceX's Falcon Heavy rocket land all 3 boosters for the first time](https://www.youtube.com/watch?v=HVqWEoyiaBA)

# Michell

- Michell Cronberg
  - Instruktør, forfatter, konsulent
- [LinkedIn](https://goo.gl/iVjaqF)
- [Nyhedsbrev](https://nyhedsbrev.cronberg.dk/)
- [Mikrokonsulenterne](http://www.mikrokonsulenterne.dk)
- [T-Shirts](http://tshirt.cronberg.dk)

![](http://log.cronberg.dk/logimage?application=kursuslinks)
