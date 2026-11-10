# Catalog review inventory

**61 proposed changes · 30 uncertain · 54 unresolved keeps**

226 entries researched. 81 saved reviews for recurring runs.

Research recommendations from the initial Opus review. The full set has not passed prior-discussion or patch validation. Proposed diffs are previews, not approved patches. Nothing was applied or submitted.

Catalog: `7be0a43cdeeb99601cac580d4f1a81ecf9bdf88c` · README SHA-256: `81f1030dbf40e5c0ec6fdffc47373ba909f72fa5223b8333d990d703dfd2e765`

## Proposed changes

<h3>Panelbear — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -27,7 +27,7 @@
 ## General analytics
 **[`^        back to top        ^`](#)**
 * [UXWizz](https://www.uxwizz.com/) - Self-hosted web analytics with heatmaps, session-recordings, A/B tests and more. `©` `Self-Hosted` `PHP`
-* [Panelbear](https://panelbear.com/) - free real-time website analytics. Supports custom event tracking, email digests, and site speed metrics. `©` `SaaS`
+* [Cronitor Analytics](https://cronitor.io/real-user-monitoring) - Cookie-free website analytics and real user monitoring (formerly Panelbear). Tracks traffic, custom conversion events, page-load performance and JavaScript errors, with alerting. `©` `SaaS`
 * [PostHog](https://posthog.com) - Open-source product analytics to track users, events, funnels and trends. Alternative to Mixpanel/Amplitude/Heap. Also includes session recording (alternative to HotJar) and feature flag/experimentation tools (alternative to Optimizely).([Source Code](https://github.com/posthog/posthog)) `MIT` `Python`
 * [stratif.io](https://stratif.io) - Open-source, self-hosted, warehouse-native product analytics. Runs funnels, retention, and path analysis directly on DuckDB, Postgres, Snowflake, or ClickHouse — no ingestion, no SDK. ([Source Code](https://github.com/stratif-io/stratif.io)) `Apache-2.0` `Python/TypeScript`
 * [GrowthBook](https://growthbook.io) - Open-source A/B testing and feature flagging that uses your existing data sources.([Source Code](https://github.com/growthbook/growthbook)) `MIT` `Typescript`
```

<details>
<summary>Evidence and limitations</summary>

<p>panelbear.com redirects to Cronitor, and the destination page states &#x27;Panelbear is now Cronitor Analytics&#x27;. This is an official rebrand into Cronitor&#x27;s analytics/RUM product. Custom event tracking and site-speed metrics are still documented. I could not verify the &#x27;free&#x27; and &#x27;email digests&#x27; claims on the current page.</p>

<p>https://cronitor.io/real-user-monitoring — https://panelbear.com/ redirects to https://cronitor.io/real-user-monitoring?ref=panelbear, whose canonical is https://cronitor.io/real-user-monitoring. The page says &#x27;Panelbear is now Cronitor Analytics&#x27; and &#x27;Traffic, performance, and errors in a single tool. Cookie-free&#x27;. It shows conversion tracking via cronitor(&#x27;track&#x27;,&#x27;Checkout&#x27;), LCP/CLS and page-load timing percentiles, JavaScript error tracking and alert rules.</p>

<p>Caveats: The Cronitor pricing page did not clearly confirm a free analytics tier, so the proposed wording drops &#x27;free&#x27;. Email digests were not mentioned, so they are dropped too.; Category tags (©, SaaS) remain appropriate.</p>

<p>Independent source check: Official Panelbear redirect and referral-specific destination banner confirm the Cronitor Analytics rebrand. Current product page supports the proposed traffic, conversion, performance and error-monitoring description. Dropping free/email-digest claims is not proof those capabilities disappeared; narrow outreach to the verified rebrand.</p>

<p>https://panelbear.com/ — Redirects to https://cronitor.io/real-user-monitoring?ref=panelbear; banner identifies the rebrand.</p>

<p>https://cronitor.io/real-user-monitoring — Official page documents custom conversion events, browser performance and JavaScript errors.</p>

</details>

<h3>Clicky — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -42,7 +42,7 @@
 * [Screpy](https://screpy.com) - Screpy is a web analyzer and monitoring tool. Its powered by Google Lighthouse. `©` `SaaS`
 * [Clicktale](https://www.clicktale.com) - record and watch exactly how a visitor used your website. `©` `SaaS`
 * [GoSquared](https://www.gosquared.com/) - analytics with visitor tagging to help you dig deeper into one user’s visit. `©` `SaaS`
-* [Clicky](http://clicky.com/) - track visits and conversions, you can also track your video and audio analytics. `©` `SaaS`
+* [Clicky](https://clicky.com/) - track visits and conversions, you can also track your video and audio analytics. `©` `SaaS`
 * [Woopra](https://www.woopra.com/) - track where your users are coming from. `©` `SaaS`
 * [Mint](https://haveamint.com/) - self-hosted analytics solution (no longer on sale).  `©` `SaaS`
 * [Going Up](https://www.goingup.com/) - manage SEO analytics and web app analytics with one tool. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>http://clicky.com/ redirects to https://clicky.com/, which is the canonical URL. The description is still accurate: Clicky offers real-time visitor tracking, goals/conversions and &#x27;Video &amp; audio analytics&#x27;. Only the URL scheme needs updating.</p>

<p>https://clicky.com/ — The http URL redirects here, and the canonical link is https://clicky.com/. The page lists &#x27;Real-time visitor logs&#x27;, &#x27;🎞️ Video &amp; audio analytics: Track interactions with HTML5 media elements… YouTube and Vimeo&#x27;, heatmaps and uptime alerts. Footer: © 2026 Roxr Software Ltd.</p>

<p>Caveats: Conversion/goal tracking is not prominent on the homepage, but nothing contradicts it.</p>

<p>Independent source check: HTTP entry resolves to the current HTTPS homepage. Real-time visitor and video/audio tracking remain documented. Valid URL hygiene, but not a compelling semantic-maintenance email example.</p>

<p>http://clicky.com/ — Resolves to HTTPS Clicky homepage.</p>

<p>https://clicky.com/ — Official product page includes real-time visitor logs and video/audio analytics.</p>

</details>

<h3>FoxMetrics — remove</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Search results show the official foxmetrics.com homepage titled &#x27;FoxMetrics has been retired&#x27;. The snippet says the product &#x27;has been retired and is no longer sold or supported&#x27; and is not accepting new accounts. Rawsoft&#x27;s TagPipes Lens is mentioned only as a separate product, explicitly not a new version of FoxMetrics, so it does not qualify as a successor for replacement.</p>

<p>https://foxmetrics.com/ — Search-result title &#x27;FoxMetrics has been retired&#x27;. The snippet says the platform is retired, no longer sold or supported, and not accepting new accounts. Direct fetch failed (proxy 502).</p>

<p>Blocking questions: The official retirement notice could not be loaded directly in this session. A maintainer should open foxmetrics.com to confirm before removing.</p>

<p>Caveats: The notice was read only via search-index excerpts.</p>

<p>Independent source check: Official homepage directly confirms retirement and that sales, support and new signups have ended. It describes TagPipes Lens as a separate product rather than an automatic migration or new FoxMetrics version. Removal remains curator judgment, but retirement is a strong verified issue with the current active-product description. This audit resolves the model’s direct-fetch uncertainty; raw assessment stays unchanged.</p>

<p>https://foxmetrics.com/ — Official retirement page read directly through web tool; separate-product qualification for TagPipes Lens verified.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Google Analytics — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -38,7 +38,7 @@
 * [Opentracker](http://www.opentracker.net/) - real time reporting, geo-location user tracking. `©` `SaaS`
 * [FoxMetrics](http://foxmetrics.com/) - analytics to track your user’s actions and activities. `©` `SaaS`
 * [Adobe Analytics](https://www.adobe.com/analytics/web-analytics.html) - web data into insights that everyone can act on. `©` `SaaS`
-* [Google Analytics](https://www.google.com/analytics/) - de facto standard for analytics in the web analytics space. `©` `SaaS`
+* [Google Analytics](https://marketingplatform.google.com/about/analytics/) - de facto standard for analytics in the web analytics space. `©` `SaaS`
 * [Screpy](https://screpy.com) - Screpy is a web analyzer and monitoring tool. Its powered by Google Lighthouse. `©` `SaaS`
 * [Clicktale](https://www.clicktale.com) - record and watch exactly how a visitor used your website. `©` `SaaS`
 * [GoSquared](https://www.gosquared.com/) - analytics with visitor tagging to help you dig deeper into one user’s visit. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>https://www.google.com/analytics/ redirects to https://marketingplatform.google.com/about/analytics/ (curl followed the redirect before the proxy blocked the destination host). Google Analytics is active (GA4 help center reachable). The description is a subjective but uncontroversial characterization. Proposed change is URL only.</p>

<p>https://www.google.com/analytics/ — curl -L effective URL became https://marketingplatform.google.com/about/analytics/. The final page was blocked by the session proxy.</p>

<p>https://support.google.com/analytics/answer/12159447 — HTTP 200 &#x27;How Google Analytics works - Analytics Help&#x27;, confirming the product is active.</p>

<p>Caveats: The redirect destination page body could not be loaded through the proxy.</p>

<p>Independent source check: Listed Google URL redirects to the proposed Marketing Platform destination, and destination content directly describes Google Analytics. Valid canonical-URL cleanup; not a strong semantic-maintenance example.</p>

<p>https://www.google.com/analytics/ — Redirect to https://marketingplatform.google.com/about/analytics/ observed.</p>

<p>https://marketingplatform.google.com/about/analytics/ — Official Google Analytics product page read directly.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Crawl Track — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -57,7 +57,7 @@
 * [parse.ly](https://www.parse.ly) - real-time web analytics tool with a focus on tracking content. `©` `SaaS`
 * [Kissmetrics](https://www.kissmetrics.com/) - real-time standard cohort analysis tool. `©` `SaaS`
 * [Sitemeter](http://sitemeter.com/) - old analytics tool. `©` `SaaS`
-* [Crawl Track](http://www.crawltrack.net/) - another old analytics tool. `©` `SaaS`
+* [Crawl Track](http://www.crawltrack.net/) - Self-hosted PHP/MySQL webmaster dashboard for web analytics and SEO, focused on tracking search engine crawlers. `©` `SaaS`
 * [Sitespect](https://www.sitespect.com/) - full-suite web app analytics tool including A/B testing. `©` `SaaS`
 * [Kirro](https://kirro.io/) - A/B testing tool with visual editor and GA4 conversion tracking. 9KB script. `©` `SaaS`
 * [ExperimentFlow](https://experimentflow.com) - A/B testing and AI personalisation platform. Features neural bandits, lightweight SDK, privacy-first (no cookies, no PII). Google Optimize alternative. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>crawltrack.net still serves CrawlTrack, a free PHP/MySQL script for webmasters. It does web analytics and SEO and focuses on tracking search-engine crawlers. &#x27;another old analytics tool&#x27; is vague and gives no factual description. The latest download is release 3.3.2 from 26 November 2011. The suffix tags `©` `SaaS` look wrong for a free downloadable self-hosted script, but tags have to be changed by hand.</p>

<p>https://crawltrack.net/ — http://www. redirects to https://crawltrack.net/. The page reads &#x27;CrawlTrack, webmaster dashboard. Web analytic and SEO&#x27; and &#x27;Two php/MySQL scripts, free and easy to install&#x27;. Quoted testimonials describe it as a free robot/spider tracker. Footer: copyright@2023.</p>

<p>https://crawltrack.net/download.php — &#x27;Download CrawlTrack release 3.3.2 26th November 2011&#x27;. The install needs PHP and one MySQL database.</p>

<p>Caveats: Tags `©` `SaaS` look inaccurate for a free self-hosted PHP script, and I found no license statement. Fixing the tags would be a separate manual edit.; I did not run the software. The last release was 2011, and I did not check compatibility with current PHP.</p>

</details>

<h3>Chartbeat — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -46,7 +46,7 @@
 * [Woopra](https://www.woopra.com/) - track where your users are coming from. `©` `SaaS`
 * [Mint](https://haveamint.com/) - self-hosted analytics solution (no longer on sale).  `©` `SaaS`
 * [Going Up](https://www.goingup.com/) - manage SEO analytics and web app analytics with one tool. `©` `SaaS`
-* [Chartbeat](https://chartbeat.com/) - beautiful, real-time app analytics tool for web apps. `©` `SaaS`
+* [Chartbeat](https://chartbeat.com/) - Real-time content analytics for digital publishers and newsrooms. `©` `SaaS`
 * [Gauges](http://get.gaug.es/) - real-time web analytics tool. `©` `SaaS`
 * [Indicative](https://www.indicative.com/) - Web & mobile analytics tool, with heavy emphasis on segmentation and funnel visualization. `©` `SaaS`
 * [Open Web Analytics](http://www.openwebanalytics.com/) - Google Analytics and Matomo alternative. ([Source Code](https://github.com/padams/Open-Web-Analytics)) `GPL-2.0` `PHP`
```

<details>
<summary>Evidence and limitations</summary>

<p>Chartbeat is a real-time content analytics (&#x27;content intelligence&#x27;) platform for digital publishers and newsrooms, not an app analytics tool for web apps. &#x27;real-time app analytics tool for web apps&#x27; misdescribes who it is for and what it measures. My only access to chartbeat.com was through search-engine excerpts. Direct fetches failed in this environment.</p>

<p>https://chartbeat.com/solutions-for-media/chartbeat-content-intelligence-solutions/ — Search excerpt: Chartbeat calls itself the &#x27;leading content intelligence solution built specifically for digital publishers, editorial teams, and enterprise media organizations&#x27;.</p>

<p>https://help.chartbeat.com/hc/en-us/articles/360017718013-What-is-Chartbeat — Search excerpt: a Real-Time Dashboard tracks every page, engaged time, referrers and scroll depth, and metrics update every few seconds.</p>

<p>Caveats: Direct HTTP fetches of chartbeat.com failed in this environment with a proxy CONNECT 502. The evidence comes from search-result excerpts of official pages, not full page reads. This looks like an access failure, not a dead site.; &#x27;beautiful&#x27; is subjective, and the proposed wording drops it.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Gauges — remove</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Search excerpts of Fathom Analytics&#x27; own announcement say Fathom bought Gauges from ReportGarden in April 2026, Gauges shut down on 30 April 2026, and customers and historical data moved to Fathom. The get.gaug.es site reportedly now serves Fathom pages. Fathom is already in the catalog under Privacy focused analytics, so removing this entry is better than replacing it. I could not read the official pages directly.</p>

<p>https://usefathom.com/blog/fathom-acquires-gauges — Search excerpt of Fathom&#x27;s official post: Fathom acquired Gauges, Gauges was shut down on 30 April 2026, and Fathom moved everyone over, historical data included.</p>

<p>https://get.gaug.es/website-analytics/ — Search result for the listed domain is titled &#x27;Fathom Analytics: Privacy-First Google Analytics Alternative&#x27;, so the Gauges domain now presents Fathom.</p>

<p>https://coywolf.com/news/startups/exclusive-fathom-analytics-acquires-gauges-from-reportgarden/ — Search excerpt (secondary): ReportGarden told Gauges customers the service would shut down on April 30, 2026, and Fathom bought it on April 15, 2026.</p>

<p>Blocking questions: I could not read the Fathom announcement or the current get.gaug.es page directly. A maintainer should confirm the shutdown notice before removing.</p>

<p>Caveats: The official sources were seen only through search excerpts. Direct fetches of get.gaug.es (502) and usefathom.com failed in this environment.; Fathom is already listed at README line 132 (https://usefathom.com/), so a replace would duplicate it.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Indicative — remove</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>mParticle acquired Indicative in January 2022 and renamed it mParticle Analytics. Search excerpts of mParticle&#x27;s official Analytics documentation show a banner: &#x27;We began sunsetting mParticle Analytics on October 1, 2026.&#x27; That would be affirmative official evidence that the listed product is being retired. I could not read it directly.</p>

<p>https://docs.mparticle.com/guides/analytics/introduction/ — Search excerpt: the banner reads &#x27;We began sunsetting mParticle Analytics on October 1, 2026&#x27; and says the documentation is retained for reference. No final shutdown date is given.</p>

<p>https://www.indicative.com/resource/indicative-joins-mparticle/ — Search result: Indicative&#x27;s own announcement that it was joining mParticle.</p>

<p>https://www.mparticle.com/news/mparticle-acquires-customer-journey-analytics-provider-indicative/ — Search result: mParticle&#x27;s press release on acquiring Indicative (January 2022).</p>

<p>Blocking questions: I saw the sunset banner only in a search excerpt. A maintainer should open docs.mparticle.com and confirm the wording and whether indicative.com still offers the product before removing.</p>

<p>Caveats: Direct fetches of indicative.com and docs.mparticle.com failed in this environment. The evidence is search excerpts.; The sunset is described as in progress, with no final date. Some third-party listings still describe the product as active.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Adobe Digital Analytics — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -52,7 +52,7 @@
 * [Open Web Analytics](http://www.openwebanalytics.com/) - Google Analytics and Matomo alternative. ([Source Code](https://github.com/padams/Open-Web-Analytics)) `GPL-2.0` `PHP`
 * [OneQuery](https://github.com/wordbricks/onequery) - Self-hosted gateway for safe, auditable queries for agents across approved data sources. `Apache-2.0` `Self-Hosted` `Rust`
 * [Statcounter](https://statcounter.com/) - one of the ORIGINAL web analytics tools available. `©` `SaaS`
-* [Adobe Digital Analytics](http://www.adobe.com/data-analytics-cloud/analytics/capabilities.html) - standard analytics tools plus some that large organizations can use. `©` `SaaS`
+* [Adobe Digital Analytics](https://business.adobe.com/products/adobe-analytics.html) - standard analytics tools plus some that large organizations can use. `©` `SaaS`
 * [Hitslink.com](https://www.hitslink.com/) - real-time analytics, social media traffic reporting, and real-time dynamic segmentation. `©` `SaaS`
 * [parse.ly](https://www.parse.ly) - real-time web analytics tool with a focus on tracking content. `©` `SaaS`
 * [Kissmetrics](https://www.kissmetrics.com/) - real-time standard cohort analysis tool. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL is a legacy adobe.com path. WebFetch saw it redirect to https://www.adobe.com/analytics/adobe-analytics-features.html and then 301 to https://business.adobe.com/products/analytics/adobe-analytics-features.html. Adobe&#x27;s current main product page is https://business.adobe.com/products/adobe-analytics.html, where the product is Adobe Analytics (shown as &#x27;digital analytics&#x27; / &#x27;Adobe CX Analytics&#x27;). The description is still broadly accurate, so this is a URL update only.</p>

<p>https://www.adobe.com/analytics/adobe-analytics-features.html — WebFetch got a 301 Moved Permanently to https://business.adobe.com/products/analytics/adobe-analytics-features.html. The listed http URL returned 403 to plain curl.</p>

<p>https://business.adobe.com/products/adobe-analytics.html — Search excerpt of the official product page: Adobe Analytics covers web, mobile and product interactions, governance, attribution and AI insights.</p>

<p>https://business.adobe.com/products/adobe-analytics/digital-analytics.html — Search excerpt: &#x27;Digital analytics&#x27; is how it is described on business.adobe.com, while &#x27;Adobe Analytics&#x27; is the sign-in and contract name.</p>

<p>Caveats: I could not fetch the final business.adobe.com page directly. Its content comes from search excerpts.; The entry name &#x27;Adobe Digital Analytics&#x27; is not Adobe&#x27;s product name (Adobe Analytics). A rename could be considered, but Adobe&#x27;s branding is shifting, so I did not propose one.; The &#x27;large organizations&#x27; framing is reasonable for an enterprise product.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Kissmetrics — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -55,7 +55,7 @@
 * [Adobe Digital Analytics](http://www.adobe.com/data-analytics-cloud/analytics/capabilities.html) - standard analytics tools plus some that large organizations can use. `©` `SaaS`
 * [Hitslink.com](https://www.hitslink.com/) - real-time analytics, social media traffic reporting, and real-time dynamic segmentation. `©` `SaaS`
 * [parse.ly](https://www.parse.ly) - real-time web analytics tool with a focus on tracking content. `©` `SaaS`
-* [Kissmetrics](https://www.kissmetrics.com/) - real-time standard cohort analysis tool. `©` `SaaS`
+* [Kissmetrics](https://www.kissmetrics.io/) - real-time standard cohort analysis tool. `©` `SaaS`
 * [Sitemeter](http://sitemeter.com/) - old analytics tool. `©` `SaaS`
 * [Crawl Track](http://www.crawltrack.net/) - another old analytics tool. `©` `SaaS`
 * [Sitespect](https://www.sitespect.com/) - full-suite web app analytics tool including A/B testing. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed domain kissmetrics.com no longer belongs to Kissmetrics. Kissmetrics&#x27; own post on kissmetrics.io says the domain was sold to Neil Patel and its URLs redirect to his blog. The product now runs at kissmetrics.io, with a V2 rebuild in 2026. Cohort analysis is still a listed feature, so the description can stay.</p>

<p>https://kissmetrics.io/blog/kissmetrics-blog-teardown — Search excerpt of Kissmetrics&#x27; own post: the kissmetrics.com domain was sold to Neil Patel, its URLs redirect to his blog homepage, and the redirects live on &#x27;a domain the company no longer controls&#x27;.</p>

<p>https://news.ycombinator.com/item?id=17416996 — A 2018 thread reports kissmetrics.com becoming Neil Patel&#x27;s SEO blog, while Kissmetrics moved its site to its parent, Space Pencil.</p>

<p>https://kissmetrics.io/tools/product-analytics — Search result: kissmetrics.io is the current official site, with blog, pricing and support at support.kissmetrics.io.</p>

<p>Caveats: I could not fetch kissmetrics.com or kissmetrics.io directly, so the current redirect behaviour of the old domain is unverified.; Kissmetrics now presents itself as person-based product and marketing analytics. A broader description is optional.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Glassbox — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -64,7 +64,7 @@
 * [Rakam](https://rakam.io/) - Custom analytics platform that lets you to create your own analytics service. Integrate with any data source (web, mobile, IoT etc.), analyze data with SQL and create dashboards. ([Source Code](https://github.com/rakam-io/rakam)) `Apache-2.0` `Java`
 * [Metabase](https://www.metabase.com) - opensource analytics/BI tool  `©` `SaaS`
 * [LiveSession](https://livesession.io) - session replay user analytics. `©` `SaaS`
-* [Glassbox](https://glassboxdigital.com/) - customer experince and session recording analytics. `©` `SaaS`
+* [Glassbox](https://glassboxdigital.com/) - customer experience and session recording analytics. `©` `SaaS`
 * [Sequential](https://www.usesequential.com/) - session replay and product analytics with an AI judge that reviews each session and lists the findings to fix. `©` `SaaS`
 * [Redash](https://redash.io/) - open source analytics/BI tool `©` `SaaS`
 * [AWStats](http://www.awstats.org/) - Generates web, streaming, ftp or mail server statistics graphically. ([Source Code](https://github.com/eldy/awstats)) `GPL-3.0` `Perl`
```

<details>
<summary>Evidence and limitations</summary>

<p>Glassbox is still a digital customer experience analytics platform centred on session replay, so the entry is relevant and broadly accurate. The description has a typo (&#x27;experince&#x27;). The company&#x27;s current official site appears to be glassbox.com rather than the listed glassboxdigital.com. I could not verify a redirect between the two, so I propose only the typo fix and leave the URL change for the maintainer to confirm.</p>

<p>https://www.glassbox.com/ — Search result titled &#x27;Digital Customer Experience Analytics - Glassbox&#x27;. It describes capturing 100% of web and mobile sessions with video-like replay.</p>

<p>https://www.glassbox.com/cp/session-recording-tool/ — Search result: Glassbox&#x27;s official session replay product page.</p>

<p>https://github.com/Glassbox-Digital-Experience-Analytics — Search result: Glassbox&#x27;s GitHub org, &#x27;Glassbox Digital Experience Analytics&#x27;.</p>

<p>Caveats: Direct fetches of glassboxdigital.com and glassbox.com failed in this environment. I could not confirm whether glassboxdigital.com redirects to glassbox.com. If it does, the maintainer may also update the URL to https://www.glassbox.com/.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Druid — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -69,7 +69,7 @@
 * [Redash](https://redash.io/) - open source analytics/BI tool `©` `SaaS`
 * [AWStats](http://www.awstats.org/) - Generates web, streaming, ftp or mail server statistics graphically. ([Source Code](https://github.com/eldy/awstats)) `GPL-3.0` `Perl`
 * [Countly](https://count.ly) - Real time mobile and web analytics, crash reporting and push notifications platform. ([Source Code](https://github.com/countly)) `AGPL-3.0` `Javascript`
-* [Druid](http://druid.io/) - Distributed, column-oriented, real-time analytics data store. ([Source Code](https://github.com/druid-io/druid)) `Apache-2.0` `Java`
+* [Druid](https://druid.apache.org/) - Distributed, column-oriented, real-time analytics data store. ([Source Code](https://github.com/druid-io/druid)) `Apache-2.0` `Java`
 * [Hastic](https://hastic.io) - Hackable time series pattern recognition tool with UI for Grafana. ([Source Code](https://github.com/hastic)) `Apache-2.0` `Python/Nodejs`
 * [Edalitics](https://www.edalitics.com) - Open source analytics/BI tool.  ([Source Code](https://github.com/jortilles/EDA)) `©` `SaaS` `AGPL-3.0` `Angular/Nodejs`
 * [Count](https://count.co/) - notebook-based analytics platform, use SQL or drag-and-drop to build queries. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>The project is now Apache Druid. http://druid.io/ redirects to https://druid.apache.org/, and the github.com/druid-io/druid source link redirects to apache/druid. The description (distributed, column-oriented, real-time analytics data store) still matches the official &#x27;real-time analytics database&#x27;. Proposed change: use the canonical URL.</p>

<p>https://druid.apache.org/ — The druid.io link resolves here. The page says &#x27;A high performance, real-time analytics database that delivers sub-second queries on streaming and batch data at scale&#x27;.</p>

<p>https://github.com/druid-io/druid — Redirects to https://github.com/apache/druid. The repo description is &#x27;Apache Druid: a high performance real-time analytics database.&#x27; It is not archived.</p>

<p>Caveats: The inline Source Code link (github.com/druid-io/druid) also redirects to github.com/apache/druid and should be updated by hand.; The name could optionally become &#x27;Apache Druid&#x27;. Not proposed, because &#x27;Druid&#x27; is still accurate.</p>

</details>

<h3>Zoho Apptics — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -81,7 +81,7 @@
 * [StackData](https://greg-rg-git.github.io/stackdata-store/tools/compare/) - Free SaaS pricing comparison tool with pricing data; structured CSV datasets available for bulk analysis. `©` `SaaS`
 * [Klinky](https://klinky.io) - A/B testing link shortener that splits one link between two destinations, with click counts. `©` `SaaS`
 * [Replayowl](https://replayowl.com/) - Open source, self-hosted session replay that runs on Cloudflare Workers or Node. ([Source Code](https://github.com/replayowl/replayowl)) `AGPL-3.0` `TypeScript`
-* [Zoho Apptics](https://www.zoho.com/apptics) – Cross-platfom analytics to monitor performance, analyze user behavior and collect feedback for mobile, web, and desktop apps.
+* [Zoho Apptics](https://www.zoho.com/apptics) – Cross-platform analytics to monitor performance, analyze user behavior and collect feedback for mobile, web, and desktop apps.
 * [rrweb](https://rrweb.com) - Open-source session replay library for the browser. Records the DOM and user interactions and replays them pixel-perfect. ([Source Code](https://github.com/rrweb-io/rrweb)) `MIT` `TypeScript`
 * [OpenPanel](https://openpanel.dev) - OpenPanel is an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting. `©` `Self-Hosted` `EU` 
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The content is accurate: Zoho Apptics offers product analytics, performance tracking, user flows and feedback across mobile, web and desktop SDKs. The description has a confirmed spelling error (&#x27;Cross-platfom&#x27;). This is a minimal prose correction.</p>

<p>https://www.zoho.com/apptics/ — &#x27;track app performance, analyze user flows, capture feedback ... Supporting 10+ SDKs for mobile, web, and desktop apps.&#x27;</p>

<p>Caveats: Typo-only change. Optional.</p>

</details>

<h3>Census — replace</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -106,7 +106,7 @@
 
 ## Endpoints
 **[`^        back to top        ^`](#)**
-* [Census](https://getcensus.com/) - The easiest way to sync your customer data from your cloud data warehouse to SaaS applications like Salesforce, Marketo, HubSpot, Zendesk, etc. Census is the operational analytics platform that syncs your data warehouse with all your favorite apps. Get your customer success, sales & marketing teams on the same page by keeping customer data in sync. No engineering favors required—just SQL. `SaaS`
+* [Fivetran Activations](https://www.fivetran.com/data-movement/activations) - Reverse ETL from Fivetran (formerly Census): syncs modeled customer data from your cloud data warehouse to business tools such as CRMs, marketing automation and support apps, with self-service audience building. `SaaS`
 * [Rawbbit](https://rawbbit.one/) - Self-hosted analytics pipeline that lands raw events as Parquet in your own object storage. Designed for teams that want to own their raw event data instead of feeding it into a SaaS vendor's pipeline. Alternative to Firebase Analytics and Amplitude. ([Source Code](https://github.com/mirlan-irokez/rawbbit)) `Apache-2.0` `Python`
 * [RudderStack](https://rudderstack.com/) - The warehouse-first customer data platform (CDP) that builds your CDP on your data warehouse for you. RudderStack makes it easy to collect, unify, transform, and store your customer data as well as route it securely to a wide range of common, popular marketing, sales, and product tools (open-source alternative to Segment et al.). ([Source Code](https://github.com/rudderlabs/rudder-server/)) `AGPL-3.0` `Go`
 * [Snowplow](http://snowplowanalytics.com/) - Analytics tool for web apps with a lot of data. Have every single event, from your websites, mobile apps, desktop applications and server-side systems, stored in your own data warehouse and available to action in real-time. ([Source Code](https://github.com/snowplow/)) `Apache-2.0` `Scala` `real-time`
```

<details>
<summary>Evidence and limitations</summary>

<p>getcensus.com now redirects (301) through www.getcensus.com to fivetran.com. Fivetran&#x27;s own documentation says &#x27;Census joined Fivetran in 2025&#x27; and that Census reverse ETL is being folded into Fivetran Activations. It provides a Census Migration FAQ, and Census Embedded has been renamed. This is an officially documented successor, not a competitor. The current description&#x27;s Census branding and &#x27;easiest way…&#x27; marketing copy no longer match any live product page.</p>

<p>https://getcensus.com/ — curl -IL: 301 to https://www.getcensus.com/, then 301 to https://www.fivetran.com/ (Fivetran homepage).</p>

<p>https://fivetran.com/docs/activations/census-migration-faq — &#x27;Census joined Fivetran in 2025, and since then, we&#x27;ve been integrating Census reverse ETL capabilities into the Fivetran platform.&#x27; Also: &#x27;Activations in Powered by Fivetran (formerly Census Embedded)&#x27;. Workspaces and Activations API V1 retire on January 15, 2027.</p>

<p>https://fivetran.com/docs/activations — &#x27;Activations is a cloud-based product that enables you to configure managed, automated reverse ETL pipelines without writing code. It activates data from a centralized source of truth, such as a data warehouse…&#x27;</p>

<p>https://www.fivetran.com/data-movement/activations — Product page: &#x27;200+ pre-built, automated reverse ETL destinations&#x27;, Audience Hub, and links to &#x27;Fivetran acquires Census to become end-to-end data movement platform&#x27;.</p>

<p>Caveats: Activations is one feature of the wider Fivetran platform, not a standalone product. The maintainer may prefer naming it &#x27;Fivetran Activations (formerly Census)&#x27;.; The SaaS tag still applies.; Alphabetical order in Endpoints (Census, Rawbbit, RudderStack, Snowplow) is preserved: &#x27;Fivetran Activations&#x27; still sorts before Rawbbit.</p>

</details>

<h3>AuditorIA — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -113,7 +113,7 @@
 
 ## SEO
 **[`^        back to top        ^`](#)**
-* [AuditorIA](https://landing-five-dusky-44.vercel.app) - Free automated SEO audit for local businesses. Detects HTTPS, meta tags, Schema markup, viewport, and phone visibility in 30 seconds. No registration required. `©` `SaaS`
+* [AuditorIA](https://landing-five-dusky-44.vercel.app) - Spanish-language SEO and digital presence audits for local businesses: a free 30-second check highlights top website issues, with paid one-time reports (SEO, business, Meta Ads) delivered within 24 hours. `©` `SaaS`
 * [Serposcope](https://serposcope.serphacker.com/) - Serposcope is a free and open-source rank tracker to monitor websites ranking in Google and improve your SEO performances. ([Source Code](https://github.com/serphacker/serposcope)) `MIT` `Java`
 * [gsc-hub](https://github.com/izzipizzy/gsc-hub) - Local self-hosted multi-account hub for Google Search Console: all sites from several Google accounts in one table, aggregated queries and pages, per-site SEO analytics. ([Source Code](https://github.com/izzipizzy/gsc-hub)) `MIT` `Self-Hosted` `TypeScript`
 * [FeedPulse](https://feed-pulse.com) - Free SEO checkers: domain authority, domain rating, SERP position, Google index status, page speed, plus a schema generator. Also serves embeddable traffic and visitor-country widgets. No signup, no paid tier. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>The page has become a Spanish-language paid digital audit service: SEO audit from €99, business audit, a Meta Ads audit and a €299 pack, with reports delivered within 24 hours. A free mini-check returns &#x27;3 errores de tu web en 30 segundos&#x27;, but the results step asks for an email (&#x27;Introduce tu email para ver el informe completo&#x27;). The listed claims of a fully free audit with no registration that detects viewport and phone visibility are not supported by current page content.</p>

<p>https://landing-five-dusky-44.vercel.app/ — Title &#x27;AuditorIA — Auditoría digital de tu negocio desde 99€&#x27;. Says &#x27;Gratis, sin registro · Resultados en 30 segundos · Pago único desde 99€&#x27;. The free section reads &#x27;Prueba gratis — 3 errores de tu web en 30 segundos&#x27;, and the next step asks for an email to see the full results. Paid plans: Auditoría SEO 99€, Auditoría de Negocio, and a Pack Triple 299€ (SEO + Business + Meta Ads). Also offers free tools: a Schema markup generator and a speed test.</p>

<p>https://landing-five-dusky-44.vercel.app/ — The page&#x27;s JSON-LD sets areaServed &#x27;ES&#x27;. Checkout runs through auditoria.lemonsqueezy.com, and the mini-audit calls /api/solicitud?action=mini.</p>

<p>Caveats: The free mini-audit was not run, so the exact checks it performs (HTTPS, meta tags, viewport, phone visibility) were not observed.; The listed URL is a Vercel deployment subdomain. No separate canonical domain was found, so the URL may change.; Whether a paid audit service fits an analytics tools list is for the maintainer to decide.</p>

</details>

<h3>NotFair — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -123,7 +123,7 @@
 * [GeoBuddy](https://geobuddy.co/) - AI search analytics: tracks whether ChatGPT, Claude, Gemini and Perplexity mention your brand, with rank, share of voice and competitor tracking; free check without signup.
 * [LLM Pulse](https://llmpulse.ai/) - AI search analytics for tracking brand mentions, citations, sentiment, and competitor share of voice across ChatGPT, Perplexity, Gemini, Google AI Overviews, and Google AI Mode. `©` `SaaS`
 * [SenseGap](https://sensegap.com/) - Analytics for the AI crawlers and agents that visit a website (GPTBot, ClaudeBot, PerplexityBot, ChatGPT-User and others): checks bots against their published IP ranges or forward-confirmed reverse DNS where available and marks the rest unverified, shows which pages AI reads and how many visitors AI sends. The bot list and verification rules are open source. ([Demo](https://sensegap.com/demo), [Source Code](https://github.com/tudortotolici/sensegap)) `©` `SaaS`
-* [NotFair](https://github.com/nowork-studio/NotFair) - Open-source Claude Code agent skills for SEO, Google Ads, and Meta Ads, connecting to live data via Google Ads MCP, Meta Ads MCP, Google Search Console MCP, and Google Analytics (GA4) MCP. Covers site audits, keyword research, meta tags, schema markup, GEO optimization, wasted-spend detection, and creative analysis. ([Source Code](https://github.com/nowork-studio/NotFair)) `MIT`
+* [NotFair](https://github.com/nowork-studio/notfair-plugin) - Open-source SEO, GEO and marketing skills for Claude Code, Codex, Cursor and other AI agents, using live Google Ads, Meta Ads, Google Search Console and Google Analytics (GA4) data through a single hosted NotFair MCP connection. Covers site audits, keyword research, schema markup, GEO optimization, wasted-spend detection, and creative analysis. ([Source Code](https://github.com/nowork-studio/NotFair)) `MIT`
 * [MessGEO](https://messgeo.com/) - AI search analytics that tracks how brands appear in ChatGPT, Gemini, Copilot, Google AI Mode and AI Overviews, with daily prompt tracking, share of voice and competitor comparison. `©` `SaaS`
 
 ## Privacy focused analytics
```

<details>
<summary>Evidence and limitations</summary>

<p>https://github.com/nowork-studio/NotFair now redirects (301) to nowork-studio/notfair-plugin (MIT, active). The current README describes skills for Claude Code, Codex, Cursor and other agents, not only Claude Code. Live data now comes through one hosted NotFair MCP connection, not separate Google Ads, Meta Ads, Search Console and GA4 MCPs. The docs say explicitly: &#x27;do not add an MCP server per platform&#x27;. The SEO, GEO, Google Ads, Meta Ads, GA4 and Search Console capabilities remain.</p>

<p>https://github.com/nowork-studio/NotFair — HTTP 301 to https://github.com/nowork-studio/notfair-plugin. The GitHub API resolves to full_name nowork-studio/notfair-plugin: MIT, not archived, pushed 2026-11-10.</p>

<p>https://raw.githubusercontent.com/nowork-studio/notfair-plugin/main/README.md — &#x27;Open-source SEO, GEO, and marketing skills for AI agents… gives Claude Code, Codex, Hermes, and other compatible agents practical marketing workflows&#x27;. Covers SEO audits, keyword research, schema, GEO, Google Ads, Meta Ads (creative fatigue), wasted ad spend, and GA4 and Search Console. &#x27;currently ships 45 skills&#x27;.</p>

<p>https://raw.githubusercontent.com/nowork-studio/notfair-plugin/main/docs/mcp-connection.md — &#x27;Use one HTTP server named NotFair at https://notfair.co/api/mcp/notfair… Connect Google Ads, Meta Ads, … Google Search Console, Google Analytics… inside that workspace; do not add an MCP server per platform.&#x27;</p>

<p>Caveats: The ([Source Code](https://github.com/nowork-studio/NotFair)) link in the entry suffix also redirects and needs a manual update to https://github.com/nowork-studio/notfair-plugin.; The skills are MIT-licensed, but live-data access goes through a hosted NotFair service with OAuth.; The repository is titled &#x27;NotFair Plugin&#x27;. The brand name NotFair is kept.</p>

</details>

<h3>KISSS — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -97,7 +97,7 @@
 ## Website analytics
 **[`^        back to top        ^`](#)**
 
-* [KISSS](https://kis3.dev) - Very minimalistic (KISS) website statistics tool. ([Source Code](https://github.com/kis3/kis3)) `MIT` `Go`
+* [KISSS](https://git.jlel.se/jlelse/kis3) - Very minimalistic (KISS) website statistics tool. ([Source Code](https://github.com/kis3/kis3)) `MIT` `Go`
 * [Umami](https://umami.is) - Umami is a simple, fast, privacy-focused alternative to Google Analytics. Umami is GDPR compliant. ([Source Code](https://github.com/umami-software/umami)) `MIT` `JavaScript`
 * [Vectr4](https://vectr4.com/) - Self-hosted web analytics with funnels and more. `©` `Self-Hosted` `Docker`
 * [OpenPanel](https://openpanel.dev) - OpenPanel is an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting. `©` `Self-Hosted` `EU`
```

<details>
<summary>Evidence and limitations</summary>

<p>kis3.dev no longer resolves (getaddrinfo ENOTFOUND), and github.com/kis3/kis3 returns 404. The author&#x27;s own Gitea instance hosts the project at git.jlel.se/jlelse/kis3. It was archived on 2021-01-04, and the last commit is &#x27;Update dependencies and remove kis3.dev reference&#x27;. The Go module path is git.jlel.se/jlelse/kis3. The description is still accurate for the archived code, so this updates the URL only. Archival alone is not grounds for removal.</p>

<p>https://git.jlel.se/jlelse/kis3 — &#x27;jlelse/kis3: Keep It Simple Stupid Stats (KISSS)&#x27;. &#x27;This repository has been archived on 2021-01-04.&#x27; Last commit: e066c7d547 &#x27;Update dependencies and remove kis3.dev reference&#x27; (2021-01-04). Mostly Go (91.4%).</p>

<p>https://git.jlel.se/api/v1/repos/jlelse/kis3 — Gitea API: full_name jlelse/kis3, archived true, description &#x27;Keep It Simple Stupid Stats (KISSS)&#x27;.</p>

<p>https://github.com/kis3/kis3 — HTTP 404. The GitHub API also returns Not Found for kis3/kis3.</p>

<p>https://jlelse.blog/thoughts/2019/04/kis3 — Author&#x27;s post (found via search) introducing kis3 as his own minimal, privacy-respecting website statistics tool.</p>

<p>Caveats: The ([Source Code](https://github.com/kis3/kis3)) link in the suffix is also dead and needs a manual change to https://git.jlel.se/jlelse/kis3. That would make it duplicate the main URL.; The project has been archived since 2021, and the author has written that he no longer uses it. The maintainer may still decide whether an unmaintained tool belongs in the list; that is outside this freshness check.; The kis3.dev failure was a DNS NXDOMAIN, and the author removed the domain reference from the repo, so a temporary outage is unlikely.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Snowplow — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -109,7 +109,7 @@
 * [Census](https://getcensus.com/) - The easiest way to sync your customer data from your cloud data warehouse to SaaS applications like Salesforce, Marketo, HubSpot, Zendesk, etc. Census is the operational analytics platform that syncs your data warehouse with all your favorite apps. Get your customer success, sales & marketing teams on the same page by keeping customer data in sync. No engineering favors required—just SQL. `SaaS`
 * [Rawbbit](https://rawbbit.one/) - Self-hosted analytics pipeline that lands raw events as Parquet in your own object storage. Designed for teams that want to own their raw event data instead of feeding it into a SaaS vendor's pipeline. Alternative to Firebase Analytics and Amplitude. ([Source Code](https://github.com/mirlan-irokez/rawbbit)) `Apache-2.0` `Python`
 * [RudderStack](https://rudderstack.com/) - The warehouse-first customer data platform (CDP) that builds your CDP on your data warehouse for you. RudderStack makes it easy to collect, unify, transform, and store your customer data as well as route it securely to a wide range of common, popular marketing, sales, and product tools (open-source alternative to Segment et al.). ([Source Code](https://github.com/rudderlabs/rudder-server/)) `AGPL-3.0` `Go`
-* [Snowplow](http://snowplowanalytics.com/) - Analytics tool for web apps with a lot of data. Have every single event, from your websites, mobile apps, desktop applications and server-side systems, stored in your own data warehouse and available to action in real-time. ([Source Code](https://github.com/snowplow/)) `Apache-2.0` `Scala` `real-time`
+* [Snowplow](https://snowplow.io/) - Analytics tool for web apps with a lot of data. Have every single event, from your websites, mobile apps, desktop applications and server-side systems, stored in your own data warehouse and available to action in real-time. ([Source Code](https://github.com/snowplow/)) `Apache-2.0` `Scala` `real-time`
 
 ## SEO
 **[`^        back to top        ^`](#)**
```

<details>
<summary>Evidence and limitations</summary>

<p>Snowplow&#x27;s official domain is now snowplow.io. GitHub shows the verified domain snowplow.io as the org website, and the old snowplowanalytics.com website repo is archived. The listed http://snowplowanalytics.com/ returned 502 through the sandbox proxy. The description of event-level data delivered to your own warehouse in real time still matches. Separately, the `Apache-2.0` tag is out of date for new core pipeline releases, which have used the Snowplow Limited Use License since January 2024.</p>

<p>https://snowplow.io/ — Live. Delivers &#x27;validated, enriched event-level data in real time to your warehouse, lake, or stream&#x27;.</p>

<p>https://github.com/snowplow — GitHub org API: login &#x27;snowplow&#x27;, blog https://snowplow.io. Search results report snowplow.io as a verified domain for the org.</p>

<p>https://raw.githubusercontent.com/snowplow/snowplow/master/README.md — &#x27;As of January 8, 2024, Snowplow introduced the Snowplow Limited Use License Agreement, and we are releasing new versions of our core pipeline technology under this license.&#x27; It describes collecting event-level data in real time and delivering it to &#x27;their warehouse, lake, or stream&#x27;.</p>

<p>Caveats: The redirect from snowplowanalytics.com to snowplow.io could not be observed directly; the proxy returned 502. The new URL rests on GitHub org metadata and the live official site.; The `Apache-2.0` licence tag should be reviewed by hand, since core pipeline releases are now under the Snowplow Limited Use License; some trackers may still be Apache-2.0.; Snowplow now positions itself as a &#x27;Customer Context Layer&#x27; for AI. That is a change in marketing; the listed capabilities remain.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Serposcope — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -114,7 +114,7 @@
 ## SEO
 **[`^        back to top        ^`](#)**
 * [AuditorIA](https://landing-five-dusky-44.vercel.app) - Free automated SEO audit for local businesses. Detects HTTPS, meta tags, Schema markup, viewport, and phone visibility in 30 seconds. No registration required. `©` `SaaS`
-* [Serposcope](https://serposcope.serphacker.com/) - Serposcope is a free and open-source rank tracker to monitor websites ranking in Google and improve your SEO performances. ([Source Code](https://github.com/serphacker/serposcope)) `MIT` `Java`
+* [Serposcope](https://www.serposcope.com/) - Serposcope is a free rank tracker to monitor websites ranking in Google. The open-source v2 codebase is archived legacy code that is no longer actively maintained. ([Source Code](https://github.com/serphacker/serposcope)) `MIT` `Java`
 * [gsc-hub](https://github.com/izzipizzy/gsc-hub) - Local self-hosted multi-account hub for Google Search Console: all sites from several Google accounts in one table, aggregated queries and pages, per-site SEO analytics. ([Source Code](https://github.com/izzipizzy/gsc-hub)) `MIT` `Self-Hosted` `TypeScript`
 * [FeedPulse](https://feed-pulse.com) - Free SEO checkers: domain authority, domain rating, SERP position, Google index status, page speed, plus a schema generator. Also serves embeddable traffic and visitor-country widgets. No signup, no paid tier. `©` `SaaS`
 * [Vaneform](https://vaneform.com/) - Free website traffic lookup: estimated monthly visits, traffic sources, top countries, search keywords and similar sites for any domain, no signup required. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>https://serposcope.serphacker.com/ redirects to https://www.serposcope.com/, which returns 403 to automated clients. The source repo is archived, labelled &#x27;Rank tracker for SEO - LEGACY CODE&#x27;, and its README says &#x27;Old application in survival mode. Bug won&#x27;t be fixed and PR won&#x27;t be merged.&#x27; The repo&#x27;s homepage field is www.serposcope.com. The URL should move to the canonical domain, and the description should not imply an actively maintained project.</p>

<p>https://serposcope.serphacker.com/ — curl -L ends at https://www.serposcope.com/?pk_campaign=serposcope2_site, which returns HTTP 403 to non-browser clients.</p>

<p>https://github.com/serphacker/serposcope — GitHub API: archived true, description &#x27;Rank tracker for SEO - LEGACY CODE&#x27;, homepage https://www.serposcope.com, MIT, last pushed 2024-01-22.</p>

<p>https://raw.githubusercontent.com/serphacker/serposcope/master/README.md — &#x27;LEGACY CODE DISCLAIMER: Old application in survival mode. Bug won&#x27;t be fixed and PR won&#x27;t be merged.&#x27; &#x27;Serposcope is an open source search engine rank checker for SEO&#x27;. MIT licence.</p>

<p>https://www.serposcope.com/en/ — Seen only via search result (direct fetch got 403). Title &#x27;Serposcope - Free rank tracker for SEO&#x27;. Snippets say Serposcope &#x27;is no longer supported and may not work&#x27;, v3 source is &#x27;not yet available&#x27;, and a SaaS version is in development.</p>

<p>Caveats: serposcope.com could not be read directly (403). Its &#x27;no longer supported&#x27; notice was seen only in search snippets, so the proposed description relies on the GitHub legacy notice.; It is not known whether the legacy v2 Java app still retrieves Google rankings successfully; the software was not run.; The ([Source Code](https://github.com/serphacker/serposcope)) link still resolves to the archived repo.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Plausible Analytics — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Product claims remain accurate: lightweight, open-source, cookie-free, no personal data, Google Analytics alternative; demo works; Source Code link is canonical. The inline &#x27;open source&#x27; link points to github.com/plausible-insights/plausible, which redirects to the canonical plausible/analytics. Proposed change only updates that inline link.</p>

<p>https://github.com/plausible-insights/plausible — Redirects to https://github.com/plausible/analytics.</p>

<p>https://github.com/plausible/analytics — Canonical plausible/analytics; AGPL-3.0; not archived; last commit 2026-11-10.</p>

<p>https://raw.githubusercontent.com/plausible/analytics/HEAD/README.md — &#x27;open source, privacy-first web analytics tool. Lightweight, cookie-free alternative to Google Analytics&#x27;; &#x27;No personal data or IP addresses are stored, and no cookies&#x27;; Live Demo link https://plausible.io/plausible.io.</p>

<p>https://plausible.io/plausible.io — Live demo dashboard renders (read via r.jina.ai).</p>

<p>Caveats: Multi-link entry; apply the inline link change by hand.; plausible.io read via r.jina.ai reader because direct fetch was blocked by the sandbox proxy.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Simple Analytics — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -132,7 +132,7 @@
 * [Fathom](https://usefathom.com/) - Fathom Analytics provides simple, useful websites stats without tracking or storing personal data of your users `©` `SaaS`
 * [Fathom Lite](https://github.com/usefathom/fathom) - Fathom Lite, a lightweight version of Fathom Analytics `MIT` `Self-Hosted`
 * [Plausible Analytics](https://plausible.io/) - Lightweight and [open source](https://github.com/plausible-insights/plausible) web analytics. Doesn’t use cookies and doesn't track personal data. A privacy-friendly alternative to Google Analytics. ([Demo](https://plausible.io/plausible.io), [Source Code](https://github.com/plausible/analytics/)) `AGPL-3.0` `Elixir`
-* [Simple Analytics](https://simpleanalytics.io/) - Simple, clean, and friendly analytics for developers `©` `SaaS`
+* [Simple Analytics](https://www.simpleanalytics.com/) - Simple, clean, and friendly analytics for developers `©` `SaaS`
 * [Logly](https://logly.uk/) - Cookieless web analytics with a sub-1KB tracker. Bots are counted separately and labelled by type — search engines, AI crawlers, SEO tools, monitors — instead of being filtered out silently. ([Demo](https://app.logly.uk/demo)) `©` `SaaS`
 * [Nibspace](https://nibspace.com/) - Affordable, lightweight, privacy-friendly website analytics `©` `SaaS`
 * [Metrical](https://metrical.xyz/) - A privacy-first web analytics tool for everyone. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>simpleanalytics.io now redirects to https://www.simpleanalytics.com/, the current official domain. The product is still privacy-focused, cookieless analytics (no cookies, no personal data, no visitor IDs). The current site no longer markets to &#x27;developers&#x27;, but the existing wording is not a confirmed false claim, so only the URL changes.</p>

<p>https://www.simpleanalytics.com/ — Final URL for https://simpleanalytics.io/ per r.jina.ai. Page lists &#x27;No cookies, No personal data, No visitor IDs, EU-hosted&#x27;; positioned as cookieless analytics alongside GA4.</p>

<p>Caveats: Redirect observed via r.jina.ai reader; direct fetch was blocked by the sandbox proxy.; Optional: description could be refreshed to current positioning (cookieless, no personal data); not required.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Umami — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Umami description remains accurate: self-hostable, privacy-focused, MIT, Node.js. Two inline links are stale. The demo link returns 404, and the README&#x27;s official demo is cloud.umami.is/share/LGazGOecbDtaIwDr/umami.is. The source link github.com/mikecao/umami redirects to the canonical umami-software/umami.</p>

<p>https://app.umami.is/share/ISgW2qz8/flightphp.com — Via r.jina.ai: 404 NOT_FOUND / DEPLOYMENT_NOT_FOUND.</p>

<p>https://github.com/mikecao/umami — Redirects to https://github.com/umami-software/umami.</p>

<p>https://raw.githubusercontent.com/umami-software/umami/HEAD/README.md — &#x27;privacy-first analytics platform... no cookies, no surveillance, self-hosted or in the cloud&#x27;; MIT license badge; demo link https://cloud.umami.is/share/LGazGOecbDtaIwDr/umami.is; requires Node.js 18.18+. package.json license MIT.</p>

<p>https://cloud.umami.is/share/LGazGOecbDtaIwDr/umami.is — Resolves to cloud.umami.is/analytics/eu/share/LGazGOecbDtaIwDr/umami.is with a live Umami dashboard.</p>

<p>https://umami.is/ — &#x27;Open-source web and product analytics&#x27;; &#x27;privacy-first platform. No cookies&#x27;.</p>

<p>Caveats: Multi-link entry; apply link changes by hand.; Umami now also offers a cloud service; &#x27;self-hosted&#x27; remains supported, so the prose is unchanged.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>piratepx — remove</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Official evidence: the piratepx/app repo was archived by the owner on Nov 4, 2025, and its README states &#x27;This project is deprecated and no longer maintained. The hosted version at https://www.piratepx.com will be shut down on December 1, 2025.&#x27; The listed URL (hosted free service) and the demo no longer respond. The entry describes the hosted service (&#x27;Just a little analytics insight... 100% free&#x27;), which has lost its purpose.</p>

<p>https://github.com/piratepx/app — Archive banner: &#x27;archived by the owner on Nov 4, 2025. It is now read-only.&#x27; License MIT.</p>

<p>https://raw.githubusercontent.com/piratepx/app/HEAD/README.md — &#x27;NOTICE: This project is deprecated and no longer maintained. The hosted version at https://www.piratepx.com will be shut down on December 1, 2025.&#x27;</p>

<p>https://www.piratepx.com/ — Connection failed (HTTP 000) from this environment; consistent with the announced shutdown.</p>

<p>Caveats: MIT source code remains publicly available in the archived repo; a maintainer could instead relink it as a historical/self-hostable project.; Site unreachability was tested only from this environment.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Piwik PRO — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -147,7 +147,7 @@
 * [Kindmetrics](https://kindmetrics.io/) - Clean privacy-focused website analytics. ([Source Code](https://github.com/kindmetrics/kindmetrics)) `MIT` `Crystal`
 * [Ackee](https://ackee.electerious.com) - Self-hosted analytics tool for those who care about privacy. ([Demo](http://demo.ackee.electerious.com), [Source Code](https://github.com/electerious/Ackee)) `MIT` `Nodejs`
 * [piratepx](https://www.piratepx.com/) - Just a little analytics insight for your personal or indie project. 100% free and open source. ([Demo](https://app.piratepx.com/shared/bGQbUJ-YADC_xIGZaYmyqp-J_PD6O1pkCdHmYdIjUvs53ExsImlzFeou4MCuZRbH), [Source](https://github.com/piratepx/app)) `MIT` `Nodejs`
-* [Piwik PRO](https://piwik.pro/) - A privacy-friendly alternative to Google Analytics with built-in consent management. Hosted in EU, in your private cloud or on-premises. `©` `SaaS` `Self-Hosted`
+* [Piwik PRO](https://piwik.pro/) - A privacy-friendly alternative to Google Analytics with built-in consent management. Hosted in the EU or in your private cloud. `©` `SaaS` `Self-Hosted`
 * [Swetrix](https://swetrix.com/) - European OSS product & web analytics, ([Source Code](https://github.com/swetrix/swetrix)) `MIT`/`AGPL-3.0` `NodeJS`
 * [GoatCounter](https://www.goatcounter.com/) - GoatCounter is an open source web analytics platform available as a hosted service (free for non-commercial use) or self-hosted app. ([Source](https://github.com/arp242/goatcounter), [Demo](https://stats.arp242.net/)) `MIT` `SaaS` `Self-Hosted`
 * [Rybbit Analytics](https://rybbit.com/) - Rybbit is powerful, lightweight, and super easy to use analytics. Cookieless and GDPR compliant. Hosted on EU infrastructure in Germany. Self-hosting compatible `©` `SaaS` `Self-Hosted` `EU`
```

<details>
<summary>Evidence and limitations</summary>

<p>Piwik PRO is still a privacy-focused analytics platform with a Consent Manager. Its official hosting article says &#x27;Piwik PRO offers public and private cloud, but not on-premise.&#x27; So the &#x27;or on-premises&#x27; claim is wrong, and the `Self-Hosted` tag in the suffix is also inaccurate and should be removed by hand.</p>

<p>https://piwik.pro/blog/public-cloud-private-cloud-self-hosted/ — &#x27;we&#x27;ll use Piwik PRO&#x27;s hosting options as examples along the way. Piwik PRO offers public and private cloud, but not on-premise, which we&#x27;ve included below for comparison.&#x27;</p>

<p>https://piwik.pro/gdpr-consent-manager/ — Consent Manager product page: &#x27;Give your visitors a way to change or withdraw their consents. Consent Manager will automatically adjust data collection.&#x27;</p>

<p>https://piwik.pro/ — &#x27;Piwik PRO is a privacy-focused and HIPAA-supportive analytics platform&#x27;; Consent management feature listed.</p>

<p>Caveats: The `Self-Hosted` metadata tag needs a manual edit.; Pages read via r.jina.ai reader because direct fetch was blocked by the sandbox proxy.; Exact current data-center list (EU and non-EU) not verified from a primary page; &#x27;Hosted in the EU&#x27; is kept as a non-exclusive claim.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Ucoder Insight — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -159,7 +159,7 @@
 * [DevDome Analytics](https://devdome.com/) - Cookieless analytics for WordPress that separates human visitors from bots and AI crawlers. Free plan. ([Plugin Source Code](https://github.com/DevDomeFamily/devdome-analytics)) `GPL-2.0` `SaaS`
 * [Statable](https://statable.com/) - Privacy-first, cookieless web analytics hosted in the EU. Import your Google Analytics 4 history and keep a unified timeline. `©` `SaaS` `EU`
 * [Facet](https://github.com/writerslogic/facet) - Cookieless, privacy-first web analytics & experimentation that runs entirely on the Cloudflare edge (Workers + D1). No cookies, no cross-session identity, raw IP is never stored; GPC/DNT respecting and self-hosted with a one-command deploy. `AGPL-3.0` `Cloudflare Workers`
-* [Ucoder Insight](https://insights.ucoder.in) - Privacy-first, cookie-free web analytics SDK for developers. 7.4kb gzipped, zero dependencies, offline support via IndexDB. ([Source Code](https://github.com/soumydip/ucoder_insight_core)) `MIT` `JavaScript`
+* [Ucoder Insight](https://insights.ucoder.in) - Privacy-first, cookie-free web analytics SDK for developers. Lightweight, with no required dependencies and offline support via IndexedDB. ([Source Code](https://github.com/soumydip/ucoder_insight_core)) `MIT` `JavaScript`
 * [Beam](https://beam-privacy.com/) - Lightweight, cookie-free web analytics on Cloudflare Workers and D1. No cookies, no fingerprinting, GDPR-compliant by design. Free tier included. ([Source Code](https://github.com/scobb/beam.js)) `©` `SaaS`
 * [Measure.events](https://measure.events) - Privacy-first web analytics with an agent-native API, MCP server, and natural language summaries. Built for AI-forward teams. `©` `SaaS`
 * [OpenPanel](https://openpanel.dev) - OpenPanel is an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting. `©` `Self-Hosted` `EU`
```

<details>
<summary>Evidence and limitations</summary>

<p>The bundle-size figure is outdated. The official homepage now says &#x27;&lt; 8.6KB SDK size (minified + gzipped)&#x27;, while the repo README still says &#x27;Under 7.4kb&#x27;. The other claims hold: cookie-free, no required runtime dependencies (web-vitals is only an optional peer dependency), and offline queueing via IndexedDB (&#x27;IndexDB&#x27; in the entry is a misspelling). Suggest dropping the volatile number. MIT license confirmed in the repo and on npm.</p>

<p>https://insights.ucoder.in — Homepage: &#x27;Analytics Without Cookies or IP Addresses&#x27; and &#x27;&lt; 8.6KB SDK size (minified + gzipped)&#x27;.</p>

<p>https://github.com/soumydip/ucoder_insight_core — README: &#x27;Lightweight SDK — Under 7.4kb (Minified + Gzipped)&#x27;, &#x27;Offline Support — IndexedDB queue, events sent when connection restores&#x27;, &#x27;no required dependencies&#x27;, &#x27;MIT License&#x27;.</p>

<p>https://raw.githubusercontent.com/soumydip/ucoder_insight_core/HEAD/package.json — Package ucoder-insight 1.1.4, license MIT. No &#x27;dependencies&#x27;; peerDependencies has web-vitals marked optional in peerDependenciesMeta. npm latest is 1.1.5, MIT, with no dependencies.</p>

<p>Caveats: The bundle size was not measured; the two official sources disagree.; The product also does error tracking and Web Vitals. These are additions, not corrections.</p>

</details>

<h3>Crazyegg — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -170,7 +170,7 @@
 ## Heatmap analytics
 **[`^        back to top        ^`](#)**
 
-* [Crazyegg](http://www.crazyegg.com/) - a heatmaps only analytics tool. `©` `SaaS`
+* [Crazy Egg](https://www.crazyegg.com/) - heatmaps, session recordings, A/B testing and web analytics. `©` `SaaS`
 * [Inspeclet](https://www.inspectlet.com/) - another web app heatmaps tool. `©` `SaaS`
 * [Mouseflow](http://mouseflow.com/) - live analytics and heatmaps. `©` `SaaS`
 * [Hoot Lens](https://hootlens.com/) - session replay, click heatmaps by device class and broken-click detection, readable by AI coding agents over MCP. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>&#x27;A heatmaps only analytics tool&#x27; is false. Crazy Egg now offers session recordings, A/B testing, surveys, error tracking and web analytics as well as heatmaps. The official brand is &#x27;Crazy Egg&#x27; (two words), and the canonical URL in archived captures is https://www.crazyegg.com/. The section is not alphabetical, so the rename does not affect ordering.</p>

<p>https://web.archive.org/web/20261029092335/https://www.crazyegg.com/ — Archived 2026-10-29. Title: &#x27;Crazy Egg Website — Optimization | Heatmaps, Recordings, Surveys &amp; A/B Testing&#x27;. Text: &#x27;Over 449,000+ websites use Crazy Egg for Heatmaps, Recordings, A/B Testing, Web Analytics, and more.&#x27; The menu lists Heatmap Reports, Session Recordings, Errors Tracking, A/B Testing, Conversion Funnels, Popup Surveys.</p>

<p>Caveats: The live crazyegg.com was unreachable from this environment (proxy 502), so the redirect from http://www.crazyegg.com/ could not be traced. Evidence comes from an archived capture dated 12 days ago.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Inspeclet — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -171,7 +171,7 @@
 **[`^        back to top        ^`](#)**
 
 * [Crazyegg](http://www.crazyegg.com/) - a heatmaps only analytics tool. `©` `SaaS`
-* [Inspeclet](https://www.inspectlet.com/) - another web app heatmaps tool. `©` `SaaS`
+* [Inspectlet](https://www.inspectlet.com/) - another web app heatmaps tool. `©` `SaaS`
 * [Mouseflow](http://mouseflow.com/) - live analytics and heatmaps. `©` `SaaS`
 * [Hoot Lens](https://hootlens.com/) - session replay, click heatmaps by device class and broken-click detection, readable by AI coding agents over MCP. `©` `SaaS`
 * [Session Cam](http://www.sessioncam.com/) - heatmaps analytics tool. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>The catalog misspells the name as &#x27;Inspeclet&#x27;. The official product name is &#x27;Inspectlet&#x27;, matching the listed domain. The description &#x27;another web app heatmaps tool&#x27; is vague but not false: Inspectlet still offers heatmaps alongside session replay, form analytics, A/B testing and error logging. Only the name needs correcting. The section is not alphabetical, so there is no ordering conflict.</p>

<p>https://web.archive.org/web/20261018191813/https://www.inspectlet.com/ — Archived 2026-10-18. Title: &#x27;Inspectlet - Session Replay, Website Heatmaps, Javascript A/B Testing, Feedback Surveys, Error Logging, Form Analytics&#x27;. The features menu includes &#x27;Dynamic Heatmaps See where attention really goes&#x27;.</p>

<p>Caveats: The live inspectlet.com was unreachable from this environment (proxy 502), so an archived capture from about three weeks ago was used.; A fuller description (session replay first) would be an optional improvement, not a correction.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Amazon Pinpoint — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -194,7 +194,6 @@
 
 * [Upsight](http://www.upsight.com/) - mobile app analytics tool for developers. `©` `SaaS`
 * [Appsflyer](http://www.appsflyer.com/) - all-in-one marketing tool with analytics. `©` `SaaS`
-* [Amazon Pinpoint](https://aws.amazon.com/pinpoint/) - Amazons multi-platform, basic mobile analytics tool. `©` `SaaS`
 * [Tapstream](https://tapstream.com/) - user lifecycle analytics. `©` `SaaS`
 * [Honeytracks](https://honeytracks.com/) - mobile app analytics for games. `©` `SaaS`
 * [Apsalar](https://apsalar.com/) - analytics tool for larger app shops. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>AWS officially ended support for Amazon Pinpoint on October 30, 2026. Its engagement features, explicitly including analytics, the Analytics/KPI APIs, and Mobile Analytics putEvents ingestion, are no longer available. Only messaging-channel APIs remain, and those continue under AWS End User Messaging. For event collection and mobile analytics, AWS points to Amazon Kinesis, which is a data-streaming service, not a successor analytics tool. The entry&#x27;s &quot;mobile analytics tool&quot; purpose is therefore gone.</p>

<p>https://aws.amazon.com/pinpoint/ — &quot;On October 30, 2026, AWS will end support for Amazon Pinpoint.&quot; Console and resources (endpoints, segments, campaigns, journeys, and analytics) will no longer be accessible.</p>

<p>https://docs.aws.amazon.com/pinpoint/latest/userguide/migrate.html — &quot;Support for Amazon Pinpoint ended on October 30, 2026… engagement features (endpoints, segments, campaigns, journeys, and analytics) are no longer available.&quot; &quot;Analytics / KPI APIs: Not supported.&quot; &quot;Mobile Analytics customers can no longer ingest events through the putEvents API.&quot; For events collection and mobile analytics, &quot;we recommend to use Amazon Kinesis&quot;.</p>

<p>Caveats: Messaging APIs (push, OTP, SMS for existing customers) still operate, but the catalog entry is about analytics.</p>

</details>

<h3>Session Cam — replace</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Glassbox acquired SessionCam in October 2020. sessioncam.com now 301-redirects to glassbox.com/sessioncam/, a page titled &quot;SessionCam is now part of Glassbox&quot;. The Glassbox platform offers Interaction Maps &amp; Heatmaps and session replay. Glassbox is the officially documented home of the product. However, Glassbox is already listed in General analytics, so the maintainer may prefer removing this line.</p>

<p>https://www.glassbox.com/sessioncam/ — Archived 2026 copy. Title &quot;SessionCam is now part of Glassbox - Glassbox&quot;; nav lists Session Replay, Interaction Maps &amp; Heatmaps, Funnel Analysis, Struggle &amp; Error Analysis.</p>

<p>http://web.archive.org/web/20260422195015id_/https://sessioncam.com/ — Archived 2026-04-22 response: 301 Moved Permanently → https://www.glassbox.com/sessioncam/.</p>

<p>https://www.glassbox.com/news/glassbox-acquires-sessioncam/ — Glassbox newsroom: &quot;Glassbox Acquires SessionCam&quot; (Oct 2020), corroborated by the PR Newswire release (seen in search results).</p>

<p>Blocking questions: Glassbox is already in the catalog under General analytics (https://glassboxdigital.com/). Replacing this line would create a cross-section duplicate, so the maintainer must choose between replace and remove.</p>

<p>Caveats: sessioncam.com was unreachable from this environment (connection refused), so the redirect comes from a Wayback capture dated 2026-04-22.; Glassbox pages were read through archive captures, not live.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Iteratively — replace</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Amplitude officially acquired Iteratively (announced May 12, 2021). iterative.ly now 301-redirects to amplitude.com/customer-data-platform, which is titled &quot;Amplitude Activation&quot;. That page describes a CDP that &quot;proactively improve[s] data quality&quot;. Iteratively&#x27;s tracking-plan and instrumentation features live on in Amplitude&#x27;s data governance tools (Amplitude Data and the Ampli SDK).</p>

<p>https://iterative.ly/ — Live response: HTTP/2 301, location: https://amplitude.com:443/customer-data-platform.</p>

<p>https://amplitude.com/customer-data-platform — Archived 2026 copy. Title &quot;Amplitude Activation | Integrated and Unified Customer Insights&quot;; meta: &quot;The only customer data platform natively integrated with analytics to proactively improve data quality…&quot;.</p>

<p>https://amplitude.com/blog/amplitude-acquires-iteratively — Official Amplitude announcement of the Iteratively acquisition, read via search results only (direct fetch failed): Iteratively described as &quot;a leader in data planning and instrumentation&quot;.</p>

<p>Blocking questions: It is unclear which Amplitude product is Iteratively&#x27;s successor. The domain redirects to Amplitude Activation (CDP), but the tracking-plan features are documented under Amplitude Data / Data Governance.; Amplitude is already listed in Mobile analytics. Replacing could duplicate it, so removing may be preferable.</p>

<p>Caveats: amplitude.com was not directly reachable from this environment; pages were read via Wayback and search summaries.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Apsalar — replace</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -197,7 +197,7 @@
 * [Amazon Pinpoint](https://aws.amazon.com/pinpoint/) - Amazons multi-platform, basic mobile analytics tool. `©` `SaaS`
 * [Tapstream](https://tapstream.com/) - user lifecycle analytics. `©` `SaaS`
 * [Honeytracks](https://honeytracks.com/) - mobile app analytics for games. `©` `SaaS`
-* [Apsalar](https://apsalar.com/) - analytics tool for larger app shops. `©` `SaaS`
+* [Singular](https://www.singular.net/) - marketing analytics and mobile attribution platform (Apsalar merged into Singular). `©` `SaaS`
 * [Roambi](http://www.roambi.com/) - 3-in-1 analytics tool that helps you track analytics, handle mobile app business intelligence, and app reporting. `©` `SaaS`
 * [Appcelerator](http://www.appcelerator.com/platform/appcelerator-analytics/) - entire mobile app marketing suite. `©` `SaaS`
 * [Flurry](http://www.flurry.com/) - pretty much the “industry standard” for mobile app analytics. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Singular officially announced in 2017 that Apsalar had merged into Singular: &quot;Our unified company and product will operate under the Singular brand.&quot; apsalar.com no longer serves content; a Feb 2026 capture shows a Cloudflare error 1001. Singular is the documented successor and, like Apsalar, focuses on mobile attribution and marketing analytics. Singular is not otherwise listed in the catalog.</p>

<p>https://www.singular.net/blog/official%E2%80%8A-%E2%80%8Aapsalar-joins-singular/ — &quot;It&#x27;s Official — Apsalar Joins Singular!&quot;: &quot;Our unified company and product will operate under the Singular brand and will provide our customers with the first marketing analytics platform that is truly end to end.&quot; Nav includes Marketing Analytics and Mobile Attribution.</p>

<p>http://web.archive.org/web/20260227205158id_/http://www.apsalar.com/ — Captured response 2026-02-27: HTTP 409, Cloudflare &quot;error code: 1001&quot; (DNS resolution error); no Apsalar content.</p>

<p>Caveats: singular.net was read via a Wayback capture; direct access was blocked in this environment.; Did not verify Singular&#x27;s current pricing or plan details.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Roambi — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -198,7 +198,6 @@
 * [Tapstream](https://tapstream.com/) - user lifecycle analytics. `©` `SaaS`
 * [Honeytracks](https://honeytracks.com/) - mobile app analytics for games. `©` `SaaS`
 * [Apsalar](https://apsalar.com/) - analytics tool for larger app shops. `©` `SaaS`
-* [Roambi](http://www.roambi.com/) - 3-in-1 analytics tool that helps you track analytics, handle mobile app business intelligence, and app reporting. `©` `SaaS`
 * [Appcelerator](http://www.appcelerator.com/platform/appcelerator-analytics/) - entire mobile app marketing suite. `©` `SaaS`
 * [Flurry](http://www.flurry.com/) - pretty much the “industry standard” for mobile app analytics. `©` `SaaS`
 * [Countly](http://count.ly/) - open source mobile & web application analytics tool. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>SAP acquired Roambi in 2016. By Jan 2022, roambi.com 301-redirected to sap.com/products/roambi.html, and that SAP page returned 404 by Mar 2025. www.roambi.com no longer resolves in DNS. SAP Community material says the Roambi products are &quot;no longer available and supported&quot; and that the mobile capabilities were folded into SAP Analytics Cloud. The listed product no longer exists as a standalone tool.</p>

<p>http://web.archive.org/web/20220126224016id_/http://www.roambi.com/ — Captured 2022-01-26: 301 Moved Permanently → http://www.sap.com/products/roambi.html.</p>

<p>http://web.archive.org/web/20250304090342id_/https://www.sap.com/products/roambi.html — Captured 2025-03-04: HTTP 404, title &quot;Page Not Found | SAP&quot;.</p>

<p>https://community.sap.com/t5/technology-q-a/expiration-date-for-sap-roambi/qaq-p/589777 — SAP answer (via search summary; direct fetch returned 403): Roambi would &quot;converge with SAP Analytics Cloud&quot;; the on-premise version &quot;will sunset by 2020&quot;.</p>

<p>Caveats: SAP&#x27;s statements were read through search summaries because community.sap.com returned 403. The exact end date for Roambi Cloud was not found.; SAP Analytics Cloud could be considered a successor, but it is a general BI suite, so replacement was not proposed.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Appcelerator — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -199,7 +199,6 @@
 * [Honeytracks](https://honeytracks.com/) - mobile app analytics for games. `©` `SaaS`
 * [Apsalar](https://apsalar.com/) - analytics tool for larger app shops. `©` `SaaS`
 * [Roambi](http://www.roambi.com/) - 3-in-1 analytics tool that helps you track analytics, handle mobile app business intelligence, and app reporting. `©` `SaaS`
-* [Appcelerator](http://www.appcelerator.com/platform/appcelerator-analytics/) - entire mobile app marketing suite. `©` `SaaS`
 * [Flurry](http://www.flurry.com/) - pretty much the “industry standard” for mobile app analytics. `©` `SaaS`
 * [Countly](http://count.ly/) - open source mobile & web application analytics tool. `©` `SaaS`
 * [Playtomatic](http://playtomic.org/) - mobile app open source analytics tool for games. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Axway officially ended Appcelerator Mobile Analytics, Crash Analytics and the Dashboard for Mobile Apps on March 1, 2022, and the analytics service stopped. The listed page now returns 404 (&quot;Unknown site&quot;). The open-source Titanium SDK continues under TiDev, but that does not carry on the analytics service.</p>

<p>https://blog.axway.com/product-insights/discontinued/appcelerator/changes-to-application-development-services — Official Axway post: support ended March 1, 2022 for &quot;Mobile Analytics, Crash Analytics, App Preview, Appcelerator Studio, Dashboard for Mobile Apps&quot;; Mobile Backend Services ended September 1, 2022.</p>

<p>http://www.appcelerator.com/platform/appcelerator-analytics/ — HTTP/1.1 404 Unknown site.</p>

<p>Caveats: The entry&#x27;s description (&quot;entire mobile app marketing suite&quot;) predates the shutdown. No successor analytics product was documented.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Flurry — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -200,7 +200,6 @@
 * [Apsalar](https://apsalar.com/) - analytics tool for larger app shops. `©` `SaaS`
 * [Roambi](http://www.roambi.com/) - 3-in-1 analytics tool that helps you track analytics, handle mobile app business intelligence, and app reporting. `©` `SaaS`
 * [Appcelerator](http://www.appcelerator.com/platform/appcelerator-analytics/) - entire mobile app marketing suite. `©` `SaaS`
-* [Flurry](http://www.flurry.com/) - pretty much the “industry standard” for mobile app analytics. `©` `SaaS`
 * [Countly](http://count.ly/) - open source mobile & web application analytics tool. `©` `SaaS`
 * [Playtomatic](http://playtomic.org/) - mobile app open source analytics tool for games. `©` `SaaS`
 * [Capptain](http://www.capptain.com/) - real-time analytics tool with segmentation and push. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Flurry&#x27;s official blog says Flurry Mobile Analytics, including SDK and Analytics UI, would sunset on March 15, 2024. It pointed customers to third-party alternatives (PostHog, Mixpanel, GameAnalytics), not an official successor. The &quot;industry standard&quot; analytics service no longer operates.</p>

<p>https://www.flurry.com/blog/flurry-sunsetting/ — Archived 2026-05-06 copy: &quot;Flurry Mobile Analytics, including SDK and Analytics UI, will sunset on March 15, 2024.&quot; Post dated 2024-02-15 recommends transitioning to PostHog, Mixpanel and GameAnalytics.</p>

<p>https://news.ycombinator.com/item?id=38729448 — HN item (Dec 2023) titled &quot;Flurry Mobile Analytics will sunset on March 15, 2024&quot;, linking to flurry.com.</p>

<p>Caveats: developer.yahoo.com/flurry/ still renders documentation navigation without a sunset banner. This looks like a stale page, not evidence the service is live.; flurry.com was unreachable directly from this environment.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Countly — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -201,7 +201,7 @@
 * [Roambi](http://www.roambi.com/) - 3-in-1 analytics tool that helps you track analytics, handle mobile app business intelligence, and app reporting. `©` `SaaS`
 * [Appcelerator](http://www.appcelerator.com/platform/appcelerator-analytics/) - entire mobile app marketing suite. `©` `SaaS`
 * [Flurry](http://www.flurry.com/) - pretty much the “industry standard” for mobile app analytics. `©` `SaaS`
-* [Countly](http://count.ly/) - open source mobile & web application analytics tool. `©` `SaaS`
+* [Countly](https://countly.com/) - open source mobile & web application analytics tool. `©` `SaaS`
 * [Playtomatic](http://playtomic.org/) - mobile app open source analytics tool for games. `©` `SaaS`
 * [Capptain](http://www.capptain.com/) - real-time analytics tool with segmentation and push. `©` `SaaS`
 * [Amplitude](https://amplitude.com/) - real-time mobile analytics with all data provided in redshift. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Countly is still an open-source (AGPL-3.0, modified §7) product analytics platform for mobile, web and desktop apps. The description is accurate. count.ly now 301-redirects to countly.com (2026 capture), and the official GitHub repo links to countly.com, so the canonical URL should change.</p>

<p>http://web.archive.org/web/20260912002214id_/https://count.ly/ — Captured 2026-09-12: 301 Moved Permanently → https://countly.com/.</p>

<p>https://github.com/Countly/countly-server — Not archived; describes a &quot;privacy-first … analytics and engagement platform … from desktop and mobile to IoT&quot;; tracks mobile, web and desktop apps; license AGPL-3.0 with modified Section 7; website countly.com.</p>

<p>Caveats: The `©` `SaaS` tags look inaccurate for an AGPL-licensed, self-hostable project (another Countly entry in General analytics uses `AGPL-3.0` `Javascript`). Tags are metadata outside this description review.; Countly is listed twice in the catalog (General analytics and Mobile analytics).</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Playtomatic — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -202,7 +202,6 @@
 * [Appcelerator](http://www.appcelerator.com/platform/appcelerator-analytics/) - entire mobile app marketing suite. `©` `SaaS`
 * [Flurry](http://www.flurry.com/) - pretty much the “industry standard” for mobile app analytics. `©` `SaaS`
 * [Countly](http://count.ly/) - open source mobile & web application analytics tool. `©` `SaaS`
-* [Playtomatic](http://playtomic.org/) - mobile app open source analytics tool for games. `©` `SaaS`
 * [Capptain](http://www.capptain.com/) - real-time analytics tool with segmentation and push. `©` `SaaS`
 * [Amplitude](https://amplitude.com/) - real-time mobile analytics with all data provided in redshift. `©` `SaaS`
 * [Appsee](http://www.appsee.com/) - mobile app analytics platform automatically tracks all users' interactions in your app `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed site playtomic.org (correct name &quot;Playtomic&quot;; the entry misspells it &quot;Playtomatic&quot;) is the open-source successor to the original Playtomic service. Its official source describes only leaderboards, achievements, player levels, gamevars, GeoIP and newsletter subscription, with no analytics. The original hosted analytics service shut down, and the analytics backend was never open-sourced. The domain now returns HTTP 520. The org&#x27;s repos were last updated in 2015. The &quot;open source analytics tool for games&quot; claim is unsupported by the official project.</p>

<p>https://raw.githubusercontent.com/playtomic/playtomic.org/master/index.html — Official site source: &quot;Playtomic: open source leaderboards, achievements, user created content and dynamic content for games… Playtomic.org is the new home of the tools once provided by Playtomic - achievements, leaderboards, player levels, gamevars, geoip and in-game newsletter subscription&quot;. Analytics is not listed.</p>

<p>https://github.com/playtomic — 10 repos (apiserver, gameapi-* clients, playtomic.org site); last updates 2013–2015.</p>

<p>https://playtomic.org/ — http→https 301, then HTTP/2 520 (Cloudflare origin error).</p>

<p>https://www.gamedev.net/forums/topic/643319-open-sourcing-playtomic/ — Search summary (not opened directly): founder Ben Lowry writes that Playtomic &quot;shut down&quot; and the open-sourced release covered leaderboards, achievements, user content, dynamic content and geoip.</p>

<p>Caveats: The 520 may be temporary, but removal rests on the official site source showing no analytics, not on reachability.; Third-party mirrors of the old analytics SDKs exist but called the defunct hosted servers.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Firebase — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -210,7 +210,7 @@
 * [Localytics](http://www.localytics.com/) - fast and beautiful real-time mobile analytics platform with in-app and push. `©` `SaaS`
 * [GameAnalytics](http://www.gameanalytics.com/) - leading game analytics platform. `©` `SaaS`
 * [Swrve](https://swrve.com) - mobile analytics with segmentation, push, A/B testing and rich messaging `©` `SaaS`
-* [Firebase](https://firebase.google.com/features/) - a free and unlimited analytics solution for android and iOS `©` `SaaS`
+* [Firebase](https://firebase.google.com/products/analytics) - a free and unlimited analytics solution for android and iOS `©` `SaaS`
 * [Liquid](https://onliquid.com/) - real-time mobile analytics, personalization, multivariate testing, audience segmentation and push. `©` `SaaS`
 * [OpenPanel](https://openpanel.dev) - OpenPanel is an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting. `©` `Self-Hosted` `EU`
 * [Apparent](https://apparent.fyi/) - mobile app analytics for iOS and Android makers: live activity from its own SDK plus App Store Connect, Google Play and RevenueCat, all apps on one page. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL https://firebase.google.com/features/ now redirects to a generic Firebase products page (/products-build) that is not about analytics. The official Google Analytics for Firebase product page exists at /products/analytics and supports the description: the product is free and gives unlimited reporting, with a 500-distinct-event cap, for iOS and Android among other platforms. Only the URL needs to change. The description stays as it is.</p>

<p>https://firebase.google.com/features/ — Running curl with redirects followed lands on https://firebase.google.com/products-build (HTTP 200). That is a general Build-products listing, not an analytics page.</p>

<p>https://firebase.google.com/products/analytics — Page title: &#x27;Google Analytics | Get unlimited app analytics | Firebase&#x27;. It says &#x27;An app measurement solution, available at no charge&#x27; and &#x27;Google Analytics provides free, unlimited reporting on up to 500 distinct events&#x27;, and lists iOS, Android, web, C++ and Unity platforms.</p>

<p>https://firebase.google.com/docs/analytics — The docs call it &#x27;an unlimited analytics solution available at no charge&#x27; and list iOS, Android, Web, Flutter, Unity and C++.</p>

<p>Caveats: The &#x27;unlimited&#x27; wording has a documented limit of 500 distinct event types. The current description is still in line with Google&#x27;s own wording.; The description mentions only Android and iOS. Other platforms are also supported, but the entry makes no &#x27;only&#x27; claim, so this is optional.</p>

</details>

<h3>Priori Data — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -221,7 +221,6 @@
 * [Appfigures](http://appfigures.com/) - app store analytics to track sales, reviews and rankings with an API. `©` `SaaS`
 * [Appannie](http://www.appannie.com/) - track your app data from iTunes, Google Play & Amazon. `©` `SaaS`
 * [Distimo](http://www.distimo.com/) - free app store analytics (acquired by [Appannie](http://www.appannie.com/)). `©` `SaaS`
-* [Priori Data](https://prioridata.com/) - track and benchmark the performance of apps on Apple- and Play store. `©` `SaaS`
 * [Asking Point](http://www.askingpoint.com/mobile-app-rating-widget) - track your mobile app user ratings. `©` `SaaS`
 * [Apptrace](http://www.apptrace.com/) - fast and free app store analytics platform. `©` `SaaS`
 * [AdMapix](https://www.admapix.com/) - AI ad intelligence and app market research platform for searching competitor creatives and tracking app rankings, downloads, and revenue across markets. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>prioridata.com no longer hosts an app tracking or benchmarking product. It is now an app-marketing content site with reports, guides and tool comparisons, run by one person. The site&#x27;s own About page says the original Berlin company that sold app store intelligence was acquired in 2018, its product was retired in 2020, and the current site is not affiliated with that company. The described service is no longer at the listed URL.</p>

<p>https://prioridata.com/ — Homepage: &#x27;App marketing insights, backed by data. Market data, tool comparisons and guides for people who build and market apps.&#x27; It has no app tracking or benchmarking product and no sign-in.</p>

<p>https://prioridata.com/about/ — &#x27;The name was first used by a Berlin company founded in 2013 that sold app store intelligence... That company was acquired in 2018 and its product was retired in 2020. This site has been run independently since 2023 and is not affiliated with the original company or its successors.&#x27;</p>

<p>Caveats: The statement that the product was retired comes from the current, unaffiliated domain operator, not from the original company or its acquirer. I did not find an officially documented successor product, so I am not proposing a replace.; The current site could arguably be judged as a separate content resource, but that would be a new entry, not this one.</p>

</details>

<h3>Capptain — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -203,7 +203,6 @@
 * [Flurry](http://www.flurry.com/) - pretty much the “industry standard” for mobile app analytics. `©` `SaaS`
 * [Countly](http://count.ly/) - open source mobile & web application analytics tool. `©` `SaaS`
 * [Playtomatic](http://playtomic.org/) - mobile app open source analytics tool for games. `©` `SaaS`
-* [Capptain](http://www.capptain.com/) - real-time analytics tool with segmentation and push. `©` `SaaS`
 * [Amplitude](https://amplitude.com/) - real-time mobile analytics with all data provided in redshift. `©` `SaaS`
 * [Appsee](http://www.appsee.com/) - mobile app analytics platform automatically tracks all users' interactions in your app `©` `SaaS`
 * [Mixpanel](https://mixpanel.com/) - fully featured mobile analytics platform with segmentation and push. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Microsoft acquired Capptain in 2014, and it became Azure Mobile Engagement. Microsoft&#x27;s official lifecycle page shows Azure Mobile Engagement was retired on 4/1/2018. The last archived capptain.com content is the acquisition notice that redirects visitors to Azure Mobile Engagement. The listed service no longer exists, and there is no live successor product.</p>

<p>https://web.archive.org/web/20161118233931/http://capptain.com/ — &#x27;Capptain has been acquired by Microsoft... Rediscover us as Mobile Engagement on Azure&#x27;. The Wayback Machine has no 200 capture of capptain.com after 2016, and a 2023 capture redirects.</p>

<p>https://learn.microsoft.com/en-us/lifecycle/products/azure-mobile-engagement — Microsoft Lifecycle: Azure Mobile Engagement start date 10/1/2015, retirement date 4/1/2018.</p>

<p>https://github.com/Azure/azure-mobile-engagement-capptain-cordova — Search results show the official Azure repo states &#x27;Azure Capptain / Mobile Engagement services have been retired and are no longer available&#x27;. I saw this in search results and did not open the repo directly.</p>

<p>Caveats: My client could not reach capptain.com directly (proxy 502), so I used Wayback captures.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Amplitude — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -204,7 +204,7 @@
 * [Countly](http://count.ly/) - open source mobile & web application analytics tool. `©` `SaaS`
 * [Playtomatic](http://playtomic.org/) - mobile app open source analytics tool for games. `©` `SaaS`
 * [Capptain](http://www.capptain.com/) - real-time analytics tool with segmentation and push. `©` `SaaS`
-* [Amplitude](https://amplitude.com/) - real-time mobile analytics with all data provided in redshift. `©` `SaaS`
+* [Amplitude](https://amplitude.com/) - product analytics for mobile and web apps, with raw data export to warehouses such as Snowflake and Redshift. `©` `SaaS`
 * [Appsee](http://www.appsee.com/) - mobile app analytics platform automatically tracks all users' interactions in your app `©` `SaaS`
 * [Mixpanel](https://mixpanel.com/) - fully featured mobile analytics platform with segmentation and push. `©` `SaaS`
 * [Localytics](http://www.localytics.com/) - fast and beautiful real-time mobile analytics platform with in-app and push. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Amplitude is still a relevant product and digital analytics platform, but the claim &#x27;all data provided in redshift&#x27; is out of date. Amplitude&#x27;s own blog says it moved its SQL Query offering from Redshift to Snowflake in 2017. Redshift is now one of several warehouse export destinations. The platform also covers web, so &#x27;mobile&#x27; alone is narrow but not false.</p>

<p>https://web.archive.org/web/2026/https://amplitude.com/blog/why-we-chose-redshift — Update note on the post: &#x27;In 2017, Amplitude migrated our SQL Query option from Redshift to Snowflake.&#x27;</p>

<p>https://amplitude.com/docs/data/destination-catalog/amazon-redshift — Search results show Redshift is documented as a Warehouse Destination for exports under Catalog &gt; Destinations. I could not reach this page directly.</p>

<p>https://web.archive.org/web/20261101/https://amplitude.com/ — Nov 2026 capture lists Product Analytics, Marketing Analytics, Session Replay, Experimentation and Data/Integrations. Amplitude is positioned as a digital analytics platform.</p>

<p>Caveats: My client could not reach amplitude.com directly (proxy/connection failure). I relied on Wayback captures and search snippets of the docs.; The proposed wording avoids listing every warehouse.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Appsee — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -205,7 +205,6 @@
 * [Playtomatic](http://playtomic.org/) - mobile app open source analytics tool for games. `©` `SaaS`
 * [Capptain](http://www.capptain.com/) - real-time analytics tool with segmentation and push. `©` `SaaS`
 * [Amplitude](https://amplitude.com/) - real-time mobile analytics with all data provided in redshift. `©` `SaaS`
-* [Appsee](http://www.appsee.com/) - mobile app analytics platform automatically tracks all users' interactions in your app `©` `SaaS`
 * [Mixpanel](https://mixpanel.com/) - fully featured mobile analytics platform with segmentation and push. `©` `SaaS`
 * [Localytics](http://www.localytics.com/) - fast and beautiful real-time mobile analytics platform with in-app and push. `©` `SaaS`
 * [GameAnalytics](http://www.gameanalytics.com/) - leading game analytics platform. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Appsee&#x27;s own site announced in 2019 that ServiceNow had acquired its platform. ServiceNow took the IP and team but not the customers, and the standalone service was wound down. By 2024 appsee.com showed only an &#x27;AppSee Coming Soon&#x27; placeholder, with no analytics product, SDK or login. The listed service is no longer offered at this URL.</p>

<p>https://web.archive.org/web/20191201/https://www.appsee.com/ — 2019 capture of the official site: &#x27;Appsee&#x27;s In-App Mobile Analytics Platform has been acquired by ServiceNow!&#x27;</p>

<p>https://web.archive.org/web/20240918042611/https://appsee.com/ — Latest capture (Sep 2024) shows only &#x27;AppSee Coming Soon&#x27;. There is no product.</p>

<p>https://techcrunch.com/2019/05/13/servicenow-acquihires-mobile-analytics-startup-appsee — From search results: ServiceNow acquired Appsee&#x27;s IP and personnel, not its customers, and Appsee was expected to wind down its business within about 12 months. This is third-party reporting that I read through a search summary.</p>

<p>Caveats: My client could not reach appsee.com live (proxy 502). The current state comes from Wayback captures up to Sep 2024.; I did not read an official ServiceNow statement that explicitly says the service shut down. The wind-down comes from press coverage. The official site&#x27;s own acquisition notice and later placeholder show the product is no longer offered.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Mixpanel — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -206,7 +206,7 @@
 * [Capptain](http://www.capptain.com/) - real-time analytics tool with segmentation and push. `©` `SaaS`
 * [Amplitude](https://amplitude.com/) - real-time mobile analytics with all data provided in redshift. `©` `SaaS`
 * [Appsee](http://www.appsee.com/) - mobile app analytics platform automatically tracks all users' interactions in your app `©` `SaaS`
-* [Mixpanel](https://mixpanel.com/) - fully featured mobile analytics platform with segmentation and push. `©` `SaaS`
+* [Mixpanel](https://mixpanel.com/) - product analytics platform for mobile and web apps with segmentation, funnels, retention and session replay. `©` `SaaS`
 * [Localytics](http://www.localytics.com/) - fast and beautiful real-time mobile analytics platform with in-app and push. `©` `SaaS`
 * [GameAnalytics](http://www.gameanalytics.com/) - leading game analytics platform. `©` `SaaS`
 * [Swrve](https://swrve.com) - mobile analytics with segmentation, push, A/B testing and rich messaging `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Mixpanel is still a relevant product analytics platform, but the &#x27;push&#x27; claim is false. Mixpanel officially sunset its Messages &amp; Experiments add-on, which provided push and email messaging, on Jan 1, 2022, and removed it from the Android SDK in v6.0.0. Segmentation and analytics remain, and Session Replay and Experiments are current features.</p>

<p>https://web.archive.org/web/2026/https://mixpanel.com/blog/why-were-sunsetting-messaging-and-experiments/ — Official blog: &#x27;on Jan 1, 2022, we&#x27;ll remove the Messages &amp; Experiments feature from Mixpanel&#x27;. That add-on was used &#x27;to send emails and push notifications, and conduct mobile A/B tests&#x27;.</p>

<p>https://github.com/mixpanel/mixpanel-android/wiki/Changelog — v6.0.0 (2022-01-02): &#x27;Remove Messages &amp; Experiments feature&#x27;.</p>

<p>https://web.archive.org/web/20261101/https://mixpanel.com/ — Nov 2026 capture: &#x27;Product Intelligence Platform for the AI Era&#x27;. Lists Mixpanel AI, Analytics, Session Replay, Experiments and Metric Trees.</p>

<p>Caveats: My client could not reach mixpanel.com live. I relied on Wayback captures from 2026.; The proposed wording avoids volatile feature lists beyond the core capabilities.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Swrve — replace</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>swrve.com now redirects with a 301 to messagegears.com/swrve/, a page titled &#x27;Swrve Is Now MessageGears&#x27;. An archived Feb 2025 Swrve homepage announced &#x27;MessageGears acquires mobile app marketing leader Swrve&#x27;. MessageGears is the officially documented continuation, offering segmentation, real-time triggers, mobile push and in-app messaging, and experiments. However, it is positioned as cross-channel marketing and messaging rather than mobile analytics, so its fit in this section is uncertain.</p>

<p>https://web.archive.org/web/20251222124752/https://www.swrve.com/ — The Dec 2025 capture returns a 301 to https://messagegears.com:443/swrve/.</p>

<p>https://web.archive.org/web/20261101/https://messagegears.com/swrve/ — Title: &#x27;Swrve Is Now MessageGears | Explore Real-Time Messaging&#x27;. Products listed: Segmentation, Reverse ETL, AI decisioning, Real-time triggers, Messaging (Email, Mobile, SMS, Web), Personalization, Experiments.</p>

<p>https://web.archive.org/web/20250214144147/https://www.swrve.com/ — Feb 2025 Swrve homepage banner: &#x27;MessageGears acquires mobile app marketing leader Swrve&#x27;. At that time the site still listed Analytics, Segmentation, Push and In-App.</p>

<p>Blocking questions: Section fit is unclear. MessageGears is mainly a marketing and messaging platform, and I found no clear current mobile-analytics offering. The maintainer may prefer to remove the entry or move it rather than replace it in &#x27;Mobile analytics&#x27;.; I could not read the live MessageGears site (403), so the current product wording comes only from a Nov 2026 Wayback capture.</p>

<p>Caveats: My client could not reach swrve.com or messagegears.com live (proxy 502 / HTTP 403). The evidence is from Wayback captures.; Did not check whether the existing Swrve SDKs and dashboards still operate for legacy customers.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Liquid — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -211,7 +211,6 @@
 * [GameAnalytics](http://www.gameanalytics.com/) - leading game analytics platform. `©` `SaaS`
 * [Swrve](https://swrve.com) - mobile analytics with segmentation, push, A/B testing and rich messaging `©` `SaaS`
 * [Firebase](https://firebase.google.com/features/) - a free and unlimited analytics solution for android and iOS `©` `SaaS`
-* [Liquid](https://onliquid.com/) - real-time mobile analytics, personalization, multivariate testing, audience segmentation and push. `©` `SaaS`
 * [OpenPanel](https://openpanel.dev) - OpenPanel is an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting. `©` `Self-Hosted` `EU`
 * [Apparent](https://apparent.fyi/) - mobile app analytics for iOS and Android makers: live activity from its own SDK plus App Store Connect, Google Play and RevenueCat, all apps on one page. `©` `SaaS`
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed domain no longer serves the Liquid product. The latest Wayback captures of onliquid.com (2025) show an Indonesian gambling/slot spam page (&#x27;MPO999... Slot Gacor&#x27;), so the domain has been taken over by an unrelated party. Third-party company databases describe Liquid Data Intelligence as no longer active. Keeping the link sends readers to unrelated and possibly harmful content.</p>

<p>https://web.archive.org/web/20250830142728/https://onliquid.com/ — Aug 2025 capture: &#x27;MPO999 ⎊ Raja Situs Slot Gacor Hari Ini Mudah Panen Maxwin 2025&#x27;. Gambling/slot spam with no analytics product.</p>

<p>https://tracxn.com/d/companies/liquid/__Ku4W9p9HdrVljWEvMcrOYx0XgPUfaitPaL_vUZ7S2nI — From search results: Tracxn lists Liquid (Lisbon, founded 2014) as deadpooled and &#x27;not active anymore&#x27;. This is a third-party source read through a search summary.</p>

<p>Caveats: My client could not reach onliquid.com live. The current state comes from 2025 Wayback captures.; I found no official shutdown statement from the original company. The removal rests on the listed URL now serving unrelated content.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Appannie — replace</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>App Annie renamed itself data.ai in 2022, and Sensor Tower acquired data.ai in March 2024. appannie.com now redirects to data.ai, and data.ai&#x27;s login page reads &#x27;We&#x27;ve Been Acquired by Sensor Tower&#x27;, with the footer &#x27;© 2026 data.ai, a Sensor Tower company&#x27;. Sensor Tower&#x27;s official announcement says it added data.ai&#x27;s product, input data and team. Sensor Tower is not currently in the catalog.</p>

<p>https://web.archive.org/web/20261008113725/https://www.appannie.com/ — Oct 2026 capture returns a 301 from www.appannie.com to https://www.data.ai/.</p>

<p>https://web.archive.org/web/20261101/https://www.data.ai/account/login/ — &#x27;Login | data.ai — We&#x27;ve Been Acquired by Sensor Tower... © 2026 data.ai, a Sensor Tower company.&#x27;</p>

<p>https://sensortower.com/blog/data-ai-joins-sensor-tower — Sensor Tower (Mar 2024): &#x27;we&#x27;ve acquired marketing intelligence platform data.ai, formerly known as App Annie. The addition of data.ai&#x27;s product, input data, and team...&#x27;</p>

<p>https://sensortower.com/ — Live: &#x27;Digital Intelligence &amp; App Data Analysis by Sensor Tower&#x27;. Covers &#x27;app downloads and engagement&#x27; and omnichannel ads.</p>

<p>Blocking questions: I found no official Sensor Tower document that explicitly names its platform as the migration path for App Annie/data.ai users. The successor relationship rests on the acquisition announcement and the data.ai login notice. The maintainer should confirm this counts as a documented successor.; The Distimo entry (id 223) embeds an inline link to appannie.com. That prose would need a coordinated manual edit.</p>

<p>Caveats: My client could not reach appannie.com live (proxy 502). The redirect chain comes from Wayback.; Sensor Tower is the acquirer and successor platform. The replacement description focuses on store data rather than private App Store Connect connections, which App Annie&#x27;s old &#x27;App Analytics&#x27; offered.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Distimo — remove</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Distimo&#x27;s own site stated &#x27;Distimo is now part of App Annie&#x27; from 2014 to 2016, and redirected visitors to App Annie products. No standalone free Distimo analytics service exists. Later captures (2023–2025) show only 301/503 responses. The acquirer, App Annie, has itself since become data.ai and been absorbed into Sensor Tower. This is a complex entry with an inline Appannie link, so removing it is a manual edit.</p>

<p>https://web.archive.org/web/20161228103030/http://distimo.com/ — Dec 2016 capture: &#x27;Distimo | App Annie... Distimo is now part of App Annie&#x27;. The page only promotes App Annie sign-up.</p>

<p>https://web.archive.org/web/20250925185301/https://distimo.com/ — Latest CDX entries (2023–2025) are 301 redirects or a 503. There is no Distimo product content.</p>

<p>https://web.archive.org/web/20261101/https://www.data.ai/account/login/ — Distimo&#x27;s acquirer App Annie (now data.ai) shows &#x27;We&#x27;ve Been Acquired by Sensor Tower&#x27;.</p>

<p>Caveats: My client could not reach distimo.com live (proxy 502). I could not resolve the current redirect target.; The entry already records the acquisition, so a maintainer might instead keep it as a historical note. The text still describes &#x27;free app store analytics&#x27; as if it were current.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Apptrace — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -223,7 +223,6 @@
 * [Distimo](http://www.distimo.com/) - free app store analytics (acquired by [Appannie](http://www.appannie.com/)). `©` `SaaS`
 * [Priori Data](https://prioridata.com/) - track and benchmark the performance of apps on Apple- and Play store. `©` `SaaS`
 * [Asking Point](http://www.askingpoint.com/mobile-app-rating-widget) - track your mobile app user ratings. `©` `SaaS`
-* [Apptrace](http://www.apptrace.com/) - fast and free app store analytics platform. `©` `SaaS`
 * [AdMapix](https://www.admapix.com/) - AI ad intelligence and app market research platform for searching competitor creatives and tracking app rankings, downloads, and revenue across markets. `©` `SaaS`
 * [AsoBeast](https://asobeast.com) - Open-source ASO tool and keyword rank tracker for the App Store and Google Play: daily rankings, competitors, reviews and an MCP server. ([Source Code](https://github.com/AsoBeast/asobeast)) `AGPL-3.0` `TypeScript` `Self-Hosted` `SaaS`
 
```

<details>
<summary>Evidence and limitations</summary>

<p>Apptrace&#x27;s official site announced it would discontinue support as of 28 February 2022 and pointed users to Adjust. Since then, www.apptrace.com returns 404 in captures through Oct 2026. The listed free app store analytics service no longer exists. Adjust is already in the catalog under Attribution tracking and is not a like-for-like successor.</p>

<p>https://web.archive.org/web/20220223094339/https://apptrace.com/ — Feb 2022 capture: &#x27;As of 28 February 2022, we will discontinue support for AppTrace.com. Interested in an analytics platform trusted by 50,000 apps? Visit Adjust.com.&#x27;</p>

<p>https://web.archive.org/web/20261002053134/https://www.apptrace.com/ — In Oct 2026 http://www.apptrace.com redirects with a 301 to https://www.apptrace.com/, which returns HTTP 404.</p>

<p>Caveats: My client could not reach apptrace.com live (proxy 502). The current state comes from Wayback captures as of Oct 2026.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Brandwatch — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -247,7 +247,7 @@
 
 Often there is no clear differentiation between social media management and analytics as most the tools provide analytics.
 
-* [Brandwatch](http://www.brandwatch.com/) - Social media monitoring and analytics. `©` `SaaS`
+* [Brandwatch](https://www.brandwatch.com/) - Social media monitoring and analytics. `©` `SaaS`
 * [Falconsocial](http://www.falconsocial.com/) - communications platform built on social media with analytics. `©` `SaaS`
 * [Quintly](https://www.quintly.com/) - web-based tool to help you track, benchmark and optimize your social media performance. `©` `SaaS`
 * [Buffer](https://bufferapp.com/) - Social media publishing and analytics platform. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>The description (social media monitoring and analytics) still fits Brandwatch&#x27;s consumer intelligence and social listening suite. The listed http://www.brandwatch.com/ redirects to https://www.brandwatch.com/, so only the URL scheme needs correcting.</p>

<p>https://www.brandwatch.com/ — http://www.brandwatch.com/ redirects here (HTTP 200). The title is &#x27;Social Media Management &amp; Consumer Intelligence | Brandwatch&#x27;. The suite lists Consumer Intelligence, Search Intelligence, Social Media Management and Influencer Marketing.</p>

<p>Caveats: This is a URL-scheme correction only. The description is not changed.</p>

</details>

<h3>Quintly — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>quintly.com is live and still a social media analytics and benchmarking tool, so the description stays accurate. An official announcement on the same site says quintly &#x27;officially becomes Facelift Data Studio&#x27; and remains a standalone product. The listed name is outdated.</p>

<p>https://www.quintly.com/ — HTTP 200. Banner reads &#x27;ANNOUNCEMENT: QUINTLY BECOMES FACELIFT DATA STUDIO&#x27; and &#x27;quintly officially becomes Facelift Data Studio&#x27;. Features: &#x27;Analytics: Track, benchmark and optimize your social media.&#x27;</p>

<p>https://www.quintly.com/quintly-becomes-facelift-data-studio — Says &#x27;With our next major update, quintly will become Facelift Data Studio&#x27; and &#x27;Facelift Data Studio will remain a standalone product, and all existing contracts will remain unchanged.&#x27;</p>

<p>https://help.facelift-cloud.com/en/collections/6890662-facelift-data-studio — Linked from quintly.com as the Facelift Data Studio help collection (link found in page markup; not fetched).</p>

<p>Blocking questions: The site still mixes &#x27;quintly&#x27; branding (page title, nav). I found no separate canonical Facelift Data Studio product URL. The maintainer should confirm the rename has fully taken effect and that quintly.com remains the canonical URL.</p>

<p>Caveats: The README has no alphabetical ordering, so a rename has no ordering impact.</p>

</details>

<h3>Buffer — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -250,7 +250,7 @@
 * [Brandwatch](http://www.brandwatch.com/) - Social media monitoring and analytics. `©` `SaaS`
 * [Falconsocial](http://www.falconsocial.com/) - communications platform built on social media with analytics. `©` `SaaS`
 * [Quintly](https://www.quintly.com/) - web-based tool to help you track, benchmark and optimize your social media performance. `©` `SaaS`
-* [Buffer](https://bufferapp.com/) - Social media publishing and analytics platform. `©` `SaaS`
+* [Buffer](https://buffer.com/) - Social media publishing and analytics platform. `©` `SaaS`
 * [Topsy](http://topsy.com/) - Social analytics tool with search. `©` `SaaS`
 * [SocialBlade](http://socialblade.com/) - premiere YouTube statistics tracking. `©` `SaaS`
 * [Open Channel Stats](https://openchannelstats.com) - Browse real YouTube channels' full owner analytics — retention, CTR, traffic sources — published by the creators themselves, not estimated; connect your own free to compare. Daily refresh; each public channel exports as a documented SQLite file. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>https://bufferapp.com/ redirects to https://buffer.com/. Buffer still offers publishing plus analytics (&#x27;Insights&#x27;), so the description is accurate and only the URL needs updating to the canonical domain.</p>

<p>https://buffer.com/ — bufferapp.com redirects here (HTTP 200). Title &#x27;Buffer: Social media management for everyone&#x27;. Features include Publish (&#x27;Plan and schedule your content&#x27;) and Insights (&#x27;Understand your performance and what to post next&#x27;).</p>

<p>Caveats: The name &#x27;Buffer&#x27; is unchanged.</p>

</details>

<h3>SocialBlade — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -252,7 +252,7 @@
 * [Quintly](https://www.quintly.com/) - web-based tool to help you track, benchmark and optimize your social media performance. `©` `SaaS`
 * [Buffer](https://bufferapp.com/) - Social media publishing and analytics platform. `©` `SaaS`
 * [Topsy](http://topsy.com/) - Social analytics tool with search. `©` `SaaS`
-* [SocialBlade](http://socialblade.com/) - premiere YouTube statistics tracking. `©` `SaaS`
+* [SocialBlade](https://socialblade.com/) - premiere YouTube statistics tracking. `©` `SaaS`
 * [Open Channel Stats](https://openchannelstats.com) - Browse real YouTube channels' full owner analytics — retention, CTR, traffic sources — published by the creators themselves, not estimated; connect your own free to compare. Daily refresh; each public channel exports as a documented SQLite file. `©` `SaaS`
 * [Hootsuite](https://hootsuite.com/) - Social media management dashbaord. `©` `SaaS`
 * [SocialBu](https://socialbu.com/) - AI-powered social media management and analytics platform with scheduling, monitoring, and automation. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>SocialBlade is live and still tracks YouTube statistics, so the non-exclusive description remains accurate even though it now also covers TikTok, Twitch, Instagram and Facebook. The listed http URL redirects to HTTPS.</p>

<p>https://socialblade.com/ — http://socialblade.com/ redirects here (HTTP 200). Title &#x27;YouTube, Instagram, Twitch, TikTok, and more Statistics - SocialBlade.com&#x27;. Says it &#x27;tracks daily statistics and growth&#x27; for over 183M creators, including 90M on YouTube.</p>

<p>Caveats: The maintainer may optionally broaden the wording to multi-platform creator statistics. That is not a factual correction.</p>

</details>

<h3>Hootsuite — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -254,7 +254,7 @@
 * [Topsy](http://topsy.com/) - Social analytics tool with search. `©` `SaaS`
 * [SocialBlade](http://socialblade.com/) - premiere YouTube statistics tracking. `©` `SaaS`
 * [Open Channel Stats](https://openchannelstats.com) - Browse real YouTube channels' full owner analytics — retention, CTR, traffic sources — published by the creators themselves, not estimated; connect your own free to compare. Daily refresh; each public channel exports as a documented SQLite file. `©` `SaaS`
-* [Hootsuite](https://hootsuite.com/) - Social media management dashbaord. `©` `SaaS`
+* [Hootsuite](https://www.hootsuite.com/) - Social media management dashboard. `©` `SaaS`
 * [SocialBu](https://socialbu.com/) - AI-powered social media management and analytics platform with scheduling, monitoring, and automation. `©` `SaaS`
 * [Sproutsocial](http://sproutsocial.com/) - Social media management and analytics platform. `©` `SaaS`
 * [AI TikTok Analyzer Pro](https://tiktok.poviai.com/) - TikTok content research: rank a creator's public videos by engagement, export comments, AI transcripts and sentiment analysis. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Hootsuite is live and remains a social media management platform with analytics (its products include &#x27;Lumen Insights and listening&#x27;). The entry has a typo (&#x27;dashbaord&#x27;). https://hootsuite.com/ redirects to https://www.hootsuite.com/.</p>

<p>https://www.hootsuite.com/ — hootsuite.com redirects here (HTTP 200). Title &#x27;Social Media Marketing and Management Tool | Hootsuite&#x27;. Solutions include &#x27;Social media analytics&#x27;.</p>

<p>Caveats: The description change is only a spelling fix.</p>

</details>

<h3>Sproutsocial — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -256,7 +256,7 @@
 * [Open Channel Stats](https://openchannelstats.com) - Browse real YouTube channels' full owner analytics — retention, CTR, traffic sources — published by the creators themselves, not estimated; connect your own free to compare. Daily refresh; each public channel exports as a documented SQLite file. `©` `SaaS`
 * [Hootsuite](https://hootsuite.com/) - Social media management dashbaord. `©` `SaaS`
 * [SocialBu](https://socialbu.com/) - AI-powered social media management and analytics platform with scheduling, monitoring, and automation. `©` `SaaS`
-* [Sproutsocial](http://sproutsocial.com/) - Social media management and analytics platform. `©` `SaaS`
+* [Sproutsocial](https://sproutsocial.com/) - Social media management and analytics platform. `©` `SaaS`
 * [AI TikTok Analyzer Pro](https://tiktok.poviai.com/) - TikTok content research: rank a creator's public videos by engagement, export comments, AI transcripts and sentiment analysis. `©` `SaaS`
 * [Pulse](https://pulse.walls.sh) - Social post metrics REST API — give it a public post URL and get back views, likes, comments, shares in JSON. Covers YouTube, X/Twitter, TikTok, Bluesky, Mastodon, Instagram. No API key to start. `Free` `SaaS`
 * [IGDataHub](https://igdatahub.com/) - Instagram profile lookup (followers, following, posts) and dated follower readings for the accounts it tracks. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Sprout Social is live and remains a social media management platform with analytics, so the description is accurate. The listed http URL redirects to https://sproutsocial.com/.</p>

<p>https://sproutsocial.com/ — http://sproutsocial.com/ redirects here (HTTP 200). Title &#x27;Sprout Social: Social Media Management Tool&#x27;. Includes &#x27;Analyze your performance: Access analytics...&#x27;.</p>

<p>Caveats: The official brand spelling is &#x27;Sprout Social&#x27;. Renaming is optional and not proposed here.</p>

</details>

<h3>Falconsocial — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -248,7 +248,6 @@
 Often there is no clear differentiation between social media management and analytics as most the tools provide analytics.
 
 * [Brandwatch](http://www.brandwatch.com/) - Social media monitoring and analytics. `©` `SaaS`
-* [Falconsocial](http://www.falconsocial.com/) - communications platform built on social media with analytics. `©` `SaaS`
 * [Quintly](https://www.quintly.com/) - web-based tool to help you track, benchmark and optimize your social media performance. `©` `SaaS`
 * [Buffer](https://bufferapp.com/) - Social media publishing and analytics platform. `©` `SaaS`
 * [Topsy](http://topsy.com/) - Social analytics tool with search. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Falcon (Falcon.io / falconsocial.com) has been folded into Brandwatch. falconsocial.com now redirects to https://www.brandwatch.com/#from-falcon, and www.falconsocial.com no longer resolves. Brandwatch&#x27;s official blog says Falcon.io is now part of Brandwatch, with former Falcon products under Brandwatch Social Media Management. Brandwatch is already listed (id 250), so replacing this entry would duplicate it.</p>

<p>https://falconsocial.com/ — The apex redirects (HTTP 200 at the destination) to https://www.brandwatch.com/#from-falcon, an official redirect into Brandwatch.</p>

<p>https://dns.google/resolve?name=www.falconsocial.com&amp;type=A — NXDOMAIN (Status 3) for www.falconsocial.com, the host in the listed URL.</p>

<p>https://www.brandwatch.com/blog/falcon-cision-deal-closed/ — Official Brandwatch post on the Cision deal combining Brandwatch and Falcon.io. It states &#x27;Falcon.io is now part of Brandwatch&#x27; and that former Falcon products are under &#x27;Social Media Management&#x27; in &#x27;Our Suite&#x27;. Existing customers can log in to access Falcon products and data.</p>

<p>Caveats: Existing Falcon customers may still reach legacy Falcon products via the Brandwatch login. That does not make falconsocial.com a separate product to list.; Alternatively, the maintainer could mention Falcon&#x27;s lineage in the existing Brandwatch entry rather than deleting outright.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Topsy — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -251,7 +251,6 @@
 * [Falconsocial](http://www.falconsocial.com/) - communications platform built on social media with analytics. `©` `SaaS`
 * [Quintly](https://www.quintly.com/) - web-based tool to help you track, benchmark and optimize your social media performance. `©` `SaaS`
 * [Buffer](https://bufferapp.com/) - Social media publishing and analytics platform. `©` `SaaS`
-* [Topsy](http://topsy.com/) - Social analytics tool with search. `©` `SaaS`
 * [SocialBlade](http://socialblade.com/) - premiere YouTube statistics tracking. `©` `SaaS`
 * [Open Channel Stats](https://openchannelstats.com) - Browse real YouTube channels' full owner analytics — retention, CTR, traffic sources — published by the creators themselves, not estimated; connect your own free to compare. Daily refresh; each public channel exports as a documented SQLite file. `©` `SaaS`
 * [Hootsuite](https://hootsuite.com/) - Social media management dashbaord. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>Topsy officially announced its shutdown in December 2015 (&#x27;We&#x27;ve searched our last tweet&#x27;) after Apple acquired it. topsy.com is now on Apple-run DNS with no A record, so the listed social analytics search service no longer exists.</p>

<p>https://techcrunch.com/2015/12/15/rip-topsy/ — Reports that Topsy &#x27;closed its doors today. That&#x27;s according to the company itself&#x27;, quoting the official @Topsy tweet of 16 Dec 2015: &#x27;We&#x27;ve searched our last tweet.&#x27; topsy.com redirected to an Apple support page.</p>

<p>https://www.macrumors.com/2015/12/15/apple-shut-down-topsy/ — Confirms Topsy &#x27;announced the end of its service&#x27; on Twitter and that the website redirects to an Apple support page.</p>

<p>https://dns.google/resolve?name=topsy.com&amp;type=A — No A record. The SOA is ns-ext-prod.jackfruit.apple.com (Apple-controlled), so no site is served.</p>

<p>Caveats: The original @Topsy tweet was read via TechCrunch&#x27;s quotation, not directly on X.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Freeboard — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The description is still accurate: the README calls it an &#x27;open source real-time dashboard builder/viewer for IOT and other web mashups&#x27;. The entry&#x27;s metadata tags are wrong, though. The repo is MIT-licensed, client-side, and runs as a static, self-hostable app, but the entry is tagged `©` `SaaS`. The hosted service the README refers to, freeboard.io, now serves a Gandi parked-domain page. The prose change below is cosmetic only; the actual correction is changing the tags to `MIT` plus whatever self-hosted tag the README uses for its other open-source entries. The README tags can&#x27;t be changed through newDescription and must be edited by hand.</p>

<p>https://github.com/Freeboard/freeboard — GitHub API: Freeboard/freeboard, license MIT, archived false, last pushed 2023-09-23. The README says it can &#x27;run entirely in the browser as a single-page static web app without the need for a server&#x27; and is &#x27;Licensed under the MIT license&#x27;.</p>

<p>http://freeboard.io/ — Returns a Gandi parked page: &#x27;This domain name has been registered with Gandi.net. It is currently parked by the owner.&#x27; HTTPS to freeboard.io failed to connect.</p>

<p>http://freeboard.github.io/freeboard/ — The demo listed in the README still returns HTTP 200.</p>

<p>Blocking questions: The main fix is to the tags (`©` `SaaS` → `MIT`), and that needs a manual edit. Applying only the prose change would leave the wrong tags in place.</p>

<p>Caveats: The last push was in 2023. I&#x27;m not inferring anything about maintenance from that.; The freeboard.io HTTPS connection failure could be temporary, but the HTTP parked page is a clear sign the hosted service is gone.</p>

</details>

<h3>Pulse — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -258,7 +258,6 @@
 * [SocialBu](https://socialbu.com/) - AI-powered social media management and analytics platform with scheduling, monitoring, and automation. `©` `SaaS`
 * [Sproutsocial](http://sproutsocial.com/) - Social media management and analytics platform. `©` `SaaS`
 * [AI TikTok Analyzer Pro](https://tiktok.poviai.com/) - TikTok content research: rank a creator's public videos by engagement, export comments, AI transcripts and sentiment analysis. `©` `SaaS`
-* [Pulse](https://pulse.walls.sh) - Social post metrics REST API — give it a public post URL and get back views, likes, comments, shares in JSON. Covers YouTube, X/Twitter, TikTok, Bluesky, Mastodon, Instagram. No API key to start. `Free` `SaaS`
 * [IGDataHub](https://igdatahub.com/) - Instagram profile lookup (followers, following, posts) and dated follower readings for the accounts it tracks. `©` `SaaS`
 * [SnapDataHub](https://snapdatahub.com/) - Subscriber counts, Spotlight views and growth for public Snapchat creator profiles; earnings figures are estimates. `©` `SaaS`
 * [TKMetrics](https://tkmetrics.com/) - TikTok creator reports (average views, engagement rate, posting times) and public hashtag trends. `©` `SaaS`
```

<details>
<summary>Evidence and limitations</summary>

<p>The operator&#x27;s own server says the service is no longer public. Every path tried on pulse.walls.sh (root, /docs, an API-style query) returns HTTP 401 with JSON {&quot;error&quot;:&quot;private&quot;,&quot;message&quot;:&quot;Pulse is a private service.&quot;}. That contradicts the entry&#x27;s &#x27;No API key to start&#x27; and `Free` claims: the listed interface can&#x27;t be used by the public. The operator&#x27;s homepage (Walls SH LLC) lists other apps and doesn&#x27;t mention Pulse. I found no public successor.</p>

<p>https://pulse.walls.sh/ — HTTP 401, body {&quot;error&quot;:&quot;private&quot;,&quot;message&quot;:&quot;Pulse is a private service.&quot;}. /docs and /api?url=... return the same.</p>

<p>https://walls.sh/ — Studio homepage &#x27;Walls is an independent studio run by Pat Walls&#x27;. It lists the apps Kickoff and Poker Practice, not Pulse. https://walls.sh/pulse returns 401 &#x27;walls.sh is private&#x27;.</p>

<p>Caveats: There&#x27;s no dated announcement. The operator could make Pulse public again; a quick recheck before removal is reasonable.; The snapshot failure was flagged as fetch-incomplete, but the live 401 response carries an explicit &#x27;private&#x27; message rather than a transient error.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Moiva.io — remove</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL no longer serves Moiva. https://moiva.io/ returns a 301 that chains through about 15 unrelated domains (hula hoops, a restaurant PDF, laser tag, cat breeds and others) and ends at a Spanish traffic-fine legal page on abogator.com. The official source repo, aantipov/moiva, whose homepage field is moiva.io, is archived and was last pushed 2024-08-07. No official replacement URL exists, so the entry can&#x27;t be pointed anywhere else.</p>

<p>https://moiva.io/ — Redirect chain starting with HTTP 301 to https://zlhulahoops.com/ and continuing through many unrelated sites to https://abogator.com/index.php/tramites-trafico/... (HTTP 200, unrelated content).</p>

<p>https://github.com/aantipov/moiva — GitHub API: archived true, pushed 2024-08-07, homepage https://moiva.io. Description: &#x27;A Universal tool to Evaluate, Discover alternatives and Compare Software projects.&#x27; The README says it supports GitHub and NPM.</p>

<p>Blocking questions: There is no official shutdown announcement. I can&#x27;t tell whether the domain lapsed or was temporarily compromised; if it was compromised, the owner might restore it.</p>

<p>Caveats: Archiving alone doesn&#x27;t prove the software is unusable. The removal rests on the listed URL no longer serving the product.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Superset — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -295,7 +295,7 @@
 * [Chartbrew](https://chartbrew.com) - Chartbrew allows you to query your databases and APIs to create live charts and visualize your data. Featuring automatic chart updates, sharing, embedding, printing, exporting, and team support with granular permissions. ([Demo](https://app.chartbrew.com/live-demo), [Source Code](https://github.com/chartbrew/chartbrew)) `MIT` `NodeJS` `SaaS` `Self-Hosted`
 * [Conyso Lens](https://conyso.com/lens.html?utm_source=github&utm_medium=directory&utm_campaign=listing) - General-purpose data-visualization studio: point it at any dataset and get publication-quality charts across 112 chart types, each with a plain-English, rule-based read (never AI-generated). Runs entirely in the browser; nothing you load ever leaves it. Self-host option available. `©` `SaaS` `Self-Hosted`
 * [Redash](http://redash.io) - connect to over 18 types of databases (SQL and "NoSQL"), query your data, visualize it and create dashboards. Everything has a URL that can be shared. Slack and HipChat integration. ([Demo](https://demo.redash.io), [Source Code](https://github.com/getredash/redash)) `BSD-2-Clause` `Python`
-* [Superset](http://superset.apache.org/) - Modern, enterprise-ready business intelligence web application. ([Source Code](https://github.com/apache/incubator-superset)) `Apache-2.0` `Python`
+* [Superset](https://superset.apache.org/) - Modern, enterprise-ready business intelligence web application. ([Source Code](https://github.com/apache/incubator-superset)) `Apache-2.0` `Python`
 * [Socioboard](https://socioboard.org/) - `⚠` Social media management, analytics, and reporting platform supporting nine social media networks out-of-the-box. ([Source Code](https://github.com/socioboard/Socioboard-4.0)) `GPL-3.0` `C#/JavaScript`
 * [Edalitics](https://www.edalitics.com) - Open source analytics/BI tool.  ([Source Code](https://github.com/jortilles/EDA)) `©` `SaaS` `AGPL-3.0` `Angular/Nodejs`
 * [DAC](https://getbruin.com/docs/dac/) - dashboard-as-code tool that defines dashboards in YAML and TSX, with a built-in semantic layer for metrics and dimensions. ([Source Code](https://github.com/bruin-data/dac)) `AGPL-3.0` `Go` `Self-Hosted`
```

<details>
<summary>Evidence and limitations</summary>

<p>The description matches the current README word for word: &#x27;A modern, enterprise-ready business intelligence web application.&#x27; The main URL uses http, and http://superset.apache.org/ redirects to https://superset.apache.org/. The inline Source Code link github.com/apache/incubator-superset redirects to the canonical apache/superset. That link sits in the suffix, so it needs a manual edit, while the https main URL can be applied directly. The Apache-2.0 license is unchanged.</p>

<p>https://superset.apache.org/ — http://superset.apache.org/ resolves via redirect to https://superset.apache.org/ (200).</p>

<p>https://github.com/apache/superset — https://github.com/apache/incubator-superset redirects here. Title: &#x27;Apache Superset is a Data Visualization and Data Exploration Platform&#x27;.</p>

<p>https://raw.githubusercontent.com/apache/superset/HEAD/README.md — Contains &#x27;A modern, enterprise-ready business intelligence web application.&#x27;</p>

<p>Caveats: The inline Source Code link (apache/incubator-superset → apache/superset) is in the suffix. A maintainer must update it by hand; it is not part of newUrl.</p>

</details>

<h3>Redash — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Redash is still relevant: it is open source, the repo had commits on 2026-11-10, and the site is live. Two description claims are outdated. &#x27;Over 18 types of databases&#x27; understates the README&#x27;s &#x27;more than 35 SQL and NoSQL data sources&#x27;, and a durable phrasing is better than either number. &#x27;HipChat integration&#x27; is no longer supported: the changelog records &#x27;Deprecated HipChat Alert Destination&#x27;, and the current redash/destinations directory has no HipChat module, while Slack is still present. This is a complex entry with inline Demo and Source Code links, so it needs a manual edit. The proposed text keeps those links. https://redash.io/ also serves 200.</p>

<p>https://raw.githubusercontent.com/getredash/redash/HEAD/README.md — &#x27;Redash supports more than 35 SQL and NoSQL data sources.&#x27; Features include a browser-based tool with shareable URLs, a query editor, visualizations and dashboards, alerts, and a REST API.</p>

<p>https://github.com/getredash/redash/tree/master/redash/destinations — Destinations are asana, chatwork, datadog, discord, email, hangoutschat, mattermost, microsoft_teams_webhook, pagerduty, slack, webex and webhook. There is no hipchat.</p>

<p>https://raw.githubusercontent.com/getredash/redash/HEAD/CHANGELOG.md — Contains &#x27;- Deprecated HipChat Alert Destination.&#x27;</p>

<p>https://redash.io/ — Live: &#x27;Redash helps you make sense of your data. Connect and query your data sources, build dashboards to visualize data and share them with your company.&#x27; http://redash.io also serves 200 without redirecting.</p>

<p>https://github.com/getredash/redash — Resolves without redirect. Description: &#x27;Make Your Company Data Driven. Connect to any data source, easily visualize, dashboard and share your data.&#x27; Latest commit is 2026-11-10.</p>

<p>Caveats: https://demo.redash.io could not be reached: the proxy CONNECT tunnel returned 502 on two attempts. Its status is unknown, so the Demo link is preserved. A maintainer should recheck it, but this does not affect the prose correction.; The LICENSE file shows a BSD-style copyright header. The SPDX identifier was not confirmed via the API because it was rate-limited.; Multi-link entry: the inline Demo and Source Code links are embedded in the description and must be hand-edited.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>awesome-bigdata — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -312,7 +312,7 @@
 - Even more lists [awesome](https://github.com/sindresorhus/awesome).
 - Another list? [list](https://github.com/jnv/lists).
 - WTF! [awesome-awesome-awesome](https://github.com/t3chnoboy/awesome-awesome-awesome).
-- Analytics [awesome-bigdata](https://github.com/onurakpolat/awesome-bigdata).
+- Analytics [awesome-bigdata](https://github.com/oxnr/awesome-bigdata).
 
 # Resources and Comparisons
 - [Analytics Compare](https://www.analytics-compare.com/tools/compare/) - An independent, interactive database comparing 30+ analytics tools based on features, hidden costs, and scalability risks.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL https://github.com/onurakpolat/awesome-bigdata returns a GitHub 301 redirect to https://github.com/oxnr/awesome-bigdata. The packet&#x27;s source snapshot also records the repository as oxnr/awesome-bigdata. The repository name is unchanged and only the owner changed. The content is still a curated big-data list, which is relevant to analytics, so a canonical URL update is warranted.</p>

<p>https://github.com/onurakpolat/awesome-bigdata — curl returned HTTP 301 with Location https://github.com/oxnr/awesome-bigdata. That is a GitHub transfer/rename redirect.</p>

<p>https://github.com/oxnr/awesome-bigdata — The page loads with no &#x27;forked from&#x27; marker and no archived banner. Its homepage/website field still points to the old onurakpolat URL, consistent with an owner rename of the same repository.</p>

<p>https://raw.githubusercontent.com/oxnr/awesome-bigdata/master/README.md — The README is &#x27;Awesome Big Data – A curated list of awesome big data frameworks, resources and other awesomeness&#x27;, with current sections including Lakehouse Table Formats, Vector Databases and Data Quality and Observability.</p>

<p>https://github.com/oxnr/awesome-bigdata/commits/master.atom — The latest commit feed entry is dated 2026-11-06, so the list is actively updated.</p>

<p>Caveats: The GitHub API was rate-limited, so the owner rename was confirmed from the HTTP redirect and the packet snapshot rather than API metadata.; The catalog (oxnr/awesome-analytics) appears to share this owner. That is a curation note, not a blocker.; Only the URL changes. The prose-prefixed entry text (&#x27;Analytics&#x27;) should be preserved by manual or deterministic editing.</p>

</details>

## Uncertain findings

<h3>stratif.io — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>README supports warehouse-native self-hosted analytics and the listed database/analysis capabilities. The repository LICENSE and README identify Apache-2.0, while pyproject.toml declares MIT. This is a real upstream metadata conflict, not enough evidence to call the catalog Apache tag false. Conservatively withhold independent baseline approval pending resolution, while retaining the raw model result.</p>

<p>https://raw.githubusercontent.com/stratif-io/stratif.io/develop/README.md — README says it &#x27;connects directly to your existing DuckDB, Postgres, Snowflake, or ClickHouse. No ingestion. No pipelines.&#x27; and &#x27;No ingestion pipeline. No SDK.&#x27; It lists supported databases as DuckDB, SQLite, PostgreSQL, ClickHouse, Snowflake and Databricks, and carries an Apache-2.0 license badge.</p>

<p>https://api.github.com/repos/stratif-io/stratif.io — Canonical repo is stratif-io/stratif.io. It is not archived, the license is Apache-2.0, and the last push was 2026-04-30.</p>

<p>https://stratif.io/ — Title: &#x27;Open-source product analytics on your warehouse&#x27;. Meta description: &#x27;Funnels, retention, and paths — directly on your warehouse. Self-hosted, no ingestion, free.&#x27;</p>

<p>Blocking questions: README supports warehouse-native self-hosted analytics and the listed database/analysis capabilities. The repository LICENSE and README identify Apache-2.0, while pyproject.toml declares MIT. This is a real upstream metadata conflict, not enough evidence to call the catalog Apache tag false. Conservatively withhold independent baseline approval pending resolution, while retaining the raw model result.</p>

<p>Caveats: Databricks and SQLite are also supported. Adding them is optional, since the entry is non-exclusive.; pyproject.toml declares license text &#x27;MIT&#x27; while the repo LICENSE/badge is Apache-2.0. The maintainer may want to double-check the license tag.; Last push was April 2026. Activity level is not assessed.</p>

<p>Independent source check: README supports warehouse-native self-hosted analytics and the listed database/analysis capabilities. The repository LICENSE and README identify Apache-2.0, while pyproject.toml declares MIT. This is a real upstream metadata conflict, not enough evidence to call the catalog Apache tag false. Conservatively withhold independent baseline approval pending resolution, while retaining the raw model result.</p>

<p>https://github.com/stratif-io/stratif.io/blob/develop/README.md — Functional claims confirmed; README blob 5a0416f3990401ab6338e36b2ea9f8dc2ca56e0b.</p>

<p>https://github.com/stratif-io/stratif.io/blob/develop/LICENSE — Apache2 text; blob44a78194b0dac91acaf146a5c0a2ffbb69e38b1b.</p>

<p>https://github.com/stratif-io/stratif.io/blob/develop/pyproject.toml — Project license field declares MIT.</p>

</details>

<h3>Screpy — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>New SEO positioning is verified, but a homepage not mentioning Lighthouse and a UI not displaying its score do not establish that Lighthouse stopped powering measurements. Older official Screpy material explicitly documents Lighthouse integration. Treat expanded wording as optional or leave backend question unresolved, not a confirmed factual correction.</p>

<p>https://screpy.com/ — Title: &#x27;AI SEO Analyzer &amp; Website Audit Tool | Screpy&#x27;. The nav lists Website Audit, SEO Crawler, Rank Tracker, AI Visibility, Core Web Vitals, PageSpeed Monitoring and Uptime Monitoring. The homepage has zero occurrences of &#x27;Lighthouse&#x27;.</p>

<p>https://screpy.com/pagespeed-monitoring/ — The FAQ says &#x27;This screen does not show a 0–100 Lighthouse or Google PageSpeed score&#x27;. The status is based on LCP/CLS/TBT classifications, and the page references PageSpeed Insights v5 docs.</p>

<p>Blocking questions: New SEO positioning is verified, but a homepage not mentioning Lighthouse and a UI not displaying its score do not establish that Lighthouse stopped powering measurements. Older official Screpy material explicitly documents Lighthouse integration. Treat expanded wording as optional or leave backend question unresolved, not a confirmed factual correction.</p>

<p>Caveats: Screpy may still use PageSpeed Insights, which runs Lighthouse, internally. The proposed wording simply avoids the claim.; Screpy is now primarily an SEO tool. Its fit in General analytics is marginal, and the maintainer may prefer a different section.</p>

<p>Independent source check: New SEO positioning is verified, but a homepage not mentioning Lighthouse and a UI not displaying its score do not establish that Lighthouse stopped powering measurements. Older official Screpy material explicitly documents Lighthouse integration. Treat expanded wording as optional or leave backend question unresolved, not a confirmed factual correction.</p>

<p>https://screpy.com/ — Current site presents SEO analysis, site audits, rank tracking and monitoring.</p>

<p>https://screpy.com/feature/pagespeed-monitoring/ — Current page distinguishes lab metrics from a displayed Lighthouse score; this does not identify the underlying measurement engine.</p>

<p>https://screpy.com/what-are-google-pagespeed-insights/ — Older official article explicitly describes Lighthouse monitoring with Screpy.</p>

<p>https://screpy.com/definivite-guide-on-first-contentful-paint/ — Older official article describes Screpy as integrated with Lighthouse.</p>

</details>

<h3>Hotjar — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>I could not load hotjar.com (proxy 502 on every attempt). Third-party 2026 reviews report that Hotjar Ltd merged into Contentsquare on 2025-07-01, that new Hotjar accounts can no longer be created, and that hotjar.com leads to a &#x27;Hotjar is now Contentsquare&#x27; page. If that is confirmed, a rename/replace to Contentsquare may be warranted. Missing fact: the current content and redirect target of hotjar.com, from the official site.</p>

<p>https://formbricks.com/blog/hotjar-review — Search-result summary from a third-party (competitor) review describing the Contentsquare merger and the end of standalone Hotjar signups. I did not read the page fully, and it is not an official source.</p>

<p>Blocking questions: Official hotjar.com content and redirect not verified.</p>

<p>Caveats: Unreachable from this session&#x27;s network proxy. This is not evidence that the site is down.; The current description is vague but not false.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Heap — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>heap.io was unreachable (proxy 502). Search results show the heap.io homepage titled &#x27;Heap - Better Insights. Faster.&#x27; and stating that Heap has joined forces with Contentsquare. Reviews say Heap still autocaptures clicks, pageviews and form fills, which matches the entry. Missing fact: direct confirmation of current heap.io content and branding (&#x27;Heap by Contentsquare&#x27;).</p>

<p>https://www.heap.io/ — Seen only as a search-result title (&#x27;Heap - Better Insights. Faster.&#x27;) with a note about joining Contentsquare. I could not load it directly.</p>

<p>Caveats: Network proxy blocked access. This is not evidence that the site is down.; If confirmed, the description is likely still accurate (autocapture of clicks and form submissions).</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Opentracker — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>opentracker.net returned 502 from this session&#x27;s proxy over both http and https. Search-indexed pages on opentracker.net describe real-time reporting and visitor geo-location profiles, consistent with the entry. Missing fact: a direct read confirming the homepage is live, and whether http redirects to https.</p>

<p>https://www.opentracker.net/products/web-analytics/ — Seen via search index only. It mentions real-time tracking, geo-location in visitor profiles and a 4-week free trial.</p>

<p>Caveats: Proxy-blocked. This is not evidence that the site is down.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Adobe Analytics — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The listed adobe.com URL returned HTTP 403 to automated requests, likely bot blocking. Adobe Analytics is still an active Adobe product (2026 Experience League material, part of Adobe CX Analytics). Missing fact: whether the listed URL still resolves for browsers or now redirects to business.adobe.com.</p>

<p>https://experienceleague.adobe.com/en/docs/analytics-platform/using/releases/2026 — Seen via search. It shows 2026 Adobe analytics release notes, indicating the Adobe Analytics family is active. Not read directly.</p>

<p>Caveats: A 403 is likely bot protection. This does not show the URL is dead.; The description is vague but not false.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Clicktale — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Clicktale was acquired by Contentsquare in 2019. Its official X account is now &#x27;Clicktale (now Contentsquare)&#x27;, and LinkedIn lists contentsquare.com as its website. clicktale.com was unreachable from this session (proxy 502), so its current redirect target is unverified. A replace with Contentsquare is plausible but unconfirmed.</p>

<p>https://x.com/clicktale?lang=en — Seen via search: account named &#x27;Clicktale (now Contentsquare)&#x27;, directing followers to @Contentsquare. Not read directly.</p>

<p>Blocking questions: clicktale.com redirect and official successor page not verified directly.; Hotjar (id 34) may also resolve to Contentsquare, which risks a duplicate entry.</p>

<p>Caveats: Network proxy blocked clicktale.com.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>GoSquared — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>gosquared.com was unreachable (proxy 502). Third-party status monitors and Crunchbase show GoSquared still operating in 2026, with analytics, CRM, live chat and email reports. Missing fact: official confirmation that &#x27;visitor tagging&#x27; is still a feature.</p>

<p>https://status.gosquared.com/uptime — Seen via search. The status page lists Website, Data Ingestion, API, Now Dashboard and Trends Dashboard. Direct fetch failed (proxy 502).</p>

<p>Caveats: Proxy-blocked. This is not evidence that the site is down.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Woopra — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>woopra.com was unreachable (proxy 502). Woopra was acquired by Appier (2022). G2 lists it as &#x27;Appier AIRIS (formerly Woopra)&#x27;, while other 2026 reviews say Woopra is still sold standalone. The current canonical name and URL are unresolved.</p>

<p>https://www.g2.com/products/appier-airis-formerly-woopra/reviews — Seen via search: product listed as &#x27;Appier AIRIS (formerly Woopra)&#x27;. This is a third-party source and was not read directly.</p>

<p>Blocking questions: No official confirmation of the rebrand or of the current woopra.com content.</p>

<p>Caveats: Proxy-blocked.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Mint — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Direct official-page reads failed in this independent audit. Raw keep relies on search excerpts and simultaneously calls the existing SaaS tag inaccurate; a known metadata discrepancy should not be buried as an informational caveat on an approved keep. Snapshot was incomplete and Mint is absent from the proposed baseline, so no completed review was saved.</p>

<p>https://haveamint.com/ — Seen via search index: &#x27;Hey there, I have officially suspended sales and support of Mint.&#x27; Account and licence forms are disabled. Direct fetch failed (proxy 502).</p>

<p>Blocking questions: Direct official-page reads failed in this independent audit. Raw keep relies on search excerpts and simultaneously calls the existing SaaS tag inaccurate; a known metadata discrepancy should not be buried as an informational caveat on an approved keep. Snapshot was incomplete and Mint is absent from the proposed baseline, so no completed review was saved.</p>

<p>Caveats: Official page read only via search excerpts.; The `SaaS` tag appears wrong (Mint is self-hosted). This is a metadata issue outside newDescription.</p>

<p>Independent source check: Direct official-page reads failed in this independent audit. Raw keep relies on search excerpts and simultaneously calls the existing SaaS tag inaccurate; a known metadata discrepancy should not be buried as an informational caveat on an approved keep. Snapshot was incomplete and Mint is absent from the proposed baseline, so no completed review was saved.</p>

<p>https://haveamint.com/ — Could not read through web tool over HTTPS or HTTP; no positive verification.</p>

<p>https://haveamint.com/about/ — Could not read; no inference that site is dead.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Going Up — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>goingup.com was unreachable (proxy 502), and search turned up only old (2009-era) third-party coverage. I found no current official evidence that GoingUp still operates or still offers combined SEO and web analytics.</p>

<p>Caveats: Proxy-blocked. This is not evidence that the site is down.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Hitslink.com — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>I could not establish whether HitsLink web analytics is still operating. hitslink.com could not be fetched from this environment. Search results show HitsLink product and pricing pages still indexed. The parent company, Net Applications, retired NetMarketShare in October 2020 and stopped billing those accounts, but I found no official notice ending HitsLink analytics itself.</p>

<p>https://www.hitslink.com/home/features — Search result: the HitsLink &#x27;Web analytics&#x27; features page is still indexed. Its content and freshness are unverified.</p>

<p>https://marketshare.hitslink.com/report.aspx?qprid=17 — Search excerpt: a notice on a HitsLink host says NetMarketShare is being retired and October 2020 is the last month of data. It does not say whether HitsLink analytics is affected.</p>

<p>Blocking questions: Unknown: whether HitsLink analytics accepts customers or runs at all after the 2020 NetMarketShare retirement. A maintainer should load hitslink.com directly.</p>

<p>Caveats: Direct fetches of hitslink.com failed (proxy CONNECT failure). Treat this as an access failure, not proof the site is dead.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Sitemeter — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Site Meter looks defunct. Third-party reports describe years of outages and failure around 2015, and a 2026 vendor article says sitemeter.com does not resolve. I found no official Site Meter shutdown notice, and both fetch attempts failed here (502 through the proxy).</p>

<p>https://althouse.blogspot.com/2014/11/whatever-happened-to-sitemeter.html — Search excerpt (third party, 2014): SiteMeter had been down for days, with no response to support email.</p>

<p>https://mapmyvisitors.com/b/sitemeter-alternatives — Search excerpt (competing vendor, 2026): says SiteMeter stopped working in the mid-2010s and sitemeter.com did not resolve in June 2026.</p>

<p>Blocking questions: No official evidence that Site Meter shut down. A maintainer should confirm sitemeter.com no longer serves the product (DNS or HTTP from a normal network) before removing.</p>

<p>Caveats: The evidence is third-party, and one source is a competitor. Fetch failures here may be environmental.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Sitespect — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>https://www.sitespect.com/ now returns HTTP 301 (WordPress) to https://monetate.com/maestro/. Press coverage of Monetate&#x27;s June 2025 release says Monetate acquired SiteSpect, and SiteSpect&#x27;s technology now ships as &#x27;Forte&#x27; inside Monetate&#x27;s Maestro experimentation suite. That points to an officially documented successor. The exact name to list (Monetate Maestro or Forte) and whether to keep the &#x27;analytics&#x27; framing need maintainer judgment, and I could not read the Monetate pages directly.</p>

<p>https://www.sitespect.com/ — Direct curl: HTTP/2 301, x-redirect-by: WordPress, resolving to https://monetate.com/maestro/.</p>

<p>https://www.morningstar.com/news/business-wire/20250630514541/monetate-acquires-sitespect-to-deliver-ai-native-personalization-and-testing-at-enterprise-scale — Search result: Business Wire release from 30 June 2025, &#x27;Monetate Acquires SiteSpect to Deliver AI-Native Personalization and Testing at Enterprise Scale&#x27;.</p>

<p>https://monetate.com/forte/ — Search excerpt: Forte is Monetate&#x27;s network-layer experimentation offering in Maestro, derived from SiteSpect.</p>

<p>Blocking questions: Successor naming is unresolved: the redirect points to Monetate Maestro, but SiteSpect&#x27;s technology is branded Forte. Read the official Monetate pages before preparing a replace.; Relevance framing: Maestro/Forte is experimentation and personalization, and the existing &#x27;full-suite analytics&#x27; wording may not carry over.</p>

<p>Caveats: monetate.com could not be fetched from this environment (connection refused, WebFetch failure). I did not read the Maestro or Forte page content directly.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Rakam — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The Source Code link github.com/rakam-io/rakam now redirects to rakam-io/rakam-api. That repo is not archived, but its last commit was 13 November 2021. Its description says it &#x27;only includes the API collector, not the visualization platform&#x27;, and its license is AGPL-3.0, not the Apache-2.0 in the tag. Search excerpts of Rakam&#x27;s official blog say Rakam joined LiveRamp and &#x27;Rakam BI &amp; API will be shut down in the following months.&#x27; This strongly suggests the hosted platform is gone, but the open-source collector code is still published, and I could not read rakam.io directly.</p>

<p>https://github.com/rakam-io/rakam — Redirects to https://github.com/rakam-io/rakam-api. Repo title: &#x27;Collect customer event data from your apps. (Note that this project only includes the API collector, not the visualization platform)&#x27;. Page metadata: isArchived false, license AGPL-3.0, homepage getrakam.com.</p>

<p>https://raw.githubusercontent.com/rakam-io/rakam-api/master/README.md — README still describes a modular analytics platform and points to a separate Rakam UI product (app.rakam.io) for dashboards.</p>

<p>https://github.com/rakam-io/rakam-api/commits/master.atom — The latest commit entry is updated 2021-11-13.</p>

<p>https://rakam.io/blog/we-are-excited-to-announce-rakam-is-joining-liveramp/ — Search excerpt of the official blog: &#x27;we&#x27;ll need to sunset some of our products: Rakam BI &amp; API will be shut down in the following months.&#x27;</p>

<p>Blocking questions: Unclear whether the sunset notice covers the self-hostable open-source rakam-api code or only the hosted Rakam BI/API service. Removal needs that confirmed from the official announcement.; Unverified whether rakam.io still serves product pages or only the LiveRamp notice.</p>

<p>Caveats: Direct fetches of rakam.io and getrakam.com failed in this environment.; The license tag mismatch (Apache-2.0 vs AGPL-3.0) and the redirected Source Code link are suffix metadata and need manual correction whatever the decision.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Hastic — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The GitHub repos behind the entry (hastic-server and hastic-grafana-app) are marked obsolete and point to a new Rust &#x27;Hastic standalone&#x27; at code.corpglory.net/hastic/hastic. That version needs Prometheus or InfluxDB and builds its own web UI, so &#x27;UI for Grafana&#x27; and the Python/Nodejs tag may describe only the obsolete implementation. The new location could not be verified and hastic.io could not be read, so an update or replace can&#x27;t be confirmed yet.</p>

<p>https://raw.githubusercontent.com/hastic/hastic-server/master/README.md — &#x27;This repo is obsolete, see new rust version of hastic (https://code.corpglory.net/hastic/hastic)&#x27;. Basic pattern recognition for anomaly detection, with a Grafana app.</p>

<p>https://raw.githubusercontent.com/hastic/hastic-grafana-app/master/README.md — Also says &#x27;This repo is obsolete, see new rust version of hastic&#x27;.</p>

<p>https://raw.githubusercontent.com/hastic/hastic/main/README.md — &#x27;THE DEVELOPMENT OF THIS REPO MOVED To https://code.corpglory.net/hastic/hastic&#x27;. &#x27;Hastic needs Prometheus or InfluxDB&#x27;. Built with cargo and node, it serves its own UI on localhost.</p>

<p>https://github.com/hastic — The org page is reachable. The latest activity shown is dated 2023-03-04.</p>

<p>Blocking questions: code.corpglory.net returned NXDOMAIN via public DNS (dns.google), so the documented successor location could not be read or confirmed as live.; Unknown whether the Rust standalone still offers a Grafana UI, which determines whether &#x27;UI for Grafana&#x27; and the `Python/Nodejs` tag are now inaccurate.; Couldn&#x27;t read hastic.io to confirm the project&#x27;s current self-description.</p>

<p>Caveats: hastic.io resolves in DNS but could not be fetched from this environment (proxy/connection failure). This is not evidence that the site is down.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Count — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>count.co could not be fetched directly (proxy 502, WebFetch failure). Search results from Count&#x27;s own blog and docs indicate it moved from a SQL notebook to a collaborative &#x27;canvas&#x27; with SQL, Python, visual and low-code cells, plus newer AI-agent positioning. If confirmed, &#x27;notebook-based&#x27; may be outdated. The SQL and drag-and-drop/low-code claims appear to still hold.</p>

<p>Blocking questions: Count&#x27;s current self-description could not be read from an official page, so it&#x27;s unconfirmed whether &#x27;notebook-based&#x27; is now inaccurate (canvas vs notebook) and what wording to use.</p>

<p>Caveats: Search snippets (count.co/blog/bye-bye-notebooks-hello-canvas, count.co/blog/introducing-low-code-the-power-of-sql-without-writing-any, learn.count.co/data-exploration-and-problem-solving/sql-cells) suggest the canvas positioning, but these pages were not read directly, so they are not cited as evidence.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Vaneform — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Vaneform blocks plain curl (403) but serves pages to a browser user agent. The lookup is still free without signup (guests get 3 per day). A sample report shows estimated monthly visits, traffic sources, regions and ranking keywords. No &#x27;similar sites&#x27; section appeared on the homepage, the tools and pricing pages, or a sample report (/e/google-com). It is unresolved whether that listed capability still exists.</p>

<p>https://vaneform.com/ — &#x27;Vaneform is a free website traffic checker: look up any site&#x27;s monthly visits, traffic sources and top countries.&#x27; &#x27;Free: 3 lookups/day · 999/day with a free account&#x27;.</p>

<p>https://vaneform.com/e/google-com — The sample report shows estimated monthly visits, a traffic channel split, Regions (top countries), keyword samples and keyword rankings. The only related items are &#x27;Related boards&#x27; and &#x27;Related tools&#x27;; no similar-sites list was found.</p>

<p>https://vaneform.com/pricing — &#x27;Website lookup is free&#x27;. Guests get 3 lookups per day; signed-in Free users get 999 per day; a paid Pro plan exists.</p>

<p>Blocking questions: It is unconfirmed whether Vaneform still offers &#x27;similar sites&#x27; for a domain. If it does not, the description should drop that phrase.</p>

<p>Caveats: Parts of the report may render client-side, so a similar-sites section could exist without appearing in the fetched HTML.</p>

</details>

<h3>Kindmetrics — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>kindmetrics.io now serves a hosting provider&#x27;s &#x27;Sorry, the website has been stopped&#x27; page, so the listed product URL no longer shows Kindmetrics. The GitHub repo still exists, is MIT and not archived, but its last commit was in May 2022. I found no official statement that the project or service was discontinued, so removal isn&#x27;t supported by official evidence.</p>

<p>https://kindmetrics.io/ — HTTP 200 but page title/body &#x27;Sorry, the website has been stopped&#x27; (hosting placeholder), no Kindmetrics content.</p>

<p>https://github.com/kindmetrics/kindmetrics — Canonical kindmetrics/kindmetrics; MIT; no archive banner; last commit feed entry 2022-05-26; README still describes privacy-focused, cookieless analytics built on Crystal/Lucky.</p>

<p>Blocking questions: No official notice found on whether Kindmetrics was discontinued or moved; site stoppage may be a billing or hosting issue.; Unresolved whether to relink the entry to the repository as the primary URL.</p>

<p>Caveats: Did not check whether the service moved to another domain.</p>

</details>

<h3>Nibspace — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>nibspace.com now redirects to a HugeDomains domain-for-sale page. Wayback Machine shows the Nibspace analytics product in 2023, then an empty &#x27;Index of /&#x27; listing by Nov 2025–Feb 2026. That strongly suggests the service is gone, but I found no official shutdown notice or successor.</p>

<p>https://nibspace.com/ — Via r.jina.ai: final URL https://www.hugedomains.com/domain_profile.cfm?d=nibspace.com (domain sale page).</p>

<p>https://web.archive.org/web/20230601031508/https://nibspace.com/ — Archived page: &#x27;Nibspace · Privacy-oriented alternative to Google Analytics... Lightweight, affordable &amp; privacy-oriented alternative to Google Analytics, without cookies&#x27;.</p>

<p>https://web.archive.org/web/20251205153710/https://nibspace.com/ — Archived page is an empty &#x27;Index of /&#x27; listing with only robots.txt (dated 2025-11-13).</p>

<p>Blocking questions: No official shutdown announcement or successor found; removal requires affirmative official evidence.</p>

<p>Caveats: Direct fetch blocked by sandbox proxy; relied on r.jina.ai and the Wayback Machine.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Swetrix — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The description is supported: Swetrix is EU-hosted, open-source, privacy-first web and product analytics with self-hosting, and the repo is canonical and active. Separately, the `MIT` half of the `MIT`/`AGPL-3.0` license tag looks wrong. The repo README and LICENSE state AGPLv3 only for the Community Edition, with no MIT component in the listed repo. The tag needs a manual check. Optionally, the trailing comma in the description could be cleaned up.</p>

<p>https://swetrix.com/ — Via r.jina.ai: &#x27;privacy-first Google Analytics alternative&#x27;; sections &#x27;Web analytics&#x27; and &#x27;Product analytics&#x27;; &#x27;Open source &amp; self-hostable&#x27;; Community Edition self-hosting.</p>

<p>https://github.com/swetrix/swetrix — Canonical Swetrix/swetrix; license AGPL-3.0; not archived; last commit 2026-11-06.</p>

<p>https://raw.githubusercontent.com/swetrix/swetrix/HEAD/README.md — &#x27;GDPR-compliant and hosted in the EU&#x27;; License section: &#x27;Swetrix Community Edition is open source under the GNU Affero General Public License v3 (AGPLv3).&#x27; LICENSE file is GNU AGPL v3.</p>

<p>Blocking questions: The `MIT` license tag is unverified for this repository and needs a manual check; it is metadata, not part of the description.</p>

<p>Caveats: Did not check whether separate Swetrix repositories (for example the tracking script) are MIT-licensed, which might explain the original tag.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>GoatCounter — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>GoatCounter remains a relevant open-source web analytics platform, available hosted or self-hosted, with a live demo. The &#x27;free for non-commercial use&#x27; claim is unresolved. The README and an Oct 2026 archived homepage say &#x27;free donation-supported hosted service&#x27; with no stated restriction; only a 2021 archived terms page says commercial users must buy a plan. Separately, the `MIT` tag is wrong: LICENSE is a modified EUPL-1.2. The tag must be fixed by hand. goatcounter.com could not be reached directly from this environment (proxy CONNECT 502).</p>

<p>https://github.com/arp242/goatcounter — README: &#x27;GoatCounter is an open source web analytics platform available as a (free) hosted service or self-hosted app&#x27; and &#x27;can be self-hosted without restrictions&#x27;. The repo resolves without a redirect.</p>

<p>https://raw.githubusercontent.com/arp242/goatcounter/HEAD/LICENSE — &#x27;GoatCounter is licensed under a slightly modified version of European Union Public License (EUPL) 1.2&#x27;. This is not MIT, so the catalog&#x27;s `MIT` tag is incorrect.</p>

<p>https://web.archive.org/web/20261031225053/https://www.goatcounter.com/ — Archived homepage, 2026-10-31: &#x27;available as a free donation-supported hosted service or self-hosted app&#x27;.</p>

<p>https://web.archive.org/web/20211009094626/https://www.goatcounter.com/terms — Only a 2021 capture was available: &#x27;The service is free for personal use, but all commercial users must purchase a plan after the initial 14-day trial&#x27;. Whether this still applies is unknown.</p>

<p>https://stats.arp242.net/ — The demo is live and shows a GoatCounter report for 2026-11-03 to 2026-11-10.</p>

<p>Blocking questions: Current goatcounter.com terms/pricing could not be read, so it is unknown whether hosted use is still restricted to non-commercial users.</p>

<p>Caveats: The live goatcounter.com site was unreachable from this environment because of a proxy error. That is a network failure here, not evidence the site is down.; License tags sit outside newDescription, so the MIT → EUPL-1.2 tag fix needs a manual edit.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Popcorn Metrics — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>www.popcornmetrics.com no longer resolves in DNS, and the Wayback availability API returns no snapshot. Crunchbase and PitchBook report the company closed / out of business, but no official shutdown notice or successor was found. Without official evidence, removal is not yet justified.</p>

<p>http://www.popcornmetrics.com/ — curl: &quot;Could not resolve host: www.popcornmetrics.com&quot;. archive.org/wayback/available returned no archived snapshot.</p>

<p>https://www.crunchbase.com/organization/popcorn-metrics — Search snippet only (not opened): Crunchbase lists Popcorn Metrics as closed; PitchBook lists &quot;Out of Business&quot;. These are third-party sources, not official.</p>

<p>Blocking questions: No official shutdown notice found. Only third-party databases report closure.</p>

<p>Caveats: Network restrictions in this environment blocked many hosts. The DNS failure was observed directly, but a temporary DNS problem cannot be fully excluded.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Upsight — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>www.upsight.com refused connections from this environment. The last Wayback capture (Nov 2022) still shows 2017-era marketing content. Third-party databases disagree: Dealroom says ironSource acquired Upsight; Tracxn calls it deadpooled. No official shutdown, acquisition or successor notice was found.</p>

<p>http://web.archive.org/web/20221113190450/http://www.upsight.com/ — Most recent capture (2022-11-13) shows &quot;Upsight - Omnichannel Marketing &amp; Monetization&quot; with an &quot;Omnichannel Analytics&quot; section and a stale &quot;Going to GDC 2017?&quot; banner. No later captures exist.</p>

<p>Blocking questions: No official evidence of shutdown or of a documented successor. Ownership claims (ironSource vs. Tapjoy) are unverified third-party data.</p>

<p>Caveats: Network restrictions blocked many hosts here, so a live check was not possible.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Honeytracks — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>honeytracks.com refused connections from this environment. The most recent Wayback capture is from Feb 2018 and showed a game analytics product (HoneyTracks – Game Analytics). No official shutdown notice or successor was found.</p>

<p>http://web.archive.org/web/20180224043524/https://honeytracks.com/ — &quot;HoneyTracks – Game Analytics… More than 100 filterable metrics… Get HoneyTracks free edition&quot;. This is the latest available capture.</p>

<p>Blocking questions: No affirmative official evidence of discontinuation or successor.</p>

<p>Caveats: No captures after 2018, which suggests the site has been offline for a long time. But lack of captures is not official evidence of shutdown.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Asking Point — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The official askingpoint.com domain no longer shows the rating widget product. A July 2025 capture shows only an empty placeholder (&#x27;askingpoint.com 2025 Copyright | All Rights Reserved&#x27;), and a Nov 2025 capture returns HTTP 410 &#x27;It is gone!&#x27;. However, I found no official statement that the AskingPoint service or its rating widget was discontinued, and I could not check the live site. Strong signs of abandonment, but no affirmative official discontinuation notice.</p>

<p>https://web.archive.org/web/20250720051824/http://www.askingpoint.com/ — July 2025 capture: the page only says &#x27;askingpoint.com 2025 Copyright | All Rights Reserved. Privacy Policy&#x27;. No product.</p>

<p>https://web.archive.org/web/20251115131640/https://www.askingpoint.com/ — Nov 2025 capture: HTTP 410, &#x27;ERROR It is gone! So be gone 410&#x27;.</p>

<p>Blocking questions: Unresolved: whether AskingPoint officially discontinued the service. No official notice was found, so removal is not confirmed under the contribution standard.</p>

<p>Caveats: My client could not reach askingpoint.com live (proxy 502).; The Wayback Machine has no capture of the specific /mobile-app-rating-widget path near the present date.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Clickmeter — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>I could not reach clickmeter.com from this environment. DNS resolves to AWS CloudFront IPs, but TCP/HTTP connections failed and the proxy returned 502. Third-party sources say ClickMeter was discontinued and that the domain redirects to Rebrandly (same team). I could not read any official ClickMeter or Rebrandly notice, and third parties disagree on the shutdown date (March 2023 vs 2026).</p>

<p>https://dns.google/resolve?name=clickmeter.com&amp;type=A — clickmeter.com resolves to 99.86.101.x addresses (AWS). Direct HTTPS requests from this environment failed (curl 000 / proxy 502).</p>

<p>https://startupstash.com/tools/clickmeter/ — Third-party page: &#x27;ClickMeter has been discontinued. clickmeter.com now redirects to Rebrandly, the branded link platform built by the same team.&#x27; Last verified 5 Nov 2026. Not an official source.</p>

<p>Blocking questions: No official ClickMeter or Rebrandly statement of discontinuation was read. The Rebrandly support article &#x27;ClickMeter to Rebrandly FAQ&#x27; did not show discontinuation text when fetched.; Rebrandly is a related product from the same team, but Rebrandly reportedly concedes it is not a 1:1 replacement. Successor status for a replace is unverified.</p>

<p>Caveats: This environment&#x27;s network failure may be local. An HTTP recheck from another network is needed.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>HasOffers Mobile app tracking — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>mobileapptracking.com no longer serves a site. Authoritative DNS (Route 53) returns no A record for either the apex or www. Search results point to official TUNE and Branch posts saying MobileAppTracking, later renamed Attribution Analytics, was acquired by Branch in September 2018 and its customers migrated to Branch. Those official pages could not be fetched here, so the successor/removal evidence was not read first-hand.</p>

<p>https://dns.google/resolve?name=www.mobileapptracking.com&amp;type=A — No answer (NODATA). Only the SOA from awsdns is returned, for both www.mobileapptracking.com and mobileapptracking.com. The listed URL cannot resolve to a web server.</p>

<p>Blocking questions: The official TUNE/Branch statements could not be read directly. Whether Branch should be listed as the documented successor (replace) or the entry simply removed needs maintainer confirmation from https://www.branch.io/resources/blog/integration-update-a-look-inside-the-branch-tune-migration/ or https://www.tune.com/blog/mobile-app-tracking-by-hasoffers/.</p>

<p>Caveats: Search snippets cite an official TUNE blog note (&#x27;formerly branded as Mobile App Tracking, was acquired by Branch in September 2018&#x27;) and a Branch post on migrating Attribution Analytics customers. Both timed out from this environment.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Codeflash — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The entry is an old marketing slogan, not a description. Codeflash now calls itself &#x27;an AI performance optimizer for your code&#x27; supporting Python, JavaScript, TypeScript and Java, and its homepage sells a performance-engineering service (&#x27;Cut your infra bill by 90%&#x27;). The slogan isn&#x27;t strictly false, since Python is still supported. Unresolved: does a code-optimisation tool belong under &#x27;Developer analytics&#x27;? That determines whether a rewrite or a removal is the right edit.</p>

<p>https://www.codeflash.ai/ — The title is &#x27;Codeflash - Always ship performant code&#x27;. The page describes the codeflash-agent finding optimisations, reviewed by senior performance engineers, with &#x27;ROI guaranteed&#x27;. The listed slogan no longer appears.</p>

<p>https://docs.codeflash.ai/ — The docs say &#x27;Codeflash is an AI performance optimizer for your code... It supports Python, JavaScript, TypeScript, and Java&#x27; and verify speed-ups through benchmarking.</p>

<p>Blocking questions: Relevance to the Developer analytics section is unclear. Codeflash optimises code; analytics isn&#x27;t its main purpose.</p>

<p>Caveats: If kept, a factual description would be something like &#x27;AI code performance optimizer for Python, JavaScript/TypeScript and Java that benchmarks and verifies speedups.&#x27; This wording needs maintainer review.; The entry has no license or hosting tags, unlike its neighbours.</p>

</details>

<h3>GitSpo — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>gitspo.com now returns a 301 redirect to gitwal.com. gitwal is a different-looking product: an archive of all public GitHub events plus trending repositories ranked by social mentions. Nothing on gitwal.com or its about page mentions GitSpo, and I found no official rename or successor notice. GitSpo&#x27;s original GitHub org (gitspo/gitspo-analytics) was last pushed in 2019. Without an official link, a replace is unsupported. Whether the listed URL still represents GitSpo is unresolved.</p>

<p>https://gitspo.com/ — HTTP 301 with Location https://gitwal.com/.</p>

<p>https://gitwal.com/about — The page says &#x27;gitwal archives every public GitHub event&#x27; (about 3.1 billion events since 2011), &#x27;For research use only&#x27;. GitSpo is not mentioned.</p>

<p>https://gitwal.com/ — Title &#x27;GitHub projects developers are talking about — gitwal&#x27;. Repositories are ranked by mentions on X, Bluesky, Reddit, HN and others, with Mentions and Alerts sections.</p>

<p>https://github.com/gitspo/gitspo-analytics — The GitSpo org&#x27;s only public repo, last pushed 2019-03-31, not archived.</p>

<p>Blocking questions: No official evidence that gitwal is GitSpo&#x27;s successor or run by the same owner.; Unknown whether the redirect means GitSpo was discontinued, rebranded, or the domain was sold.</p>

<p>Caveats: gitwal&#x27;s mention tracking and alerts look like GitSpo&#x27;s original pitch (tracking mentions of open-source projects on Twitter, Reddit and HN), but that resemblance isn&#x27;t proof of the same owner or a successor.</p>

</details>

<details>
<summary>54 unresolved keeps</summary>

These entries were not added to the baseline.

<h3>PostHog — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>posthog.com is reachable. The GitHub repo (canonical PostHog/posthog) is active and not archived. The site still lists Product Analytics, Session Replay, Feature Flags and Experiments, so every claim in the description holds. Python is the primary language, and code outside ee/ is MIT Expat.</p>

<p>https://posthog.com/ — The product list includes Product Analytics, Session Replay, Error Tracking, Web Analytics, Feature Flags, Experiments, Surveys, Warehouse and Heatmaps. The headline is now &#x27;Your product&#x27;s context layer&#x27;.</p>

<p>https://api.github.com/repos/PostHog/posthog — full_name is PostHog/posthog. It is not archived, the language is Python, and the last push was 2026-11-10.</p>

<p>https://raw.githubusercontent.com/PostHog/posthog/master/LICENSE — Content outside &#x27;ee/&#x27; is MIT Expat; ee/ has its own license.</p>

<p>Caveats: The source link uses lowercase &#x27;posthog/posthog&#x27;. GitHub resolves this case-insensitively, so it is cosmetic only.; PostHog now emphasizes AI agents and many additional products. These are optional expansions.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Matomo — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Matomo is still a leading open-source, privacy-first analytics platform. The main repo matomo-org/matomo is active, GPL-3.0 and PHP. The org link https://github.com/matomo-org/ resolves to the official org, which links to matomo.org. The Piwik rename note is historical and accurate.</p>

<p>https://matomo.org/ — Title: &#x27;Privacy-first analytics you can trust - Analytics Platform - Matomo&#x27;. The page offers cloud and on-premise options, funnels, A/B testing and heatmaps.</p>

<p>https://api.github.com/repos/matomo-org/matomo — Not archived, license GPL-3.0, language PHP, last push 2026-11-10. Description: &#x27;Matomo is the leading open-source alternative to Google Analytics&#x27;.</p>

<p>https://api.github.com/orgs/matomo-org — Org matomo-org, blog field https://matomo.org.</p>

<p>Caveats: The source link points to the org rather than the core repo. This is acceptable, but https://github.com/matomo-org/matomo would be more specific (optional).</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Kirro — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official homepage confirms every claim: A/B testing, a no-code visual editor, GA4 goals used as test objectives, and &#x27;Kirro&#x27;s script is 9KB.&#x27;</p>

<p>https://kirro.io/ — &#x27;A/B testing made simple&#x27;. &#x27;Visual editor, no code: Click anything on your page and rewrite it.&#x27; &#x27;GA4 goals built in: Your existing conversion goals become test objectives automatically.&#x27; &#x27;Kirro&#x27;s script is 9KB. Most competitors load 100-200KB.&#x27;</p>

<p>Caveats: The 9KB script size is a vendor claim that may change. I did not measure it.; The site now also leads with AI-suggested test ideas. That is an addition and does not contradict the entry.</p>

</details>

<h3>Metabase — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Metabase is still an open-source BI and analytics tool, with self-service BI, a query builder, a SQL editor, dashboards and embedded analytics. The short description is accurate.</p>

<p>https://www.metabase.com/ — Title: &#x27;Open source AI analytics you can verify | Metabase&#x27;. The navigation lists Business Intelligence, Embedded Analytics, Dashboards and reporting, Query builder and SQL editor. It promotes Metabase 65.</p>

<p>Caveats: The suffix tags `©` `SaaS` sit oddly with an open-source product that also offers Metabase Cloud. A tag fix would be a manual maintainer decision.; I did not re-verify the license from the GitHub repo in this pass.</p>

</details>

<h3>Sequential — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official site describes Sequential as session replay and analytics. Its AI judge reads each session, gives verdicts, opens cases for product problems, and hands them to the user&#x27;s coding agent to fix. This fits the entry&#x27;s &#x27;AI judge that reviews each session and lists the findings to fix&#x27;.</p>

<p>https://www.usesequential.com/ — &#x27;Session replay and analytics for teams with a website or app&#x27;. Step 02 Judge: &#x27;Sequential&#x27;s AI reads each session and answers your questions about it&#x27;. Step 04 Case opens a case per product problem, and Step 05 has your agent connect over MCP to write the fix.</p>

<p>Caveats: The product now stresses handing fixes to external AI coding agents. That could be added as an optional expansion, but the current wording is not wrong.</p>

</details>

<h3>Statcounter — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Statcounter is still an active real-time web analytics service. Its own pages say it has run since 1999 or 2000 and was &#x27;one of the first website analytics tools available&#x27;, which supports the &#x27;ORIGINAL&#x27; claim.</p>

<p>https://statcounter.com/statcounter-review — Search excerpt: &#x27;Founded in 2000 and one of the first website analytics tools available, Statcounter has grown from ... a website hit counter to a fully fledged analytics tool.&#x27;</p>

<p>https://statcounter.com/about/mission/ — Search excerpt: the service has run since 1999 and is a real-time web analytics service used on over 1 million websites.</p>

<p>Caveats: Direct fetches of statcounter.com failed in this environment. The evidence is search excerpts of official pages.; Optional: the shouted &#x27;ORIGINAL&#x27; could be toned down, but it is not factually wrong.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>parse.ly — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>WordPress VIP acquired Parse.ly in 2021, and it remains an active real-time content analytics product (Parse.ly HUD launched September 2026). Wikipedia and WPVIP&#x27;s partner page still list parse.ly as its site. The description is accurate.</p>

<p>https://wpvip.com/capabilities/content-intelligence-and-analytics/ — Search excerpt: &#x27;Parse.ly by WordPress VIP is a content intelligence and analytics platform designed specifically for publishers, marketers, and content teams&#x27;, with live dashboards and sub-second processing.</p>

<p>https://www.parse.ly/wpvip-acquisition/ — Search result: Parse.ly&#x27;s own page announcing it was joining WordPress VIP.</p>

<p>https://customerhub.wpvip.com/lobby/2026/09/01/new-feature-parse-ly-hud/ — Search result: a September 2026 Parse.ly HUD feature announcement shows active development.</p>

<p>Caveats: Direct fetches of www.parse.ly failed in this environment, so I could not confirm whether the homepage now redirects to wpvip.com.; Optional: the name could be capitalised &#x27;Parse.ly&#x27; to match official branding.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>LiveSession — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>LiveSession is an active product analytics platform built around session replay, with heatmaps and funnels. It has 2026 blog posts and an active changelog. &#x27;session replay user analytics&#x27; is accurate.</p>

<p>https://livesession.io/features — Search excerpt: a product analytics platform combining session replays, heatmaps, funnels and dashboards.</p>

<p>https://livesession.io/updates/ — Search result: the changelog shows recent session-player and error-click updates.</p>

<p>https://livesession.io/blog — Search excerpt: blog posts dated June and September 2026.</p>

<p>Caveats: Direct fetches of livesession.io failed in this environment. The evidence is search excerpts of official pages.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Edalitics — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Edalitics is still an open-source BI/dashboarding platform with source in jortilles/EDA and a hosted SaaS offering. The description and tags are supported.</p>

<p>https://raw.githubusercontent.com/jortilles/EDA/master/README.md — &#x27;Edalitics ... is an open-source analytics and dashboarding platform created by Jortilles&#x27;. Its stack is Node.js, TypeScript and Angular. &#x27;You can use Edalitics as a SAS service at https://www.edalitics.com/.&#x27;</p>

<p>https://www.edalitics.com — Live (Spanish). It offers a cloud BI tool and links an Open Source section.</p>

<p>Caveats: The license was not re-read from the LICENSE file.</p>

</details>

<h3>Deepnote — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The description matches current official wording. The GitHub README says &#x27;Deepnote is a drop-in replacement for Jupyter&#x27; and positions it as an AI-era data notebook.</p>

<p>https://raw.githubusercontent.com/deepnote/deepnote/main/README.md — &#x27;Deepnote is a drop-in replacement for Jupyter ... adds an AI agent, sleek UI, new block types, and native data integrations.&#x27; It covers Deepnote Open Source and Deepnote Cloud.</p>

<p>https://deepnote.com/ — Live. &#x27;Collaborative analytics &amp; data science notebook&#x27;.</p>

<p>Caveats: The license was not re-read from the LICENSE file.</p>

</details>

<h3>Klinky — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Klinky is still an A/B testing link shortener that splits one link between two destinations and tracks clicks.</p>

<p>https://klinky.io — &#x27;Split one link between two destinations.&#x27; Under &#x27;KLINKY DOES&#x27;: &#x27;Split traffic by percentage... Track clicks so you can see traffic volume.&#x27;</p>

<p>Caveats: Klinky explicitly does not claim conversion or significance analysis. That&#x27;s consistent with the description.</p>

</details>

<h3>rrweb — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>rrweb is still an MIT-licensed open-source library for recording and replaying the DOM and user interactions. rrweb.com is now the official site, which also hosts the commercial &#x27;rrweb cloud&#x27; and the docs.</p>

<p>https://raw.githubusercontent.com/rrweb-io/rrweb/main/README.md — &#x27;rrweb refers to record and replay the web, a tool for recording and replaying users interactions&#x27;. Packages include snapshot, record, replay and player. It links rrweb.com as the guide and hosted cloud.</p>

<p>https://rrweb.com — Live. &#x27;#1 Open Source Session Replay&#x27;. Also sells a hosted session-replay service.</p>

<p>Caveats: The rrweb.com landing page focuses on the commercial cloud. github.com/rrweb-io/rrweb is the library&#x27;s canonical source and is already linked.</p>

</details>

<h3>Countly — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The count.ly site could not be fetched (the sandbox proxy returned 502), but the official repo confirms the description: real-time analytics across mobile and web, crash/error reporting and push notifications. The license is AGPL-3.0 with a modified Section 7.</p>

<p>https://raw.githubusercontent.com/Countly/countly-server/master/README.md — Analytics across &#x27;mobile, web, desktop&#x27; in &#x27;real time&#x27;. &#x27;Crash/error reporting for iOS, Android...&#x27;. &#x27;Rich and interactive push notifications for iOS and Android&#x27;. &#x27;licensed under AGPL-3.0 with modified Section 7&#x27;.</p>

<p>https://raw.githubusercontent.com/Countly/countly-server/master/LICENSE.md — &#x27;Countly is provided under AGPL-3.0 with modified Section 7&#x27; (branding requirements).</p>

<p>https://github.com/countly — The org page is reachable and shows activity dated 2026-11-10.</p>

<p>Caveats: count.ly and countly.com were not reachable from the research environment (proxy 502, though DNS resolves). Whether count.ly redirects to countly.com is unconfirmed. The README links countly.com as the website.; The README says Countly Lite is under an &#x27;open-source, non-commercial license&#x27; while also stating AGPL-3.0 with a modified Section 7. The AGPL tag is supported, but the maintainer may want to note the modification.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>OpenPanel — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The catalog description matches the official GitHub repository description word for word, and the README documents self-hosting. The site could not be fetched, but the repo is authoritative for the claims made.</p>

<p>https://github.com/Openpanel-dev/openpanel — Repo description: &#x27;OpenPanel is an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting.&#x27; The page references AGPL-3.0.</p>

<p>https://raw.githubusercontent.com/Openpanel-dev/openpanel/main/README.md — &#x27;An open-source alternative to Mixpanel&#x27;. Has a &#x27;Self-hosting&#x27; section linking openpanel.dev/docs/self-hosting.</p>

<p>Caveats: openpanel.dev was not reachable from the research environment (proxy failure, though DNS resolves).; The entry has a `©` tag although the repo appears to be AGPL-3.0, and the `EU` tag was not verified. These are tag issues outside the description scope that the maintainer may want to check.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Vectr4 — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Vectr4 is live and is still self-hosted analytics. It ships as a Docker Compose deployment, and its browser SDK collects pageviews, custom events and funnels. The listed description holds. The site now calls itself &#x27;product analytics&#x27; rather than &#x27;web analytics&#x27;, but pageview tracking keeps it within Website analytics. The © tag fits a paid one-time licence.</p>

<p>https://vectr4.com/ — Title &#x27;Vectr4 | Self-Hosted Product Analytics for Indie Hackers&#x27;. Lists &#x27;Docker Compose deployment&#x27;, &#x27;Caddy, PostgreSQL, ClickHouse, and Redis&#x27;, &#x27;Browser SDK: pageviews, custom events, and identify calls&#x27;, and Funnels, Session summaries and User journeys. Pricing is a &#x27;€79 one-time license payment&#x27; and buyers get source-code download access &#x27;for review&#x27;.</p>

<p>Caveats: The software was not run.; The site positions the product as product analytics for SaaS founders. A maintainer may want to clarify the wording, but the current description is not false.</p>

</details>

<h3>ShieldLabs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Both linked URLs load. ShieldLabs now presents itself mainly as fraud and abuse prevention, but its current product menu still lists Bot Detection, Identification (&#x27;Recognize every returning visitor&#x27;), Risk Signals and Risk Analytics (&#x27;Understand real traffic&#x27;). The homepage also promises to show &#x27;which users and traffic sources are trustworthy&#x27;. So every capability in the description is still offered, and the Anonymity Checker link works and matches its label.</p>

<p>https://shieldlabs.ai/ — Title &#x27;Fraud Detection and Prevention for Web Apps | ShieldLabs&#x27;. The menu includes Bot Detection, Identification, Risk Signals, Risk Scoring and Risk Analytics (&#x27;Understand real traffic&#x27;). Under &#x27;Trust your metrics&#x27; it says: &#x27;See which users and traffic sources are trustworthy&#x27;.</p>

<p>https://demo.shieldlabs.ai/anonymity-checker — A free Anonymity Checker that shows a 0–100 Risk Score, Device ID, Visitor ID, and VPN, proxy, Tor and anti-detect browser signals.</p>

<p>Caveats: The site&#x27;s main positioning has moved toward fraud prevention (multi-accounting, account takeover). Whether it still fits Website analytics is for the maintainer to judge. The traffic-analytics features in the entry are still offered.</p>

</details>

<h3>SiteData — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>SiteData is live. Its pages offer website traffic and audience estimates, Reverse AdSense lookup, Google Ads advertiser analysis, and Domain Rating (in the meta description and in DR-ranked lists). All four listed capabilities are present.</p>

<p>https://sitedata.dev/ — Meta description: &#x27;Research website traffic, SEO keywords, Google Ads, AdSense IDs, DR, WHOIS and competitor signals&#x27;. Sections include Reverse AdSense Lookup, Advertiser Lookup, Google Ads Analysis, Audience Intelligence (visit snapshots), and rankings &#x27;by Domain Rating&#x27;.</p>

<p>Caveats: The description starts with a lowercase word. That is a style point only.; The site also offers keywords, WHOIS, MCP, a CLI and browser extensions. These are additions, not corrections.</p>

</details>

<h3>LLM Pulse — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>LLM Pulse tracks ChatGPT, Perplexity, Google AI Mode, AI Overviews and Gemini as core models, with Claude, Copilot, Grok and others as add-ons. It offers prompt tracking, citation sources, sentiment analysis and competitor share of voice. The listed claims are supported.</p>

<p>https://llmpulse.ai/ — Title &#x27;LLM Pulse: All-in-One AI Search Visibility &amp; Reputation Platform&#x27;. &#x27;Tracked AI Models: ChatGPT, Perplexity, Google AI Mode, AI Overviews, Gemini, Grok Add-on, Claude Add-on, Copilot Add-on…&#x27; Features include Prompt Tracking, Citation Sources and Sentiment Analysis.</p>

<p>Caveats: The site also offers AI-crawler analytics and GEO writing tools. These are additions, not corrections.</p>

</details>

<h3>MessGEO — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>MessGEO&#x27;s Prompt Tracking runs measurements every day across ChatGPT, Gemini, Copilot, AI Mode, AI Overviews and Perplexity. It reports share of voice and tracks up to 15–25 competitors. Every listed engine and feature is confirmed.</p>

<p>https://messgeo.com/tools/prompt-checker/ — &#x27;Measured across these AI surfaces: ChatGPT Gemini Copilot AI Mode AI Overviews Perplexity&#x27;. &#x27;On Starter, ChatGPT, Gemini and AI Mode are fixed. Pro also opens Copilot, AI Overviews and Perplexity&#x27;. &#x27;How often is it measured? Every day, automatically.&#x27;</p>

<p>https://messgeo.com/pricing/ — Starter costs €49/month: &#x27;Automatic daily measurement&#x27;, &#x27;Share of voice, average position, win rate, sentiment score&#x27;, and &#x27;Tracked competitors Up to 15&#x27; (25 on Pro).</p>

<p>Caveats: Copilot and AI Overviews are only available on the Pro plan.</p>

</details>

<h3>Umami — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Umami repo is active (pushed 2026-11-10, MIT, not archived) and describes a privacy-first analytics platform with no cookies, self-hosted or cloud. umami.is could not be fetched from this sandbox (proxy 502). Search results from umami.is still show it presenting itself as a privacy-focused Google Analytics alternative that is GDPR compliant by default. The description stands.</p>

<p>https://github.com/umami-software/umami — GitHub API: umami-software/umami, MIT, not archived, pushed 2026-11-10, homepage https://umami.is. Description: &#x27;privacy-first web and product analytics platform… No cookies, no surveillance, self-hosted or in the cloud.&#x27;</p>

<p>https://umami.is/compare/google-analytics — Seen only via search result: &#x27;Umami vs. Google Analytics&#x27; page. Snippets say Umami does not use cookies or collect personal data and is GDPR/CCPA compliant by default.</p>

<p>https://umami.is/blog/gdpr-compliant-website-analytics — Seen only via search result: official blog page titled &#x27;GDPR Compliant Website Analytics&#x27;.</p>

<p>Caveats: umami.is was not fetched directly; the sandbox proxy returned 502 and WebFetch failed. The GDPR wording was confirmed only through search snippets of official pages.; GitHub reports the language as TypeScript, while the entry tags JavaScript. That is a tag issue for the maintainer, outside the prose.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>OpenPanel — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The OpenPanel repo&#x27;s official description matches the entry word for word: &#x27;an open-source web and product analytics platform, an open-source alternative to Mixpanel with optional self-hosting&#x27;. The repo is active (pushed 2026-11-09). However, the entry&#x27;s `©` tag is wrong: the GitHub API reports AGPL-3.0. This tag needs a maintainer edit.</p>

<p>https://github.com/Openpanel-dev/openpanel — GitHub API: Openpanel-dev/openpanel, license AGPL-3.0, TypeScript, not archived, pushed 2026-11-09, homepage https://openpanel.dev. Its description is identical to the catalog text.</p>

<p>https://raw.githubusercontent.com/Openpanel-dev/openpanel/main/README.md — &#x27;An open-source alternative to Mixpanel&#x27;. Features include funnels, cohorts, session replay, &#x27;Self-Hosted: Full control over your data&#x27;, and &#x27;Cookieless tracking and GDPR compliance&#x27;.</p>

<p>Caveats: openpanel.dev could not be fetched from this sandbox (proxy 502). Evidence comes from the official repo.; The `©` licence tag conflicts with GitHub&#x27;s AGPL-3.0. Tags are outside newDescription, so the maintainer must edit it by hand.; The `EU` tag (EU hosting) was not verified.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>RudderStack — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>rudder-server is active (pushed 2026-11-10). Its README still calls RudderStack &#x27;the leading open source Customer Data Platform&#x27;, &#x27;Warehouse-first&#x27; and &#x27;Segment API-compatible&#x27;, so the prose matches the official source. However, the repo&#x27;s LICENSE is now the Elastic License 2.0 (ELv2), not AGPL-3.0. The entry&#x27;s `AGPL-3.0` tag is out of date and needs a manual maintainer edit.</p>

<p>https://raw.githubusercontent.com/rudderlabs/rudder-server/master/LICENSE — The file begins &#x27;Elastic License 2.0 (ELv2)&#x27;.</p>

<p>https://raw.githubusercontent.com/rudderlabs/rudder-server/master/README.md — Licence badge: &#x27;ELv2&#x27;. &#x27;As the leading open source Customer Data Platform (CDP), RudderStack provides data pipelines…&#x27;. Key features include &#x27;Warehouse-first&#x27; and &#x27;Segment API-compatible&#x27;. Tagline: &#x27;The Customer Data Platform for Developers&#x27;.</p>

<p>https://github.com/rudderlabs/rudder-server — GitHub API: rudderlabs/rudder-server, not archived, Go, homepage https://www.rudderstack.com/, description &#x27;Privacy and Security focused Segment-alternative&#x27;.</p>

<p>Caveats: rudderstack.com could not be fetched from this sandbox (proxy 502/WebFetch failure). The URL&#x27;s continued validity rests on the repo&#x27;s homepage field.; ELv2 is usually classed as source-available rather than OSI open source. The entry&#x27;s &#x27;open-source alternative&#x27; wording repeats RudderStack&#x27;s own claim. The maintainer may want to soften it when fixing the `AGPL-3.0` tag to ELv2.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Metrical — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>metrical.xyz is live and its headline matches the entry verbatim: &#x27;A privacy-first web analytics tool for everyone.&#x27; It states it uses no cookies and collects no personal data.</p>

<p>https://metrical.xyz/ — HTTP 200. Headline &#x27;A privacy-first web analytics tool for everyone.&#x27;; &#x27;We don&#x27;t use cookies&#x27;; &#x27;we don&#x27;t collect any personal data (like IP addresses)&#x27;; 5 metrics: pages, sources, country, language, device type.</p>

<p>Caveats: Could not verify pricing or account signup flow.</p>

</details>

<h3>Fathom — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Fathom homepage confirms a hosted, privacy-first Google Analytics alternative with anonymous pageview tracking that does not collect or store personal data. Description accurate.</p>

<p>https://usefathom.com/ — Read via r.jina.ai reader (direct fetch blocked by sandbox proxy). &#x27;Analytics without the cookies&#x27;; &#x27;anonymous pageview tracking that doesn&#x27;t collect or store personal data&#x27;; &#x27;From $15/month&#x27;.</p>

<p>Caveats: Direct fetch failed with a proxy CONNECT 502 in this environment; content read via a third-party reader proxy.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>PageLens — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The PageLens homepage confirms every claim: cookieless analytics, EU hosting in Amsterdam, Stripe/Paddle revenue by source, and an AI Visibility feature that tracks what ChatGPT, Claude and Perplexity read, use in answers and send as visits. The demo link redirects to an app share URL.</p>

<p>https://pagelens.io/ — Says: &#x27;See what ChatGPT, Claude and Perplexity read, quote and send you, and which sources turn into paying customers. Cookieless analytics with Stripe and Paddle revenue&#x27;. Also &#x27;EU-hosted cloud, Amsterdam&#x27;, &#x27;No cookies&#x27;, and an AI Visibility section with Read, Used in answers, Visits and Revenue.</p>

<p>https://pagelens.io/demo — Redirects to https://app.pagelens.io/#/share/demo/main, a JavaScript single-page app. The page title loads; dashboard content was not rendered without a browser.</p>

<p>Caveats: The demo content was not rendered because it needs JavaScript.</p>

</details>

<h3>Lomen — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Lomen homepage confirms the entry: a cookie-free script, a built-in AI chat (Lomen AI) for questions about your traffic, revenue from Stripe, Shopify, Lemon Squeezy and Polar (plus Paystack) on the same chart as visitors, and ChatGPT, Claude and Perplexity tracked as sources. The demo is live.</p>

<p>https://lomenanalytics.com/ — Says: &#x27;One cookie-free script&#x27;, &#x27;Connect your payment provider (Stripe, Shopify, Lemon Squeezy, Polar or Paystack) and Lomen draws your income on the same chart as your visitors&#x27;, &#x27;Lomen AI is a chat next to your dashboard: ask about your traffic in plain words&#x27;, and &#x27;ChatGPT, Claude, Perplexity and Gemini counted as sources of their own&#x27;.</p>

<p>https://lomenanalytics.com/demo — An interactive demo of the Lomen dashboard using illustrative sample data.</p>

<p>Caveats: The product is labeled &#x27;Free during the beta&#x27;, so pricing may change.; Paystack is an extra payment provider. Its absence from the entry is not an error.</p>

</details>

<h3>DevDome Analytics — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The DevDome homepage and the plugin repo confirm cookieless WordPress analytics that counts humans and bots/AI crawlers separately, with a free plan. The plugin is GPLv2-or-later, which matches the GPL-2.0 tag.</p>

<p>https://devdome.com/ — Says: &#x27;DevDome shows pageviews and clicks from people and from bots as separate numbers. See your visitors, see which bots and AI crawlers come to your site&#x27;. Also &#x27;Free plan: 50,000 human pageviews per month&#x27;, &#x27;Cookieless by default&#x27; and &#x27;Free WordPress plugin&#x27;.</p>

<p>https://github.com/DevDomeFamily/devdome-analytics — README: &#x27;cookieless website visitor tracking and traffic sources with human vs bot traffic split. Google Analytics alternative for WordPress.&#x27; readme.txt: &#x27;License: GPLv2 or later&#x27;, &#x27;Stable tag: 1.1.8&#x27;. It notes that the optional &#x27;Track Returning Visitors&#x27; setting is off by default.</p>

<p>Caveats: The plugin can optionally recognize returning visitors when the user turns that on. The default is cookieless.; Full reports require the hosted DevDome service, and a free account is required.</p>

</details>

<h3>twelvebit — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The twelvebit homepage confirms privacy-friendly analytics with revenue attribution by channel, a realtime globe, funnels, journeys and an MCP server. The demo is live.</p>

<p>https://twelvebit.app/ — Says: &#x27;twelvebit is privacy-friendly web analytics with revenue attribution. ... you see revenue by channel, campaign and page.&#x27; The navigation lists &#x27;Realtime globe Funnels Journeys Ask and MCP&#x27;. Plans include &#x27;REST API, the CLI and the MCP server&#x27;. &#x27;data stays in the EU&#x27;.</p>

<p>https://twelvebit.app/demo — Live demo dashboard with Overview, Live, Revenue, Funnels and People tabs.</p>

<p>Caveats: The tracker sets two first-party cookies by default (&#x27;_tb_vi...&#x27;), and users can choose to disable them. The entry says only &#x27;privacy-friendly&#x27;, not cookieless, so it stays accurate.</p>

</details>

<h3>Rybbit Analytics — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Rybbit&#x27;s prose is accurate: cookieless, GDPR-focused, the cloud runs on Hetzner servers in Germany, and self-hosting is supported. Metadata caveat: the repo rybbit-io/rybbit is AGPL-3.0, but the catalog tags it `©`. A maintainer may want to fix this tag by hand. rybbit.com was not reachable directly here (proxy 502), so archived copies were used.</p>

<p>https://web.archive.org/web/20261102194650/https://rybbit.com/ — Archived 2026-11-02: &#x27;Rybbit is open-source, cookieless analytics. No consent banner needed. EU-hosted cloud&#x27;. Lists &#x27;No cookies GDPR &amp; CCPA ... Self-hosting Open source&#x27;.</p>

<p>https://web.archive.org/web/20260920204222/https://rybbit.com/security — &#x27;Rybbit is hosted on Hetzner servers located in Germany, within the European Union.&#x27;</p>

<p>https://github.com/rybbit-io/rybbit — README: &#x27;Open Source Web &amp; Product Analytics&#x27;, &#x27;No cookies &amp; privacy friendly&#x27;, a self-hosting guide, and &#x27;License (AGPL-3)&#x27;. LICENSE.md is GNU AGPL v3.</p>

<p>Caveats: The live rybbit.com was unreachable because of a proxy CONNECT 502 here, so evidence comes from Wayback snapshots from Sept–Nov 2026 and GitHub.; The `©` tag vs the AGPL-3.0 license is a metadata issue outside newDescription.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>OpenPanel — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>OpenPanel&#x27;s prose is accurate: an open-source web and product analytics platform, described as an open-source alternative to Mixpanel, that can be self-hosted. Metadata caveat: the repo is AGPL-3.0 and an EU-hosted cloud is offered, but the catalog tags it `©` with no `SaaS`. A maintainer may want to fix the tags by hand. openpanel.dev was not reachable directly here.</p>

<p>https://github.com/Openpanel-dev/openpanel — README: &#x27;An open-source alternative to Mixpanel&#x27; and &#x27;Openpanel is an open-source web and product analytics platform&#x27;. Also &#x27;Self-Hosted: Full control&#x27;, &#x27;Cookieless tracking&#x27;. LICENSE.md is GNU AGPL v3.</p>

<p>https://web.archive.org/web/20261109102223/https://openpanel.dev/ — Archived 2026-11-09: &#x27;The open-source Mixpanel alternative, cookie-less, in our EU cloud or on your own servers&#x27;. &#x27;Self-host for free Docker Compose&#x27; and &#x27;EU cloud Hosted in the EU, GDPR compliant, from $2.50 a month&#x27;.</p>

<p>Caveats: The live openpanel.dev was unreachable because of a proxy CONNECT 502 here, so a Wayback capture from the previous day was used.; OpenPanel now also has AI observability; this is an addition, not a correction.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Mouseflow — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Mouseflow is still a behavior analytics SaaS offering heatmaps, session replay and related tools. &#x27;live analytics and heatmaps&#x27; is brief but not contradicted by current material, so it stays.</p>

<p>https://web.archive.org/web/20261019234113/https://mouseflow.com/ — Archived 2026-10-19. Title: &#x27;Mouseflow | Behavior analytics for optimal website UX&#x27;. Features: &#x27;Session Replay Website Heatmaps Friction Detection Conversion Funnels Journey Analytics Form Analytics Feedback Surveys&#x27;, plus Mouseflow AI and MCP.</p>

<p>Caveats: The live mouseflow.com was unreachable from this environment (proxy 502), so the http→https redirect could not be checked. Updating the URL to https://mouseflow.com/ would be a low-risk optional cleanup.; No &#x27;live&#x27; feature was named explicitly in the extracted text. &#x27;Live analytics&#x27; is loose wording, not a confirmed false claim.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Segment — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Segment is still Twilio&#x27;s customer data platform. An archived capture from Oct 29, 2026 shows segment.com 302-redirecting to twilio.com/en-us/segment. Collecting data once and routing it to many analytics destinations is its core function, so the description and section remain accurate. The redirect is temporary (302), so the segment.com URL can stay.</p>

<p>http://web.archive.org/web/20261029045535id_/https://segment.com/ — Archived 2026-10-29 response: 302 Found → https://www.twilio.com/en-us/segment.</p>

<p>Caveats: Direct and WebFetch access to segment.com and twilio.com failed in this environment, so the current product page was not read. Description accuracy relies on Segment&#x27;s well-established function and the redirect.; Optionally, the URL could change to https://www.twilio.com/en-us/segment if the maintainer wants the post-redirect location.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Appsflyer — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>AppsFlyer is live. A capture from Nov 4, 2026 shows &quot;AppsFlyer | Modern Marketing Cloud&quot; with Marketing Analytics, Product Analytics, attribution and deep linking. &quot;All-in-one marketing tool with analytics&quot; remains accurate.</p>

<p>http://web.archive.org/web/20261104005837id_/https://www.appsflyer.com/ — 200. Title &quot;AppsFlyer | Modern Marketing Cloud&quot;; meta &quot;Unify measurement, deep linking, data collaboration, and AI across mobile, web, CTV, console…&quot;; nav includes Marketing Analytics and Product Analytics.</p>

<p>Caveats: Direct connection to appsflyer.com failed in this environment, so the page was read via a 2026-11-04 Wayback capture.; The http:// URL could be modernized to https://www.appsflyer.com/. This is optional.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Tapstream — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Tapstream&#x27;s site was online as of a Sept 30, 2026 archive capture. It is titled &quot;Tapstream - App Marketing Cloud&quot; and lists Analytics (web and app traffic insights) alongside deep links, app invites and landers. &quot;User lifecycle analytics&quot; is vague but not contradicted.</p>

<p>http://web.archive.org/web/20260930082640/https://www.tapstream.com/ — &quot;Tapstream - App Marketing Cloud… Tapstream powers user acquisition and engagement for the world&#x27;s top apps… Analytics: Unparalleled insights into web and app traffic&quot;; SDKs for iOS, Android, Unity, etc.</p>

<p>Caveats: Direct connection to tapstream.com failed here, so liveness relies on the 2026-09-30 capture.; Some site content looks dated; active product maintenance was not verified.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>AdMapix — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official site and pricing page support each claim in the description: AI ad creative intelligence (search across 200M+ ads on Meta, TikTok, Google and more), app market research with app search, ranking queries, and download and revenue datasets across 170+ markets. It fits App store analytics as a market-intelligence tool.</p>

<p>https://www.admapix.com/ — &#x27;AdMapix — AI Ad Creative Intelligence&#x27;. Says &#x27;Analyze 200M+ ads across Meta, TikTok, Google &amp; 100+ channels&#x27;, has an app search demo, and claims &#x27;170+ markets &amp; categories&#x27;.</p>

<p>https://www.admapix.com/pricing — Credits cover &#x27;image/video creative searches... ranking queries, app detail views, download and revenue datasets, market distribution analysis, AI creative analysis, and AI competitor reports&#x27;. Paid plans run from $19.90 to $89.90 per month.</p>

<p>Caveats: I did not test the accuracy or coverage of the data.; The product&#x27;s focus is mainly ad creative intelligence. App market research is secondary, but the description already says both.</p>

</details>

<h3>Localytics — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Localytics was spun out of Upland in 2025 and now presents itself mainly as an AI-implementation firm for CRM marketing. Its official Platform page still lists Mobile Analytics, Push Messaging and In-App Messaging with real-time event-triggered messaging, so the core claims (real-time mobile analytics, in-app and push) are still supported. &#x27;Fast and beautiful&#x27; is promotional but not a factual error.</p>

<p>https://web.archive.org/web/20261101/https://localytics.com/platform — Nov 2026 capture: &#x27;Behavioral data collection, multi-channel messaging, journey orchestration, and predictive analytics&#x27;. Lists &#x27;Mobile Analytics&#x27;, &#x27;Push Messaging&#x27;, &#x27;In-App Messaging&#x27;, &#x27;Inbox Messaging&#x27; and &#x27;Real-time event-triggered messaging&#x27;.</p>

<p>https://web.archive.org/web/20261101/https://localytics.com/about — &#x27;Localytics is an AI-implementation firm for enterprise marketing organizations... We have a long history as a mobile analytics and engagement platform.&#x27;</p>

<p>Caveats: My client could not reach localytics.com live (proxy 502). The evidence is from Wayback captures dated Oct/Nov 2026.; The company&#x27;s main positioning has moved toward AI-agent CRM services. The maintainer may want to watch whether the self-serve platform stays available.; The URL uses http://www. The canonical host appears to be https://localytics.com/.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>GameAnalytics — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>GameAnalytics is still an active game analytics platform. The Nov 2026 capture shows AnalyticsIQ, SDKs and integrations, data export and warehouse, and support for mobile, Roblox, VR/AR and PC/Console. The entry&#x27;s terse description is still accurate, and &#x27;leading&#x27; is ordinary marketing language.</p>

<p>https://web.archive.org/web/20261102073315/https://www.gameanalytics.com/ — Nov 2, 2026 capture: products AnalyticsIQ, PipelineIQ (data export/API), MarketIQ, SDKs &amp; Integrations, AI Agent/MCP Server. Platforms: Mobile, Roblox, VR/AR, PC/Console.</p>

<p>https://github.com/GameAnalytics/GA-SDK-ANDROID — The official SDK repository is reachable (HTTP 200).</p>

<p>Caveats: My client could not reach gameanalytics.com live (proxy 502). The evidence is from a Wayback capture dated Nov 2, 2026.; The listed URL uses http://. The site serves https://www.gameanalytics.com/.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>OpenPanel — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official site and README confirm the description word for word: &#x27;An open-source web and product analytics platform&#x27;, &#x27;The open-source alternative to Mixpanel&#x27;, self-hostable, and EU hosted. It also has Swift, Kotlin and React Native SDKs, which fits the Mobile analytics section. The description is accurate. Separately, the `©` (proprietary) tag conflicts with the project&#x27;s open-source status. Tags are outside the scope of a description edit, so I flag this for the maintainer.</p>

<p>https://web.archive.org/web/20261101/https://openpanel.dev/ — Nov 2026 capture: &#x27;The open-source alternative to Mixpanel. An open-source web and product analytics platform...&#x27; Also lists &#x27;GDPR compliant&#x27;, &#x27;EU hosted&#x27;, &#x27;Cookie-less tracking&#x27;, &#x27;Open-source&#x27;.</p>

<p>https://raw.githubusercontent.com/Openpanel-dev/openpanel/main/README.md — &#x27;Openpanel is an open-source web and product analytics platform...&#x27; Features include Self-Hosted and Multi-Platform: &#x27;Web, mobile (iOS/Android), and server-side tracking&#x27;. The SDKs listed are Web, Swift, Kotlin and ReactNative.</p>

<p>Caveats: My client could not reach openpanel.dev live. I used a Wayback capture and the GitHub README.; I could not fetch the LICENSE file at the path I tried (404), so I have not verified the exact license name. The `©` tag and the missing license/source-code link may need correcting by hand.; OpenPanel is web- and product-focused. Its placement under Mobile analytics is supported by its mobile SDKs.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Adjust — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Adjust is still an active mobile measurement and attribution platform with campaign measurement and analytics (Datascape). Its SDKs are open source (MIT) on GitHub. The description is accurate and fits Attribution tracking.</p>

<p>https://web.archive.org/web/20261014041748/https://www.adjust.com/ — Oct 2026 capture: &#x27;Measure: Unlimited measurement on mobile, web, CTV, PC, and console. Analyze: AI analytics and reporting... in Datascape&#x27;. Also lists ROI Measurement, Incrementality and Fraud Prevention.</p>

<p>https://raw.githubusercontent.com/adjust/android_sdk/master/README.md — Official &#x27;Adjust SDK for Android&#x27; README: &#x27;Distributed under the MIT license.&#x27;</p>

<p>Caveats: My client could not reach adjust.com live (proxy 502). I used a Wayback capture from Oct 2026.; The listed URL is http://adjust.com/. The canonical host appears to be https://www.adjust.com/.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>mbuzz — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>mbuzz is a live server-side multi-touch attribution SaaS. It advertises native SDKs for Ruby, Node, Python and PHP and a SQL-like Attribution DSL. Public SDK repositories exist under the mbuzzco GitHub organization.</p>

<p>https://mbuzz.co/ — Title &#x27;mbuzz | Server-Side Multi-Touch Attribution&#x27;. Text includes &#x27;Native SDKs for Ruby, Node, Python, and PHP. GTM and REST also available&#x27; and &#x27;mbuzz also ships a SQL-like Attribution DSL&#x27;.</p>

<p>https://mbuzz.co/docs/getting-started — Docs describe &#x27;Server-side multi-touch attribution tracking&#x27;, with Ruby and Node.js client library tabs and Attribution Models (AML).</p>

<p>https://github.com/mbuzzco — The org lists the public repos mbuzz-ruby, mbuzz-node, mbuzz-python and mbuzz-php (each returned HTTP 200), plus mbuzz-sgtm, mbuzz-shopify and mbuzz-wp.</p>

<p>https://raw.githubusercontent.com/mbuzzco/mbuzz-ruby/HEAD/LICENSE.txt — The MIT License (MIT).</p>

<p>Caveats: I confirmed an MIT license only for the Ruby SDK. Licenses for the Node, Python and PHP repos were not individually confirmed, but the repos are public.</p>

</details>

<h3>Appy — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Appy is live and offers smart/deep links. Its pricing page confirms that the native iOS/Android SDK (deferred deep linking, install attribution, in-app events and revenue) is an Enterprise feature. The description is accurate.</p>

<p>https://appy.to/ — Title &#x27;Appy | Smart Links, Dynamic QR Codes &amp; Analytics&#x27;. Offers universal/deep links with an analytics dashboard.</p>

<p>https://appy.to/pricing — The Enterprise tier lists &#x27;Native iOS and Android SDK&#x27;, &#x27;Deferred deep linking&#x27;, &#x27;Install attribution for every link&#x27;, and &#x27;In-app events and revenue per link&#x27;. Also says &#x27;Business includes the REST API and the MCP server, and Enterprise adds the mobile SDK.&#x27;</p>

<p>Caveats: The product has added QR codes, a REST API and an MCP server. These are additions and do not require a correction.</p>

</details>

<h3>SocialBu — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>SocialBu is live. It describes itself as an AI-powered social media management tool with publishing/scheduling, listening, automation and analytics modules, which matches the description.</p>

<p>https://socialbu.com/ — HTTP 200. Title &#x27;SocialBu: AI-Powered Social Media Management Tool&#x27;. Product menu lists AI &amp; Agents, Publish (schedule), Listen (track keywords, mentions), Automate (RSS, webhooks, auto replies) and Analyze (post, account and network performance).</p>

</details>

<h3>ClickTrail — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The npm package @vizuh/clicktrail exists (latest 0.1.0, MIT, repository vizuh/clicktrail-js). The source repo is live. Its README describes a deterministic engine that parses UTMs, referrers and click IDs, applies first/last-touch rules, and persists to first-party storage. The fetch-incomplete flag came from npm returning 403 to page fetches, not from a dead project.</p>

<p>https://registry.npmjs.org/@vizuh%2Fclicktrail — Registry metadata: latest 0.1.0 (published 2026-08-24). Description &#x27;Deterministic first-party attribution conventions and engine. Captures the trail from ad click to conversion.&#x27; License MIT. Repository git+https://github.com/vizuh/clicktrail-js.git. Not deprecated.</p>

<p>https://github.com/vizuh/clicktrail-js — HTTP 200, so the canonical repo is vizuh/clicktrail-js.</p>

<p>https://raw.githubusercontent.com/vizuh/clicktrail-js/HEAD/README.md — Describes a &#x27;motor determinístico&#x27; (deterministic engine) that interprets UTMs, referrers and click IDs and applies deterministic first/last-touch rules, with first-party storage. Release candidate 0.2.0-rc.2 is pending on npm. A pnpm TypeScript workspace.</p>

<p>Caveats: https://www.npmjs.com/package/@vizuh/clicktrail returned 403 to automated fetches. The registry API was used instead.; The GitHub API was rate-limited, so archived status came from the rendered repo page and README activity rather than API metadata.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>IGDataHub — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The live IGDataHub site is an Instagram analytics tool. It looks up public profiles (stats, bio, posts, engagement) and shows follower history for the profiles it fetches and refreshes. That matches the entry and fits Social media analytics.</p>

<p>https://igdatahub.com/ — Title &#x27;IGDataHub - Instagram Analytics &amp; Data Tool&#x27;. The page says &#x27;Look up any public profile, hashtag or place&#x27;, &#x27;Public Instagram profile data, refreshed regularly&#x27;, and &#x27;Stats, bio, posts, engagement metrics, and follower history at a glance&#x27;. It also shows follower counts for popular creators.</p>

<p>Caveats: The site now also offers hashtag/place lookup, creator comparison and CSV export. These are additions, not corrections.; I did not run a lookup; the site asks for an email before searching.</p>

</details>

<h3>SnapDataHub — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>SnapDataHub shows subscriber counts, Spotlight performance and growth for public Snapchat profiles. It says its earnings figures are modelled estimates. Every claim in the entry is supported.</p>

<p>https://snapdatahub.com/ — The page says &#x27;Look up any public Snapchat profile to see subscriber counts, spotlight performance, engagement metrics, and growth data&#x27; and that it stores snapshots &#x27;so we can chart subscriber growth over weeks&#x27;. It also says &#x27;The earnings estimates on each page are modelled from public reach and standard sponsorship rates, not disclosed&#x27; and has an Earnings Calculator.</p>

<p>Caveats: Engagement metrics, hashtag/keyword/location search and Spotlight trends are additional features, not corrections.</p>

</details>

<h3>TKMetrics — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>TKMetrics offers TikTok creator reports and public hashtag trends. Creator pages include average views, engagement rates, and a posting-days and posting-hours (UTC) heatmap. The trends page tracks hashtags across 19 regions. The entry is accurate.</p>

<p>https://tkmetrics.com/ — The page says &#x27;TikTok creator stats, hashtag trends and earnings estimates from public TikTok data&#x27; and &#x27;See followers, engagement rate, posting frequency, top videos, and growth metrics&#x27;.</p>

<p>https://tkmetrics.com/blog/khaby-lame-tiktok-profile-stats/ — This sample creator report shows views beating &#x27;its own average views&#x27;, posting days, and a &#x27;Posting Hours (UTC)&#x27; heatmap with the busiest hour.</p>

<p>https://tkmetrics.com/trends/ — The page says &#x27;See what&#x27;s trending on TikTok in 19 regions. Track hashtag growth&#x27; and has a Hashtag Tracker.</p>

<p>Caveats: Earnings estimates and creator comparison are additional features, not corrections.</p>

</details>

<h3>twtData — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>twtData exports X/Twitter followers, following lists and tweets to CSV, and has a trends section by country with dated history per trend. The entry is accurate.</p>

<p>https://twtdata.com/ — The page says &#x27;Download Twitter/X data in CSV format&#x27; and lists followers, following, tweets, lists and Spaces, with per-record pricing and sample CSVs. It also says &#x27;explore Twitter/X trends worldwide... by country&#x27;.</p>

<p>https://twtdata.com/twitter-trends/trend/jim-jordan/ — A per-trend page shows &#x27;trending history&#x27; with dated entries back to 3 January 2019 and a breakdown by location, which supports &#x27;trends archive by country&#x27;.</p>

<p>Caveats: The site has many more tools (bot detector, social listening, crypto tools). These are additions.</p>

</details>

<h3>LurkAPI — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>LurkAPI is a social media data API. It returns public profiles, posts and comments as JSON from 16 platforms, including TikTok, Instagram, YouTube, X and Reddit. &#x27;TikTok, Instagram, YouTube, X, Reddit and 11 more&#x27; adds up to 16, so the count is currently correct.</p>

<p>https://lurkapi.com/ — The page says &#x27;Clean data from public pages on 16 platforms&#x27; and &#x27;88 endpoints across 16 platforms&#x27;. The listed platforms are Facebook, Reddit, YouTube, TikTok, Google, Bluesky, Snapchat, Truth Social, Telegram, X, Threads, Instagram, LinkedIn, Link-in-bio, eBay and Web.</p>

<p>https://lurkapi.com/docs — The docs say &#x27;Send one request, get JSON back&#x27; and publish an openapi.json.</p>

<p>Caveats: &#x27;11 more platforms&#x27; is a count that can drift. A maintainer may prefer count-free wording later.; Some of the 16 &#x27;platforms&#x27; (Google, eBay, Web) are not social networks. The entry does not claim they are.</p>

</details>

<h3>LogBrew — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>LogBrew offers error tracking, performance monitoring and traces, logs, metrics, and product analytics. Every plan includes all features, there is a free plan, and AI agents can use it over MCP. The entry is accurate.</p>

<p>https://logbrew.co/en — The page says &#x27;LogBrew brings error tracking, performance monitoring, logs, and product analytics together&#x27; and &#x27;Every feature here is on every plan, including Free&#x27;. The SDK &#x27;sends errors, logs, traces, metrics, and product actions&#x27;. Agents can read evidence &#x27;over MCP&#x27;. It lists free-plan quotas: 100,000 errors and 50 GB of logs.</p>

<p>Caveats: https://logbrew.co/ redirects to the /en locale path. The listed root URL is still the right one.</p>

</details>

<h3>Metabase — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The opening sentence matches the current README word for word. Dashboards, the GUI query builder and SQL editor, scheduled email and Slack dashboard subscriptions, and the PostgreSQL, MySQL and Redshift connectors are all still documented. &#x27;Nightly Emails&#x27; is narrower than today&#x27;s scheduled subscriptions, but it is not false. The license is still AGPL outside the enterprise directory.</p>

<p>https://raw.githubusercontent.com/metabase/metabase/HEAD/README.md — &#x27;Metabase is the easy, open-source way for everyone in your company to ask questions and learn from data.&#x27; Lists dashboards, the SQL editor, asking questions without SQL, and &#x27;schedule dashboard subscriptions to email, Slack, or even a webhook&#x27;.</p>

<p>https://raw.githubusercontent.com/metabase/metabase/HEAD/LICENSE.txt — Code is AGPL outside the top-level &#x27;enterprise&#x27; directory, which is under the Metabase Commercial License.</p>

<p>https://github.com/metabase/metabase — Resolves without redirect. The repo tree has docs/databases/connections/postgresql.md, mysql.md and redshift.md.</p>

<p>https://www.metabase.com/ — https://metabase.com/ redirects to https://www.metabase.com/.</p>

<p>Caveats: The `Java` language tag looks inaccurate, since Metabase is primarily Clojure/JVM. Not verified through GitHub&#x27;s language metadata because the API was rate-limited. A maintainer could check it.; The README no longer uses &#x27;GUI Query tool&#x27; or &#x27;Nightly Emails&#x27;. Optional rewording could reflect embedding and AI (Metabot), but that is not required.</p>

</details>

<h3>Chartbrew — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The prose is still accurate. Chartbrew connects to databases and APIs, builds live charts and dashboards, and supports sharing, embedding, image export, team permissions and scheduled updates. v6 added AI and MCP features. The repo had commits in 2026-11. Maintainer note on metadata outside the prose: LICENSE.md now says Chartbrew is under the Functional Source License v1.1 (FSL-1.1-MIT), and each version becomes MIT two years after release. The `MIT` tag is therefore inaccurate for current code and needs a manual tag edit. The live demo page loads.</p>

<p>https://raw.githubusercontent.com/chartbrew/chartbrew/HEAD/LICENSE.md — &#x27;Chartbrew is licensed under the Functional Source License v1.1 (MIT Future License)... Each version... becomes available under the MIT License exactly two years after its release date.&#x27; It bars offering Chartbrew as a hosted service without a commercial license.</p>

<p>https://raw.githubusercontent.com/chartbrew/chartbrew/HEAD/README.md — &#x27;open-source web application that can connect directly to databases and APIs and use the data to create beautiful charts. It features a chart builder, editable dashboards, embedable charts, query &amp; requests editor, and team capabilities.&#x27; It runs on Node.js.</p>

<p>https://raw.githubusercontent.com/chartbrew/chartbrew/HEAD/docs/v6-release-notes.md — v6 adds Chart Studio, ECharts rendering, chart image sharing and export, scheduled email summaries, a Data API, and MCP connections.</p>

<p>https://chartbrew.com/ — Live SaaS site, &#x27;Chartbrew | Dashboard and Reporting Software&#x27;. It offers a 14-day free trial.</p>

<p>https://app.chartbrew.com/live-demo — Returns 200 with title &#x27;Chartbrew - Visualize your data in one place&#x27;.</p>

<p>Caveats: The license-tag correction (MIT → FSL-1.1-MIT) is metadata, not description prose, so it needs manual review. Whether older MIT-licensed versions justify keeping `MIT` is a maintainer judgement.; Did not inspect the &#x27;printing&#x27; feature specifically.</p>

</details>

<h3>Socioboard — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The prose still matches the official repo README: &#x27;Socioboard Core is an open source social media management, analytics and reporting platform. It supports nine social media networks.&#x27; socioboard.org is live and promotes social media management and analytics. Maintainer note on the suffix: the inline Source Code link github.com/socioboard/Socioboard-4.0 redirects to github.com/Socioboard-developers/Socioboard-5.0, which is not archived and had commits in 2026-08. That link needs a manual edit. The existing ⚠ marker is preserved. The repo now contains Node.js API services and a PHP web front end, so the `C#/JavaScript` tag may be outdated.</p>

<p>https://github.com/Socioboard-developers/Socioboard-5.0 — github.com/socioboard/Socioboard-4.0 redirects here. The repo is not archived. The atom feed&#x27;s latest commit is 2026-08-17.</p>

<p>https://raw.githubusercontent.com/Socioboard-developers/Socioboard-5.0/HEAD/README.md — &#x27;Socioboard Core is an open source social media management, analytics and reporting platform. It supports nine social media networks.&#x27; It also describes a commercial SaaS at socioboard.com and the open-source version at socioboard.org.</p>

<p>https://socioboard.org/ — Live: &#x27;Powerful social media management and content marketing platform&#x27; with &#x27;top class analytics&#x27; and pre-built reports.</p>

<p>Caveats: The Source Code link redirect (Socioboard-4.0 → Socioboard-developers/Socioboard-5.0) and a possibly stale language tag are suffix metadata needing manual review.; Did not verify the meaning of the ⚠ marker or the current license file in the 5.0 repo.</p>

</details>

<h3>Edalitics — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>&#x27;Open source analytics/BI tool&#x27; is accurate. The README calls Edalitics an &#x27;open-source analytics and dashboarding platform&#x27;, and the repo shows an AGPL-3.0 license. Angular/Node.js matches the stated tech stack. The vendor site offers a cloud SaaS. The repo had commits in 2026-11.</p>

<p>https://github.com/jortilles/EDA — Resolves without redirect, with an AGPL-3.0 license badge. Description: &#x27;Edalitics is an open-source business intelligence platform that lets you build interactive dashboards...&#x27;. Latest commit is 2026-11-06.</p>

<p>https://raw.githubusercontent.com/jortilles/EDA/HEAD/README.md — &#x27;Edalitics (previously Enterprise Data Analytics) is an open-source analytics and dashboarding platform created by Jortilles.&#x27; Stack: &#x27;Node.js, TypeScript, Angular&#x27;.</p>

<p>https://www.edalitics.com/ — Live Spanish-language site: &#x27;Herramienta BI en la nube - dashboards sin código&#x27; (cloud BI tool with no-code dashboards). It mentions auditable open-source code.</p>

</details>

<h3>Lookout — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official site confirms each claim. Lookout shows Vercel Web Analytics and Speed Insights (Core Web Vitals) for all projects on one board, with alerts, read-only share links, a REST API and an open-source MCP server. Pricing is &#x27;Free. Up to 100 projects and 5 members per workspace.&#x27;</p>

<p>https://lookoutstats.com/ — Title &#x27;Lookout — Vercel Web Analytics for every project, in one view&#x27;. Mentions Core Web Vitals &#x27;via Vercel Speed Insights&#x27;, &#x27;share a read-only link&#x27;, alerts, &#x27;connect the open-source lookout-mcp server... The same key works for the REST API&#x27;, and &#x27;Pricing Free. Up to 100 projects and 5 members per workspace.&#x27;</p>

<p>Caveats: &#x27;Free for up to 100 projects&#x27; is a volatile pricing claim. It is accurate today, but the site says it may change with notice.</p>

</details>

</details>

The complete research records remain local. This inventory contains all recommendations and unresolved entries from the saved initial review.

[One-entry integration example](https://github.com/bromanko/awesome-analytics/blob/codex/catalog-inventory-preview/.um/catalog-inventory/checked-example.md). Saved research with real discussion-history and patch checks.
