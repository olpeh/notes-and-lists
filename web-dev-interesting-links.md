# A List of Links to Interesting Websites and Blog Posts Related to Web Development

Just a long list of links to interesting stuff that I have stumbled upon. The links are in no particular order and future links will be added to the bottom of each section. Trying to keep these in some kind of categories.

// @TODO: Create a script that saves all these websites as HTML and commits those to this repo
// @TODO: Add short description after each URL

## Web Performance

### Tools or Documentation

* https://developers.google.com/speed/pagespeed/insights/
  * Analyze your web page speed as Google sees it
* https://www.webpagetest.org
  * Free web page performance test
* https://developers.google.com/web/tools/lighthouse/
  * Test your application performance, especially good for PWAs
* https://www.giftofspeed.com/
  * Website speed test, nicely looking but not as many features as webpagetest.org
* https://whatdoesmysitecost.com/
  * How much data is spent by your site
* https://developers.google.com/web/fundamentals/performance/critical-rendering-path/
  * Nice explanations on critical rendering path
* https://developers.google.com/web/tools/chrome-user-experience-report/
  * The Chrome User Experience Report provides user experience metrics for how real-world Chrome users experience popular destinations on the web.
* http://requestmap.webperf.tools/
  * RequestMap, Visually map the request sent by a site

### Blog Posts and Tutorials

* https://gist.github.com/kkas/919fcf835a58ef610495
* http://duncanleung.com/the-critical-rendering-path-optimizing-script-loading/
* https://medium.com/@luisvieira_gmr/understanding-the-critical-rendering-path-rendering-pages-in-1-second-735c6e45b47a
* https://varvy.com/pagespeed/critical-render-path.html
* https://www.sitepoint.com/optimizing-critical-rendering-path/
* http://www.apmdigest.com/website-response-time-1
* https://css-tricks.com/prefetching-preloading-prebrowsing/
* https://www.igvita.com/2015/08/17/eliminating-roundtrips-with-preconnect/
* https://digiday.com/media/google-reveals-sites-failing-ads-including-forbes-la-times/
* https://webmasters.googleblog.com/2018/01/using-page-speed-in-mobile-search.html
* https://font-display.glitch.me/
  * With the new font-display attribute, you can control the length of each of the periods in downloading and rendering a font, and what happens when one of them fails.
* http://trentwalton.com/notes/2018/01/04/third-party-scripts.html
  * "My latest realization is that delivering a performant, accessible, responsive, scalable website isn’t enough: I also need to consider the impact of third-party scripts."
* https://timkadlec.com/2014/01/fast-enough/
* http://trentwalton.com/notes/2018/02/05/tag-manager-chat-with-vector-media-group.html
* http://trentwalton.com/notes/2018/01/23/third-party-script-prevalence-on-alexa-top-50.html
* https://blog.optimizely.com/2016/07/13/how-does-page-load-time-impact-engagement/
* http://trentwalton.com/notes/2018/01/08/optimizely-blog-page-load-time-engagement.html
* http://trentwalton.com/notes/2018/01/18/itemizing-third-party-scripts.html
* https://clearleft.com/posts/analysing-analytics
* https://www.w3.org/TR/longtasks/
* http://httparchive.org/trends.php
* https://medium.com/@paul_irish/requestanimationframe-scheduling-for-nerds-9c57f7438ef4
* https://stackoverflow.com/questions/41740082/scroll-events-requestanimationframe-vs-requestidlecallback-vs-passive-event-lis
* https://jakearchibald.com/2016/caching-best-practices/
* https://wildlyinaccurate.com/introducing-a-faster-bbc-news-front-page/
* https://engineering.klarna.com/how-removing-caching-improved-mobile-performance-by-25-52a17cc339a2
* http://trentwalton.com/notes/2018/01/05/andy-davis-and-simon-hearne-on-third-party-components.html
  * Third party: managed by someone else
  * Amount of third party scripts is increasing: 3rd, 4th and 5th-parties etc.
  * Generally sites with tag managers have worse visual performance
  * Find what's on the site: Ghostery, Webpagetest, RequestMap
  * Monitor your third party resources, both syntethic and RUM

## Progressive Web Applications

### Tools or Documentation

* https://jakearchibald.com/2014/offline-cookbook/
* https://developers.google.com/web/progressive-web-apps/checklist
* https://developers.google.com/web/fundamentals/primers/service-workers/
* https://github.com/GoogleChromeLabs/sw-precache
* https://github.com/GoogleChromeLabs/sw-toolbox

### Blog Posts and Tutorials

