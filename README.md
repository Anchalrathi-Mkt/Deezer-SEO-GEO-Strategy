Deezer SEO & GEO Case Study — Supporting Excel Analysis
Brazil media acquisition | French Christmas music SEO & GEO
Candidate project | November 2026

This repository documents an independent candidate analysis prepared for a Deezer SEO internship case study. The Excel workbook supports the presentation with channel-level calculations, proposed subscription-growth experiments, a French Christmas SEO research framework, an optimization roadmap, KPI definitions, and an exploratory AI-search (GEO) test log.
Disclaimer: This is an independent recruitment case study, not an official Deezer project or an implementation of Deezer's marketing strategy. Data supplied in the case, calculated metrics, proposed actions, illustrative scenarios, and unverified inputs are separate categories. No access to Deezer's private Search Console, campaign spending, or subscription attribution data is claimed.

Project objectives
1. Brazil acquisition: Identify two channels to consider stopping and propose two approaches to increase subscriptions.
2. French Christmas SEO: Determine relevant French Christmas music search intents; propose before/during/after optimization; define success metrics.
3. Christmas GEO: Evaluate a small sample of AI-generated recommendations and propose content and measurement actions.
Workbook guide
Worksheet	What it contains	Evidence classification
START HERE	Navigation and evidence-status overview	Documentation
02 Brazil channels	The ten supplied channels, visits, engagement metrics, subscriptions, calculated conversion rates, and channel assessment	Supplied case data + derived metrics + provisional recommendation
03 Brazil growth	Two subscription growth recommendations and editable organic-conversion scenario	Proposed actions + illustrative calculation
04 Keywords	French Christmas seed keywords, intent groups, potential landing page mapping, and research fields	Primarily proposed research; some entries require independent verification
Full SEO Audit	38-field SEO audit checklist across proposed Christmas content types	Template/proposed checks; not a completed live-site audit
05 SEO Roadmap	Prioritized actions before, during, and after Christmas	Recommendations
Audit Field Guide	Definitions and limitations of technical, content, linking, and third-party SEO audit fields	Methodology
06 KPI Dashboard	Proposed visibility-to-subscription dashboard	Framework; sample values are not verified campaign results
06 KPI Inputs	Metrics, intended data sources, and required inputs	Tracking specification
07 GEO Tests	Four French prompts, observations and supporting screenshots/notes	Exploratory observations; accuracy/citations pending verification
07 GEO Actions	Deezer-feature-specific content ideas, AI intents, SEO/GEO actions and KPIs	Proposed strategy


Brazil: acquisition analysis
Calculation:
Channel conversion rate (CVR) = Subscriptions / Visits × 100
Selected calculated CVRs from the case data:
Channel	CVR (approximately)	Interpretation
Google Ads	9.52%	Strong observed visit-to-subscription conversion; profitability not known
Facebook	7.99%	Strong observed CVR; channel spend and incrementality need review
Organic Search	2.36%	Large traffic base and a conversion-optimization opportunity
Affiliation	0.187%	Low CVR; provisional review/pause candidate
User content sharing	0.097%	Very low CVR; its organic/distribution role may justify separate assessment
Display	0.023%	Lowest CVR and 79% bounce rate; strongest provisional pause candidate


Provisional conclusion: Review or pause Display first and examine Affiliation second, after checking costs, attribution, and channel roles. User content sharing converts even less than Affiliation, so it should be explicitly investigated before a final stop decision.

Two growth actions:
1. Test a controlled reallocation toward promising Google Ads/Facebook campaigns only after reviewing cost per acquired subscriber, attribution and incremental impact.
2. Improve Organic Search landing pages, CTAs, signup journeys and subscription conversion through testing.
The workbook models an illustrative organic CVR increase to 2.60% at unchanged traffic:
1,927,077 organic visits × 2.60% ≈ 50,104 modeled subscriptions
50,104 − 45,500 observed subscriptions ≈ 4,604 modeled incremental subscriptions
This is a scenario, not a prediction or realized uplift. The workbook's formulas and references should be recalculated and audited before reuse.
France: Christmas SEO methodology
Research: Build keyword clusters for generic Christmas music, French classics, playlists, family/children, jazz/moods, albums, and podcasts. Use the France database in Semrush, Google Trends for seasonal peaks, SERP inspection, and Search Console where authorized.

