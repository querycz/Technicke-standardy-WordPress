# Technické standardy WordPress 💻

- HTML5, CSS3/SASS, JavaScript/jQuery/ES6, PHP/MySQL.
- Gulp.js pro automatizaci vývoje.
- Node.js a NPM pro automatizaci vývoje a správu front-end komponent.
- Psaní CSS dle metodiky ITCSS pro udržitelnou a škálovatelnou strukturu stylopisu.
- Responsivní layout – podpora širokých rozlišení, standardních rozlišení, rozlišení mobilních zařízení – tabletů a mobilních telefonů metodou „mobile first“.
- Grafické prvky optimalizované pro zařízení s vysokým rozlišením displeje („Retina“).
- Podpora internetových prohlížečů:
	- Edge (jádro Edge),
	- Firefox (jádro Gecko, Windows/macOS),
	- Chrome/Opera 15+ (jádro Blink, Windows/macOS),
	- Safari (jádro WebKit, macOS).
- Uživatelská přístupnost a použitelnost:
	- Ctění standardů uživatelské přístupnosti (www.pravidla-pristupnosti.cz) 
- Redakční systém/CMS WordPress – aktuální stabilní revize + ověřené příslušné pluginy.
- SSL/HTTPS – v případě hostování na serverech Query, v opačném případě dle možností produkčního serveru (doporučeno minimálně použití self-signed certifikátu, typicky Let’s Encrypt.
- HTTP/2 – v případě hostování na serverech Query, v opačném případě dle možností produkčního serveru.
- Důraz na rychlé načítání:
	- Minifikace JavaScript skriptů a CSS souborů pro snížení datové náročnosti,
	- kombinace JavaScript skriptů,
	- kombinace CSS stylů do jednoho souboru nebo rozdělení CSS a načítání dle komponent (pouze při využití HTTP/2),
    - critical CSS,
    - minifikace generovaných HTML,
	- extra komprese grafických formátů (především PNG, JPG, SVG),
	- cachování (WordPress plugin „WP Super Cache“),
	- serverová g-zip komprese a Cache-Control (CSS, JS, HTML/PHP) v případě hostování na serverech Query, v opačném případě dle možností produkčního serveru,
	- využití CDN pro načítání standardních skriptů/knihoven (typicky jQuery),
	- omezení počtu pluginů, které zatěžují běh stránky.
- SEO
	- On-page faktory – validní, sémantický a čistý kód.
	- Off-page faktory
		- Indexace
			- Podpora indexace podstrčením stránek vyhledávači Google prostřednictvím sitemap.xml a Google Search Console.
			- Podpora indexace podstrčením stránek vyhledávači Seznam.cz.
- Analytika návštěvnosti – založení Google Analytics profilu, případně vložení vlastního kódu Objednatele.
