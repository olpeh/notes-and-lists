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
* https://developers.google.com/web/fundamentals/performance/rail
  * RAIL: Response, Animation, Idle, Load
  * Performance guidelines
* https://www-origin.sitespeed.io/
  * Sitespeed.io is a set of Open Source tools that makes it easy to monitor and measure the performance of your website.
* https://github.com/ausi/respimagelint
  * Bookmarklet for linting images on a webpage
* https://www.thinkwithgoogle.com/feature/mobile/
  * Winning on Mobile – Compare website speeds based on Chrome User Experience Report (CrUX) data
* https://wpostats.com/
  * Case studies and experiments demonstrating the impact of web performance optimization (WPO) on user experience and business metrics
* https://developers.google.com/web/fundamentals/performance/speed-tools/
  * An infographic explaining Google's web performance tools and how to think about them.
* https://testmysite.withgoogle.com/
  * Test your site's mobile speed.
* https://speedcurve.com/
  * See how real people experience the speed of your website.
  * Uses WebPageTest under the hood
* https://calibreapp.com/
  * World-class web performance monitoring for teams who want to be the best.
  * Seems pretty similar to SpeedCurve
  * Uses LightHouse under the hood

### Blog Posts and Tutorials

* https://gist.github.com/kkas/919fcf835a58ef610495
  * Nice collection and recap of Critical Rendering Path related optimizations
* http://duncanleung.com/the-critical-rendering-path-optimizing-script-loading/
  * Optimizing the Critical Rendering Path involves optimizing the dependencies between HTML, CSS, and JavaScript and reducing the time required to process and turn them into rendered pixels.
* https://medium.com/@luisvieira_gmr/understanding-the-critical-rendering-path-rendering-pages-in-1-second-735c6e45b47a
  * Page load time is not a good metric for performance
  * How does the browser rendering engine work?
  * The initial file size of your DOM tree will have a performance cost.
  * Tips for optimizations
* https://varvy.com/pagespeed/critical-render-path.html
  * Critical Rendering Path explained
  * A real world example of optimizing the critical rendering path
* https://www.sitepoint.com/optimizing-critical-rendering-path/
  * How can you accomplish ambitious goal of 1s render time without cutting off features or dramatically disfiguring your site?
  * Critical Rendering Path explained in detail
  * Three Steps to Optimizing the Critical Rendering Path
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
* http://www.deanhume.com/Home/BlogPost/measuring-web-page-performance-with-selenium-2-and-the-web-timings-api/56
  * Measuring Web Page Performance with Selenium 2 and the Web Timings API
  * Selenium webdriver can be used to execute "return window.performance.timing"
* https://webperf.ninja/2016/getting-reliable-visual-metrics/
  * Visual metrics such as Speed Index, render start and visual complete are the best proxies we have for user experience. Unfortunately two of these are totally thrown by rotating carousels, popups, cookie banners and adverts.
* https://webperf.ninja/2016/prioritising-sitespeed-recommendations/
  * The vast majority of the improvements are best practises and relatively easy to observe.
    There’s little value in telling a client about the best practices they’ve already implemented.
  * In my reports I now suggest that site speed optimisations can be ranked by two critical factors:
    * What impact will this change have on the users
    * How hard will the change be to implement
* http://www.webperformancetoday.com/2011/07/14/fourth-party-calls-third-party-content/
  * Fourth-party calls: What you don’t know can hurt your site… and your visitors
* https://webperf.ninja/2017/analytics-lie/
  * You can't rely on your web analytics for performance data and it's understating bounce rate and traffic numbers from old devices.
  * Phantom bounces - user cancels the navigation
* https://webperf.ninja/2016/three-takeaways-from-velocity/
  * Three WebPerf Takeaways from Velocity Europe
    * Performance KPIs are broken
    * Team success = business success
    * We are not using great Web features
* http://nicj.net/an-audit-of-boomerangs-performance/
  * Thorough audit of Boomerang’s (RUM analytics script) performance
* https://developers.google.com/web/fundamentals/performance/why-performance-matters/
  * Performance is about improving conversions
  * Performance is about the user experience
  * Performance is about people