Prioritization: Choose search intents based on verified search demand, competition, suitability of Deezer's existing pages, editorial feasibility, and potential engagement/acquisition. Prefer improving the right existing indexed asset over creating duplicate pages.

Execution:
- Before Christmas: Audit available URLs, map keyword intent, improve titles/H1s/descriptions, verify canonical/indexation/sitemap, and link related content.
- During Christmas: Refresh relevant playlists/podcasts, monitor Search Console and performance, resolve technical issues, and respond to seasonal intent.
- After Christmas: Compare performance against valid baselines, review listening-to-registration outcomes, preserve evergreen content and document learnings.
Measurement framework: Organic impressions, clicks, CTR, query/ranking visibility, indexing, organic landing sessions, playlist/podcast engagement, registrations, and attributed subscriptions. Internal Deezer analytics are needed for downstream commercial outcomes.
France: exploratory Christmas GEO test
Four French prompts were tested across ChatGPT, Gemini, and Perplexity:
Intent	Platform	Result for Deezer
Best Christmas playlist	ChatGPT	Mentioned/recommended as an alternative; Spotify led
French Christmas songs	ChatGPT	Recommended second; Spotify led
Children's Christmas playlists	Gemini	Recommended second; Spotify led
Christmas podcasts	Perplexity	Mentioned as a listening platform, but Radio France content was prominent


Observed in this small, nonrepresentative sample:
- Mention rate: 4/4 = 100%.
- Explicit recommendation rate: 3/4 = 75%.
- Leading recommendation rate: 0/4 = 0%.
- Citation share: Not yet verified.
- Answer accuracy: Not yet verified; claims about Deezer's features and catalog must be checked against official sources.
Because different prompts were used on different systems and the sample is small, these percentages must not be presented as Deezer's general market-wide AI visibility.
Proposed GEO actions
Create accurate, helpful, discoverable content around actual seasonal intents, selecting Deezer capabilities only where relevant:
- Christmas playlists and podcasts: French classics, children's selections, festive moods, and stories.
- Flow: Personalized music discovery where the user asks for recommendations.
- HiFi: Listening quality for relevant audio-quality queries.
- SongCatcher: Identifying unfamiliar Christmas songs.
- Playlist Transfer: Moving existing festive playlists from another service.
Improve titles, headings, descriptions, internal links and source clarity; verify factual claims; study the sources cited by AI answers; and repeat standardized prompts. Track mentions, explicit recommendations, top-choice appearances, verified citations, answer accuracy, and attributable registrations/subscriptions when data access permits.
Data integrity and limitations
- Supplied case data: The Brazil traffic, engagement and subscription counts originate from the recruitment exercise.
- Calculated values: Brazil CVRs are derived from those counts; a high CVR does not establish profitability or incrementality.
- Hypothetical scenario: The 2.60% organic conversion target is illustrative and editable, not a Deezer target.
- Keyword research: Search-volume/difficulty entries must have documented source, units, geography and capture date before being called verified. The current workbook includes an entry for musique de Noël (volume 9.9, difficulty 41) whose supporting evidence and volume unit should be independently confirmed.
- SEO audit: Unverified fields and proposed metadata should not be described as audited live-page findings.
- KPI dashboard: Existing numeric example values (including 88, 65, 0.5, and 48) are not verified Deezer results; replace or remove them before treating the dashboard as performance reporting.
- GEO: Screenshots support what the tools displayed in individual trials, not the correctness of their catalog claims. Citation share and factual accuracy remain pending review.
Suggested repository structure
.
├── README.md
├── Deezer case study.xlsx      # Rename the uploaded workbook consistently
├── Deezer SEO-GEO Case Study.pdf  # Optional accompanying presentation
└── evidence/                  # Optional, only for permitted GEO screenshots and sources
How to use
1. Download and open the workbook in Excel.
2. Start with START HERE, then follow the sheets for slides 2–7.
3. Separate provided data, calculated findings, recommendations, and hypothetical/unverified values when presenting.
4. Use the presentation for the concise story and the workbook to demonstrate supporting methodology.
Tools and approach
Microsoft Excel (formulas, scenario modeling, tracking templates), SEO research planning (Semrush, Google Trends, Google Search Console), and exploratory manual tests using ChatGPT, Gemini, and Perplexity. Mention of a tool does not imply access to Deezer's internal data.
Project status: Candidate analysis / methodological demonstration — not an implemented or independently validated campaign.