* https://blog.ionicframework.com/what-is-a-progressive-web-app/
* https://mxb.at/blog/how-to-turn-your-website-into-a-pwa/
* https://technology.condenast.com/story/not-progressive-alien-web-apps
* https://medium.com/@Huxpro/how-does-sw-precache-works-2d99c3d3c725
* https://blog.twitter.com/engineering/en_us/topics/open-source/2017/how-we-built-twitter-lite.html
* https://medium.com/@paularmstrong/twitter-lite-and-high-performance-react-progressive-web-apps-at-scale-d28a00e780a3
* https://digiday.com/media/new-mobile-site-forbes-boosted-impressions-per-session-10-percent/
* https://eng.uber.com/m-uber/
* https://www.thinkwithgoogle.com/intl/en-gb/consumer-insights/trivago-embrace-progressive-web-apps-as-the-future-of-mobile/
* https://medium.com/dev-channel/a-pinterest-progressive-web-app-performance-case-study-3bd6ed2e6154
* https://dockyard.com/blog/2017/10/24/software-rot-and-the-case-for-the-pwa-rewrite
* https://m.phillydevshop.com/apples-refusal-to-support-progressive-web-apps-is-a-serious-detriment-to-future-of-the-web-e81b2be29676
* https://twitter.com/rmondello/status/956256845311590400
* https://medium.com/@firt/pwas-are-coming-to-ios-11-3-cupertino-we-have-a-problem-2ff49fd7d6ea
* https://medium.com/javascript-scene/native-apps-are-doomed-ac397148a2c0
* https://code.luasoftware.com/tutorials/pwa/basic-progressive-web-app-pwa-setup/
* https://stackoverflow.com/questions/39109789/what-limitations-apply-to-opaque-responses/39109790#39109790
* https://www.html5rocks.com/en/tutorials/offline/whats-offline/
* https://medium.com/arjs/why-web-apps-are-the-future-of-augmented-reality-c503e796a0c5
* https://www.kollegorna.se/en/2017/06/service-worker-gotchas/
* https://blog.hackages.io/migrating-a-service-worker-from-an-old-domain-to-your-new-domain-69236418051c
* https://www.loxodrome.io/post/service-worker-registration/
* https://www.loxodrome.io/post/break-service-workers/
* https://www.theverge.com/2018/2/7/16987842/microsoft-progressive-web-apps-pwa-edge-windows-10
  * Edge on Windows 10 will have desktop PWA support
  * Also available on Chrome Canary under chrome://flags/#enable-desktop-pwas
* https://webperf.ninja/2017/twitter-pwa/
  * Twitter Lite isn't as good as the app, and that's okay
  * Published April 07, 2017, so most of the issues mentioned are already fixed

## React, Preact, VueJS, CycleJS and Others

* https://www.sitepoint.com/switching-from-react-to-cycle-js/
* http://pixeljets.com/blog/why-we-chose-vuejs-over-react/
* https://medium.com/@saurabhnanda/benchmarks-fp-languages-libraries-for-front-end-development-a11af0542f7e

## Web Development in General

* http://trentwalton.com/2014/03/10/device-agnostic/
* https://medium.com/@mikeal/ive-seen-the-future-it-s-full-of-html-2577246f2210
* https://hackernoon.com/why-im-moving-on-to-web-components-and-not-looking-back-aa8028c99c83
* https://philipwalton.com/articles/what-no-one-told-you-about-z-index/
* http://alistapart.com/article/inline-validation-in-web-forms
* https://medium.com/@treshugart/%C3%A5server-side-rendering-web-components-e5df705f3f48
* https://www.smashingmagazine.com/2017/04/start-using-css-custom-properties/
* https://medium.com/@matteozago/why-the-web-3-0-matters-and-you-should-know-about-it-a5851d63c949
  * The future of the web (Web 3.0) relies on decentralized solutions
* https://m.signalvnoise.com/stimulus-1-0-a-modest-javascript-framework-for-the-html-you-already-have-f04307009130
  * Stimulus 1.0: A modest JavaScript framework for the HTML you already have

## Software Development in General

* http://www.dwmkerr.com/the-death-of-microservice-madness-in-2018/
* https://redditblog.com/2017/06/30/why-we-chose-typescript/
* https://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to
* http://blog.thomasbelin.fr/p/you-dont-need-this/?utm_content=buffer5a045&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer
* https://dev.to/bitario/surviving-in-open-source
* https://staltz.com/why-we-need-callbags.html
* https://medium.com/@benlesh/learning-observable-by-building-observable-d5da57405d87
* https://dev.to/samjarman/giving-and-receiving-great-code-reviews
* https://mtlynch.io/human-code-reviews-1/
* https://gist.github.com/staltz/868e7e9bc2a7b8c1f754
* https://codeburst.io/ui-testing-with-jest-and-puppeteer-an-introduction-f0ea99b56f3a
* https://css-tricks.com/accessible-web-apps-react-typescript-allyjs/

## Interesting But Difficult to Categorize

* https://github.com/WICG/webpackage
* http://bradfrost.com/blog/post/facebook-you-needy-sonofabitch/
* https://hackernoon.com/tech-companies-these-are-the-perks-and-benefits-i-want-5e9788c30958
* https://dev.to/samjarman/how-to-build-an-online-presence-as-a-junior-developer
* https://www.lucify.com/inside-einsteins-head/
* https://staltz.com/the-web-began-dying-in-2014-heres-how.html

## Videos

* https://www.youtube.com/watch?v=CPP9ew4Co0M
* https://www.youtube.com/watch?v=N33lYfsAsoU