* https://www.doubleclickbygoogle.com/articles/mobile-speed-matters/
  * Over half of all mobile site visits are abandoned if the page doesn’t load within 3 seconds
  * 3 out of 4 mobile sites take longer than 10 seconds to load and the average time to load is 19 seconds
* https://infrequently.org/2017/10/can-you-afford-it-real-world-web-performance-budgets/
  * Can You Afford It?: Real-world Web Performance Budgets
  * Majority of the users are on a slow connection
  * Baseline device is surprisingly low-end, and will probably not improve a lot
  * Calculations for affordability
    * First load in under 5s and second load in under 2s on 3G
    * Leads to 130-170KB as the budget

## Progressive Web Applications

### Tools or Documentation

* https://jakearchibald.com/2014/offline-cookbook/
  * Caching and offline done right
* https://developers.google.com/web/progressive-web-apps/checklist
* https://developers.google.com/web/fundamentals/primers/service-workers/
* https://github.com/GoogleChromeLabs/sw-precache
* https://github.com/GoogleChromeLabs/sw-toolbox
* https://jakearchibald.github.io/isserviceworkerready/
  * Is service worker ready?

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
* https://medium.com/@addyosmani/a-tinder-progressive-web-app-performance-case-study-78919d98ece0
  * More user engagement achieved with a PWA vs. native apps
  * Route-level code-splitting etc.
  * After introducing route-based code-splitting their main bundle sizes went down from 166KB to 101KB and DCL improved from 5.46s to 4.69s
  * Many different methods for optimizing performance
* https://medium.com/dev-channel/treebo-a-react-and-preact-progressive-web-app-performance-case-study-5e4f450d5299
  * A React And Preact Progressive Web App Performance Case Study: Treebo
  * HTML Streaming
  * Caching static assets like their CSS and JavaScript bundles means pages load up (almost) instantly on repeat visits as they load from the disk cache rather than having to go back out to the network each time. Diligently defined caching headers can have this same effect with respect to disk cache hit-rates, but it’s Service Worker that gives us offline support.

## React, Preact, VueJS, CycleJS and Others

* https://www.sitepoint.com/switching-from-react-to-cycle-js/
  * Introduction to Cycle.js and a story about switching from React to Cycle.js
* http://pixeljets.com/blog/why-we-chose-vuejs-over-react/
  * Story about choosing VueJS over React

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
* https://www.smashingmagazine.com/2018/02/jquery-vue-javascript/
  * Replacing jQuery with Vue makes your code simpler
  * No build step needed

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
  * A collection of specifications aimed at packaging websites
* http://bradfrost.com/blog/post/facebook-you-needy-sonofabitch/
  * Facebook, You Needy Sonofabitch
* https://hackernoon.com/tech-companies-these-are-the-perks-and-benefits-i-want-5e9788c30958
  * "I don’t care about video games, NERF guns, or kegs in the kitchen."
* https://dev.to/samjarman/how-to-build-an-online-presence-as-a-junior-developer
  * "As a developer in 2017, it’s important to have some form of online presence."
* https://www.lucify.com/inside-einsteins-head/
  * An explorable explanation of relativistic spacetime, inspired by Albert Einstein's thought experiments.
* https://staltz.com/the-web-began-dying-in-2014-heres-how.html
  * "It looks like nothing changed since 2014, but GOOG and FB now have direct influence over 70%+ of internet traffic."

## Videos

* https://www.youtube.com/watch?v=CPP9ew4Co0M
  * Alexander Pope: ServiceWorkers Outbreak: index-sw-9a4c43b4b47781ca619eaaf5ac1db.js | JSConf EU 2017
  * Good tips about avoiding pitfalls in service worker registration
* https://www.youtube.com/watch?v=N33lYfsAsoU
  * Umar Hansa / Optimise your Web Development Workflow
* https://vimeo.com/254834890
  * SmashingConf London — Ilya Grigorik on ‘How’s the UX on the Web, Really?’
  * If you can't measure it, you can't improve it
* https://vimeo.com/254728119
  * SmashingConf London — Patrick Meenan on ‘How Fast Is It?’
  * We have more metrics than what we know what to do with
  * Pick metrics that will improve the user experience
  * Page load is a horrible metric
