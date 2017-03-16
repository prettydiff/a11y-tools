Tool List
---

All tools are public Github repositories primary written in HTML and/or JavaScript

Repo                                                                                                                                 |Purpose                 |Type              |Dependencies
-------------------------------------------------------------------------------------------------------------------------------------|------------------------|------------------|------------
[ainspector/ainspector.github.io](https://github.com/ainspector/ainspector.github.io)                                                |code audit              |browser addon     |-
[Document Outline Audit](https://github.com/edenspiekermann/outline-audit)                                                           |code audit              |browser addon     |-
[dequelabs/axe-core](https://github.com/dequelabs/axe-core)                                                                          |code audit              |in-page function  |-
[GoogleChrome/accessibility-developer-tools](https://github.com/GoogleChrome/accessibility-developer-tools)                          |code audit              |local Node service|Node
↳ [Khan/tota11y](https://github.com/Khan/tota11y)                                                                                    |semantic analysis       |in-page function  |JQuery
↳ [addyosmani/a11y](https://github.com/addyosmani/a11y)                                                                              |code audit              |CLI               |Node/PhantomJS
↳ [GoogleChrome/accessibility-developer-tools-extension](https://github.com/GoogleChrome/accessibility-developer-tools-extension)    |code audit              |browser addon     |Closure Compiler
[rackt/react-a11y](https://github.com/reactjs/react-a11y)                                                                            |code audit              |React Component   |React
[squizlabs/HTML_CodeSniffer](https://github.com/squizlabs/HTML_CodeSniffer)                                                          |code audit              |stand-alone page  |-
↳ [yargalot/grunt-accessibility](https://github.com/yargalot/grunt-accessibility)                                                    |code audit              |CLI               |Node/Grunt
↳ [nature/pa11y](https://github.com/springernature/pa11y)                                                                            |code audit              |CLI               |Node/PhantonJS
↳ [nature/pa11y-dashboard](https://github.com/springernature/pa11y-dashboard)                                                        |reporting               |stand-alone page  |Node/PhantomJS
[TENON](http://tenon.io/)                                                                                                            |code audit              |stand-alone page  |-
[A11y.css](https://github.com/ffoodd/a11y.css)                                                                                       |utility                 |bookmarklet       |-
[Visual ARIA, bookmarklet for seeing ARIA](https://github.com/accdc/csun-2016)                                                       |utility                 |bookmarklet       |-
[prettydiff/colorContrast](https://github.com/prettydiff/colorContrast)                                                              |color contrast          |color contrast    |-
[LeaVerou/contrast-ratio](https://github.com/LeaVerou/contrast-ratio)                                                                |color contrast          |color contrast    |-
[jxnblk/colorable](https://github.com/jxnblk/colorable)                                                                              |color contrast          |color contrast    |-
[howlowck/Akbar](https://github.com/howlowck/Akbar)                                                                                  |vision simulation       |bookmarklet       |-
[prettydiff/semanticText](https://github.com/prettydiff/semanticText)                                                                |semantic analysis       |in-page function  |-
[RAMP-PCAR/RAMP-PCAR](https://github.com/RAMP-PCAR/RAMP-PCAR)                                                                        |framework               |framework         |Node/Grunt
[CaptionBot](https://www.captionbot.ai/)                                                                                             |image caption generator |web service       |-
[wesbos/keycodes](https://github.com/wesbos/keycodes)                                                                                |keyboard keycodes       |stand-alone page  |-
[W3C](http://w3c.github.io/uievents/tools/key-event-viewer.html)                                                                     |keyboard keycodes       |stand-alone page  |-
[a11yproject/a11yproject.com](https://github.com/a11yproject/a11yproject.com)                                                        |informational           |stand-alone page  |Ruby
[Accessibility Tree Training Guide, how ARIA works](http://whatsock.com/training)                                                    |reference browser       |stand-alone page  |-
[melmo/melmo.github.io](https://github.com/melmo/melmo.github.io)                                                                    |reference landmarks     |stand-alone page  |-
[dylanb/dylanb.github.io](https://github.com/dylanb/dylanb.github.io)                                                                |reference ARIA          |stand-alone page  |-
[html5accessibility.com](http://html5accessibility.com/)                                                                             |reference browser       |stand-alone page  |-
[zone/zwag](https://github.com/zone/zwag)                                                                                            |reference WCAG          |stand-alone page  |Node
[a11y.js](https://github.com/IBM-Watson/a11y.js)                                                                                     |utility, ARIA           |in-page function  |-
[ally.js](http://allyjs.io/)                                                                                                         |utility, focus          |in-page function  |-
[A11yance/a11y-core](https://github.com/A11yance/a11y-core)                                                                          |?                       |local Node service|Node/Grunt
[haltersweb/Accessibility](https://github.com/haltersweb/Accessibility)                                                              |code library            |code library      |-
[jQuery plugins for simple elements](https://a11y.nicolas-hoffmann.net/)                                                             |utility, ARIA           |in-page function  |JQuery
[jQuery powered accessible widget archive, using ARIA](https://github.com/accdc/tsg)                                                 |utility, ARIA           |in-page function  |JQuery
↳ [jQuery ARIA menubar utility](https://github.com/accdc/aria-menubar)                                                               |utility, ARIA           |in-page function  |jQuery
↳ [MooTools powered accessible widget archive, using ARIA](https://github.com/accdc/tsg-mootools)                                    |utility, ARIA           |in-page function  |MooTools
↳ [Dojo powered accessible widget archive, using ARIA](https://github.com/accdc/tsg-dojo)                                            |utility, ARIA           |in-page function  |Dojo
[A11y Dialog](https://github.com/edenspiekermann/a11y-dialog)                                                                        |utility, modal generator|in-page function  |-
[A11y Toggle](https://github.com/edenspiekermann/a11y-toggle)                                                                        |utility, toggle         |in-page function  |-
[adobe-accessibility/Accessible-Mega-Menu](https://github.com/adobe-accessibility/Accessible-Mega-Menu)                              |web component           |web component     |JQuery



My purpose in making such a list is that I want to be aware of what things are being evaluated so that I can get an idea of what things aren't being evaluated.  Accessibility is hard, and since many commercial sites don't produce high quality HTML accessibility is much harder than it should be.  Making accessibility easier to implement and understand is absolutely important.  Good tools help with this.

Sometimes the biggest problem with accessibility is that we know what to check for (most of the time), but we don't always know what grading aspects we are missing.  Examples include color contrast problems over gradient backgrounds and improper use of the `title` attribute.  Sometimes we also don't realize how the dynamic interactions we introduce with JavaScript alienate segments of our audience.

Accessibility advocates typically suggest having at least 3 accessibility tools frequently used, because they each are better in different particular areas.  An awareness of the tools available benefits everybody whether or not you intend to make accessibility tools.  Please submit pull requests with additional tools.
