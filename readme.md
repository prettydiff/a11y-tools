Tool List
---

All tools are public Github repositories primary written in HTML and/or JavaScript

Repo                                                                                                                           |Type              |Purpose                 |Dependencies
-------------------------------------------------------------------------------------------------------------------------------|------------------|------------------------|------------
[GoogleChrome/accessibility-developer-tools-extension](https://github.com/GoogleChrome/accessibility-developer-tools-extension)|browser addon     |code audit              |Closure Compiler
[ainspector/ainspector.github.io](https://github.com/ainspector/ainspector.github.io)                                          |browser addon     |code audit              |-
[Document Outline Audit](https://github.com/edenspiekermann/outline-audit)                                                     |browser addon     |code audit              |-
[yargalot/grunt-accessibility](https://github.com/yargalot/grunt-accessibility)                                                |CLI               |code audit              |Node/Grunt
[nature/pa11y](https://github.com/nature/pa11y)                                                                                |CLI               |code audit              |Node/PhantonJS
[addyosmani/a11y](https://github.com/addyosmani/a11y)                                                                          |CLI               |code audit              |Node/PhantomJS
[dequelabs/axe-core](https://github.com/dequelabs/axe-core)                                                                    |in-page function  |code audit              |-
[GoogleChrome/accessibility-developer-tools](https://github.com/GoogleChrome/accessibility-developer-tools)                    |local Node service|code audit              |Node
[Grunt Tenon Client](https://github.com/egauci/grunt-tenon-client)                                                             |local Node service|code audit              |Node/Grunt
[Gulp Tenon Client](https://github.com/egauci/gulp-tenon-client)                                                               |local Node service|code audit              |Node/Gulp
[rackt/react-a11y](https://github.com/rackt/react-a11y)                                                                        |React Component   |code audit              |React
[squizlabs/HTML_CodeSniffer](https://github.com/squizlabs/HTML_CodeSniffer)                                                    |stand-alone page  |code audit              |-
[TENON](http://tenon.io/)                                                                                                      |stand-alone page  |code audit              |-
[haltersweb/Accessibility](https://github.com/haltersweb/Accessibility)                                                        |stand-alone page  |code library            |-
[prettydiff/colorContrast](https://github.com/prettydiff/colorContrast)                                                        |stand-alone page  |color contrast          |-
[jxnblk/colorable](https://github.com/jxnblk/colorable)                                                                        |stand-alone page  |color contrast          |-
[LeaVerou/contrast-ratio](https://github.com/LeaVerou/contrast-ratio)                                                          |stand-alone page  |color contrast          |-
[RAMP-PCAR/RAMP-PCAR](https://github.com/RAMP-PCAR/RAMP-PCAR)                                                                  |framework         |framework               |Node/Grunt
[CaptionBot](https://www.captionbot.ai/)                                                                                       |stand-alone page  |image caption generator |-
[a11yproject/a11yproject.com](https://github.com/a11yproject/a11yproject.com)                                                  |stand-alone page  |informational           |Ruby
[wesbos/keycodes](https://github.com/wesbos/keycodes)                                                                          |stand-alone page  |keyboard keycodes       |-
[W3C](http://w3c.github.io/uievents/tools/key-event-viewer.html)                                                               |stand-alone page  |keyboard keycodes       |-
[dylanb/dylanb.github.io](https://github.com/dylanb/dylanb.github.io)                                                          |stand-alone page  |reference ARIA          |-
[html5accessibility.com](http://html5accessibility.com/)                                                                       |stand-alone page  |reference browser       |-
[melmo/melmo.github.io](https://github.com/melmo/melmo.github.io)                                                              |stand-alone page  |reference landmarks     |-
[zone/zwag](https://github.com/zone/zwag)                                                                                      |stand-alone page  |reference WCAG          |Node
[nature/pa11y-dashboard](https://github.com/nature/pa11y-dashboard)                                                            |stand-alone page  |reporting               |Node/PhantomJS
[Khan/tota11y](https://github.com/Khan/tota11y)                                                                                |in-page function  |semantic analysis       |JQuery
[prettydiff/semanticText](https://github.com/prettydiff/semanticText)                                                          |in-page function  |semantic analysis       |-
[a11y.js](https://github.com/IBM-Watson/a11y.js)                                                                               |in-page function  |utility, ARIA           |-
[ally.js](http://allyjs.io/)                                                                                                   |in-page function  |utility, focus          |-
[A11y Dialog](edenspiekermann/a11y-dialog)                                                                                     |in-page function  |utility, modal generator|-
[A11y Toggle](edenspiekermann/a11y-toggle)                                                                                     |in-page function  |utility, toggle         |-
[howlowck/Akbar](https://github.com/howlowck/Akbar)                                                                            |bookmarklet       |vision simulation       |-
[adobe-accessibility/Accessible-Mega-Menu](https://github.com/adobe-accessibility/Accessible-Mega-Menu)                        |web component     |web component           |JQuery
[A11yance/a11y-core](https://github.com/A11yance/a11y-core)                                                                    |local Node service|?                       |Node/Grunt



My purpose in making such a list is that I want to be aware of what things are being evaluated so that I can get an idea of what things aren't being evaluated.  Accessibility is hard, and since many commercial sites don't produce high quality HTML accessibility is much harder than it should be.  Making accessibility easier to implement and understand is absolutely important.  Good tools help with this.

Sometimes the biggest problem with accessibility is that we know what to check for (most of the time), but we don't always know what grading aspects we are missing.  Examples include color contrast problems over gradient backgrounds and improper use of the `title` attribute.  Sometimes we also don't realize how the dynamic interactions we introduce with JavaScript alienate segments of our audience.

Accessibility advocates typically suggest having at least 3 accessibility tools frequently used, because they each are better in different particular areas.  An awareness of the tools available benefits everybody whether or not you intend to make accessibility tools.  Please submit pull requests with additional tools.
