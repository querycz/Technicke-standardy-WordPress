# 💻 Technické standardy WordPress

## Dev-stack
- HTML5, CSS3, JavaScript/jQuery/ES6, PHP/MySQL.
- Webpack, NPM a Node.js pro automatizaci vývoje a správu front-end komponent.
- CSS framework Tailwind CSS.
- Responsivní layout – podpora širokých rozlišení, standardních rozlišení, rozlišení mobilních zařízení – tabletů a mobilních telefonů metodou „mobile first“.
- Grafické prvky optimalizované pro zařízení s vysokým rozlišením displeje („Retina“).
- Podpora internetových prohlížečů:
	- Edge (jádro Edge),
	- Firefox (jádro Gecko, Windows/macOS),
	- Chrome/Opera 15+ (jádro Blink, Windows/macOS),
	- Safari (jádro WebKit, macOS).
- Redakční systém/CMS WordPress – aktuální stabilní revize + příslušné ověřené pluginy.

## Rychlost
- Minifikace JavaScript skriptů a CSS souborů pro snížení datové náročnosti,
- rozdělení JavaScript skriptů dle stránek a/nebo komponent a načítání dle stránek/komponent,
- utilitární globální CSS styl frameworku Tailwind CSS,
- minifikace generovaného HTML,
- extra komprese grafických formátů (především PNG, JPG, SVG),
- cachování (WordPress plugin „WP Super Cache“),
- serverová g-zip komprese a Cache-Control (CSS, JS, HTML/PHP) v případě hostování na serverech Query, v opačném případě dle možností produkčního prostředí,
- důraz na minimální počet pluginů 3. stran, které zatěžují běh stránky.

## Server
- SSL/HTTPS – v případě hostování na serverech Query, v opačném případě dle možností produkčního prostředí (doporučeno minimálně použití self-signed certifikátu, typicky Let’s Encrypt.
- HTTP/2 – v případě hostování na serverech Query, v opačném případě dle možností produkčního prostředí.

## Přístupnost a použitelnost
- Ctění standardů uživatelské přístupnosti (www.pravidla-pristupnosti.cz).

## SEO
- On-page faktory
	- Sémantický a čistý kód.
	- Rychlost.
- Off-page faktory
	- Indexace
		- Podpora indexace podstrčením stránek vyhledávači Google prostřednictvím sitemap.xml a Google Search Console.
		- Podpora indexace podstrčením stránek vyhledávači Seznam.cz.

## Analytika návštěvnosti 
- Založení Google Analytics profilu, případně vložení vlastního kódu Objednatele.
- Propojení Google Analytics a Google Search Console.
- Volitelně implementace Plausible analytiky
