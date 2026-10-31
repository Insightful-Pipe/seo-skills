# InsightfulPipe SEO Skills

**38 free Claude skills for SEO and Google Search Console: site audits, keyword research, cannibalization, striking-distance keywords, content briefs, content decay, internal links, schema and AI search visibility.**

Most of these skills also work from reports you export and paste in, with no account needed. Skills that need numbers read them live from your accounts when the InsightfulPipe MCP is connected.

Part of the free [InsightfulPipe marketing skills library](https://github.com/Insightful-Pipe/marketing-skills). Skills with a **Page** link have a page with a sample run at [insightfulpipe.com](https://insightfulpipe.com/marketing-claude-skills/seo); newer ones get theirs soon.

## Install

### Claude Code

```
/plugin marketplace add Insightful-Pipe/seo-skills
/plugin install insightfulpipe-seo@insightfulpipe-seo
```

### Any agent: Claude Code, Codex, Cursor and others

```
npx skills add Insightful-Pipe/seo-skills
```

Add `--skill backlink-auditor` to install one skill.

### Claude.ai and Claude Desktop

Download a skill's ZIP from its page on insightfulpipe.com (the **Page** links below), or zip its folder from `skills/` if it has no page yet, then in Claude open **Customize > Skills**, choose **+ Create skill > Upload a skill** and pick the ZIP. Skills need code execution turned on.

## Skills (38)

| Skill | What it does | |
|---|---|---|
| [AI Answer Source Placement Planner](skills/ai-answer-source-placement/) | Finds the third-party pages ChatGPT and Google AI Overviews cite for your category, like best-of lists, Reddit threads and YouTube videos, that name rivals but not you… |  |
| [Ai Search Visibility](skills/ai-search-visibility/) | Scores AI search visibility from GA4 AI referrals, Search Console questions, AI Overview and ChatGPT mentions and llms.txt, checks if assistants get brand facts right… | [Page](https://insightfulpipe.com/marketing-claude-skills/seo/ai-search-visibility) |
| [AI Shopping Visibility Audit (ChatGPT Shopping SEO)](skills/ai-shopping-visibility/) | Checks which of a store's products ChatGPT shopping cards and Google AI Overviews name for buying questions, then traces each miss to feed, Merchant Center, markup… |  |
| [Backlink Auditor and Outreach Planner](skills/backlink-auditor/) | Audits backlinks for spam, lost and broken links, decides on disavow, and turns domains linking to competitors but not you into an outreach plan. |  |
| [Bing Webmaster SEO Analyst](skills/bing-seo-analyst/) | Analyses Bing search performance from Bing Webmaster Tools, splits brand and non-brand queries, compares Bing with Google Search Console, finds pages Google ranks that… |  |
| [Brand SERP and Knowledge Panel Optimizer](skills/brand-serp-knowledge-panel/) | Audits what Google shows for a brand or founder name, labels every page-one result, checks sitelinks, the knowledge panel, People Also Ask and negative results, and… |  |
| [Competitor Keyword and Content Gap](skills/competitor-keyword-gap/) | Finds the keywords and topics competitors rank for on Google and you don't, checks each gap against your Search Console, compares domain rank and referring domains, and… |  |
| [Content Brief Writer](skills/content-brief-writer/) | Writes an SEO content brief for one keyword from the live Google top 10, People Also Ask, competitor headings and your Search Console, and says new page or refresh. | [Page](https://insightfulpipe.com/marketing-claude-skills/seo/content-brief-writer) |
| [Content Decay Refresh](skills/content-decay-refresh/) | Finds pages losing Google clicks in Search Console, works out why (lost rank, lower CTR, cannibalisation, redirect or demand), checks update timing and AI Overview… | [Page](https://insightfulpipe.com/marketing-claude-skills/seo/content-decay-refresh) |
| [Core Web Vitals Fixer](skills/core-web-vitals-fixer/) | Diagnoses Core Web Vitals by page template with PageSpeed Insights and Lighthouse on your top Search Console pages, and writes ranked LCP, INP and CLS fix plans plus… |  |
| [Digital PR Link Campaign Planner](skills/digital-pr-link-campaign/) | Plans a data-led digital PR campaign for news links, testing the story in your survey, Shopify or GA4 data, building a media list from outlets that ran similar stories… |  |
| [Ecommerce SEO Auditor](skills/ecommerce-seo-auditor/) | Audits ecommerce SEO for Shopify, WooCommerce or Magento, covering duplicate product URLs, faceted navigation and filter URLs, out-of-stock and discontinued products… |  |
| [GitHub README Optimizer](skills/repo-readme-optimizer/) | Writes or audits a GitHub README and repo card (About line, topics, social preview) for an open-source tool, SDK, plugin or MCP server so it ranks in Google and gets… |  |
| [Google Discover and News SEO Optimizer](skills/news-discover-seo/) | Reviews Google Discover and Google News traffic from Search Console for publishers, checks articles for large image previews, Article markup, bylines and the news… |  |
| [Google Penalty Recovery Planner](skills/penalty-recovery/) | Diagnoses a Google penalty or sudden traffic drop, telling manual actions, hacked sites, core or spam updates and non-Google causes apart, then plans the cleanup and… |  |
| [Image SEO and Alt Text Generator](skills/image-seo-alt-text/) | Writes alt text by looking at each image and audits image SEO, flagging missing or stuffed alt, camera file names, heavy files and lazy-loaded hero images, ranked by… |  |
| [Indexing and Sitemap Monitor](skills/indexing-monitor/) | Checks which pages Google and Bing have indexed using Search Console URL inspection, sitemaps and Bing Webmaster data, groups not-indexed pages by reason, tracks new… |  |
| [Internal Linking Planner](skills/internal-linking-planner/) | Plans internal links from Google Search Console data, matching pages ranking 4 to 20 with on-topic donor pages, anchors from real queries, anchor text fixes and click… | [Page](https://insightfulpipe.com/marketing-claude-skills/seo/internal-linking-planner) |
| [International SEO and Hreflang Planner](skills/international-seo-planner/) | Plans international SEO and checks hreflang across country and language versions, sizes new markets with local keyword volume, picks subfolders vs ccTLDs and writes… |  |
| [JavaScript SEO Rendering Check](skills/javascript-seo-rendering-check/) | Checks what Google and AI crawlers can read on a JavaScript site by comparing raw and rendered HTML per template, then names the rendering fix for Next.js, Nuxt, React… |  |
| [Keyword Cannibalization Fixer](skills/keyword-cannibalization-fixer/) | Finds keyword cannibalization in Google Search Console, where two of your pages split one query, picks the owner page and writes a merge, differentiate or relink fix… | [Page](https://insightfulpipe.com/marketing-claude-skills/seo/keyword-cannibalization-fixer) |
| [Keyword Research Clustering](skills/keyword-research-clustering/) | Researches keywords for a topic with volume, difficulty, CPC and intent, clusters them by SERP overlap and Search Console data, and ranks a page plan. | [Page](https://insightfulpipe.com/marketing-claude-skills/seo/keyword-research-clustering) |
| [On-Page SEO Optimizer](skills/on-page-seo-optimizer/) | Optimizes one page or draft for one keyword against the Google top 10 and its Search Console queries, writing each edit as before and after text. |  |
| [Programmatic SEO](skills/programmatic-seo/) | Plans programmatic SEO pages, one template per city, trade, integration or competitor, by sizing demand per permutation and reading SERPs and incumbents, then gives a… | [Page](https://insightfulpipe.com/marketing-claude-skills/marketing/programmatic-seo) |
| [Rank and SERP Feature Tracker](skills/rank-tracker/) | Tracks Google rankings for up to 5 keywords a run with a live SERP snapshot set against Search Console averages, shows which SERP features you hold and could win, and… |  |
| [Schema Markup Generator](skills/schema-markup-generator/) | Audits structured data against the rich results Google Search Console reports and writes missing or broken JSON-LD for Organization, Breadcrumb, Article, Product… | [Page](https://insightfulpipe.com/marketing-claude-skills/seo/schema-markup-generator) |
| [SEO Audit](skills/seo-audit/) | Audits a site's SEO from Search Console, Bing, PageSpeed and GA4, covering indexation, broken links, redirects, titles, H1s, thin pages and speed, ranked by… | [Page](https://insightfulpipe.com/marketing-claude-skills/marketing/seo-audit) |
| [SEO Blog Writer](skills/seo-blog-writer/) | Writes SEO blog posts, roundups, X vs Y comparisons and alternatives pages from Search Console gaps and the live Google top 10, or reworks an existing page so AI… |  |
| [SEO Content Planner](skills/seo-content-planner/) | Plans a 12-week SEO content calendar from Search Console, GA4 and competitor gaps, with pillars, glossary pages, a content audit and ideas from sales calls or tickets. |  |
| [SEO Forecast and ROI Calculator](skills/seo-forecast/) | Forecasts SEO traffic, leads, revenue and the break-even month for a target keyword plan, using the site's own Search Console click curve and GA4 conversion rate, in… |  |
| [SEO Performance Report](skills/seo-performance-report/) | Reports Google Search Console results month over month and year over year, splitting clicks by brand vs non-brand, device, country, folder, page and query, plus… | [Page](https://insightfulpipe.com/marketing-claude-skills/seo/seo-performance-report) |
| [SEO Roadmap Planner](skills/seo-roadmap-planner/) | Builds a 3, 6 and 12-month SEO roadmap from Search Console, GA4 and Bing, diagnoses whether the site is new, growing, plateaued or declining, and fits the work into the… |  |
| [SEO Split Test Designer](skills/seo-split-test/) | Designs and reads SEO split tests on similar pages from Search Console, with matched test and control groups, a run length from the site's own noise and a controlled… |  |
| [Server Log and Crawl Budget Analyzer](skills/log-file-crawl-analyzer/) | Analyzes server and CDN access logs for crawl budget, verifying Googlebot, Bingbot and AI crawlers like GPTBot and ClaudeBot against published IP lists, then ranks… |  |
| [Site Migration SEO Monitor](skills/site-migration-monitor/) | Protects organic traffic in a site migration, redesign or replatform with a Search Console baseline, a launch check, a 301 redirect map and day 1 to 90 checks of… |  |
| [Site Structure Planner](skills/site-structure-planner/) | Plans a website's SEO architecture from keyword demand, with sections, hubs, URL and slug rules, menus, breadcrumbs, click depth and orphans, keeping ranking URLs in… |  |
| [Striking Distance Optimizer](skills/striking-distance-optimizer/) | Finds Google Search Console keywords at positions 8 to 20 and low-CTR pages, then rewrites the titles and meta descriptions losing clicks, with a sitewide title tag… | [Page](https://insightfulpipe.com/marketing-claude-skills/seo/striking-distance-optimizer) |
| [XML Sitemap, Robots.txt and llms.txt Generator](skills/robots-llms-txt-builder/) | Writes and tests robots.txt, XML sitemaps and llms.txt, checking every URL for Googlebot, Bingbot and AI crawlers so no page with clicks gets blocked, and sets AI bot… |  |

## Live data (optional)

Skills that read account data use the [InsightfulPipe MCP server](https://insightfulpipe.com/mcp-servers) when it's connected. Without it, each skill tells you which exports to paste in and works from those.

## What this plugin runs and sends

The plugin contains skills only: Markdown instructions (`SKILL.md`, `HOW_TO_USE.md`) and sample input and output files. It adds no hooks, commands or MCP servers, runs no code on your machine and sends no data anywhere by itself. When you have the InsightfulPipe MCP connected, Claude uses it to read your accounts, and makes a change only after you confirm it. The `scripts/` and `.github/` folders keep this repository in sync with insightfulpipe.com and are not part of what the plugin does.

## License

MIT. See [LICENSE](LICENSE).
