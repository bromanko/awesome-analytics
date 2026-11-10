# Single-entry integration example

Saved research reused for one correction; no new entry research and no full-catalog freshness run. Real production history collection, Opus history review, patch/link checks and report rendering were exercised.

**1 ready for review · 0 held**

1 checked · 0 unchanged · 1 saved assessment reused · 0 source checks unavailable

<h2>Panelbear — Ready for maintainer review</h2>

```diff
--- a/README.md
+++ b/README.md
@@ -27,7 +27,7 @@
 ## General analytics
 **[`^        back to top        ^`](#)**
 * [UXWizz](https://www.uxwizz.com/) - Self-hosted web analytics with heatmaps, session-recordings, A/B tests and more. `©` `Self-Hosted` `PHP`
-* [Panelbear](https://panelbear.com/) - free real-time website analytics. Supports custom event tracking, email digests, and site speed metrics. `©` `SaaS`
+* [Cronitor Analytics](https://cronitor.io/real-user-monitoring) - free real-time website analytics. Supports custom event tracking, email digests, and site speed metrics. `©` `SaaS`
 * [PostHog](https://posthog.com) - Open-source product analytics to track users, events, funnels and trends. Alternative to Mixpanel/Amplitude/Heap. Also includes session recording (alternative to HotJar) and feature flag/experimentation tools (alternative to Optimizely).([Source Code](https://github.com/posthog/posthog)) `MIT` `Python`
 * [stratif.io](https://stratif.io) - Open-source, self-hosted, warehouse-native product analytics. Runs funnels, retention, and path analysis directly on DuckDB, Postgres, Snowflake, or ClickHouse — no ingestion, no SDK. ([Source Code](https://github.com/stratif-io/stratif.io)) `Apache-2.0` `Python/TypeScript`
 * [GrowthBook](https://growthbook.io) - Open-source A/B testing and feature flagging that uses your existing data sources.([Source Code](https://github.com/growthbook/growthbook)) `MIT` `Typescript`
```

<details>
<summary>Evidence and checks</summary>

<p>panelbear.com redirects to Cronitor, and the destination page states &#x27;Panelbear is now Cronitor Analytics&#x27;. This is an official rebrand into Cronitor&#x27;s analytics/RUM product. Custom event tracking and site-speed metrics are still documented. I could not verify the &#x27;free&#x27; and &#x27;email digests&#x27; claims on the current page.</p>

<p>https://cronitor.io/real-user-monitoring — https://panelbear.com/ redirects to https://cronitor.io/real-user-monitoring?ref=panelbear, whose canonical is https://cronitor.io/real-user-monitoring. The page says &#x27;Panelbear is now Cronitor Analytics&#x27; and &#x27;Traffic, performance, and errors in a single tool. Cookie-free&#x27;. It shows conversion tracking via cronitor(&#x27;track&#x27;,&#x27;Checkout&#x27;), LCP/CLS and page-load timing percentiles, JavaScript error tracking and alert rules.</p>

<p>Caveats: The Cronitor pricing page did not clearly confirm a free analytics tier, so the proposed wording drops &#x27;free&#x27;. Email digests were not mentioned, so they are dropped too.; Category tags (©, SaaS) remain appropriate.</p>

<p>related: The only match is PR #106, &quot;Add Panelbear&quot;, by anthonynsimon (https://github.com/oxnr/awesome-analytics/pull/106). It was merged on 2021-01-25. Its patch added the current entry text: &quot;free real-time website analytics. Supports custom event tracking, email digests, and site speed metrics.&quot; That PR explains where the entry came from, but it isn&#x27;t the same change. It added Panelbear; it didn&#x27;t rename it to Cronitor Analytics or replace the URL with cronitor.io. It has no comments or reviews, so there is no objection to this update. The searches for &quot;https://cronitor.io/real-user-monitoring&quot; and &quot;Cronitor Analytics&quot; in oxnr/awesome-analytics and bromanko/awesome-analytics turned up no open or merged PR making this rebrand correction. These results cover only the 8 listed queries, which retrieval marked as complete. Checks passed; existing unrelated link failures are listed separately.</p>

</details>

<details>
<summary>Saved review baseline</summary>

0 new completed reviews · 1 pending.

To retain completed reviews, review and commit the bundled `baseline.json` as `.um/freshness/baseline.json`.

</details>

<details>
<summary>Full research and run details</summary>

# Freshness research

Advisory only; every suggested change requires maintainer review.
No list edits, PRs, comments, or reviews were submitted.

Catalog revision: `fd3895d3600ce7bb74eeab95088c4613919343d7`
Scope: one selected entry from saved research
Catalog recheck: unchanged

Sources below are agent-reported observations, not independent verification.

## Entry 30

<pre>Panelbear

panelbear.com redirects to Cronitor, and the destination page states &#x27;Panelbear is now Cronitor Analytics&#x27;. This is an official rebrand into Cronitor&#x27;s analytics/RUM product. Custom event tracking and site-speed metrics are still documented. I could not verify the &#x27;free&#x27; and &#x27;email digests&#x27; claims on the current page.

https://cronitor.io/real-user-monitoring
https://panelbear.com/ redirects to https://cronitor.io/real-user-monitoring?ref=panelbear, whose canonical is https://cronitor.io/real-user-monitoring. The page says &#x27;Panelbear is now Cronitor Analytics&#x27; and &#x27;Traffic, performance, and errors in a single tool. Cookie-free&#x27;. It shows conversion tracking via cronitor(&#x27;track&#x27;,&#x27;Checkout&#x27;), LCP/CLS and page-load timing percentiles, JavaScript error tracking and alert rules.

Blocking uncertainties:
None reported.

Informational caveats:
The Cronitor pricing page did not clearly confirm a free analytics tier, so the proposed wording drops &#x27;free&#x27;. Email digests were not mentioned, so they are dropped too.
Category tags (©, SaaS) remain appropriate.

Recommendation: update
Proposed name: Cronitor Analytics
Proposed URL: https://cronitor.io/real-user-monitoring
Proposed description: None</pre>


</details>

Proposals only; no catalog edits or PRs submitted. Full records and checked patches are in the run artifacts.
