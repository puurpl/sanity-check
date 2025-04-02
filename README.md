Project Sanity

A Scalable WikiTribune type project for the AI Era

🌐 Purpose

We're building an AI-powered news analysis platform that:

✅ Detects media bias by comparing how several hundred international outlets cover the same events

✅ Explains discrepancies with historical/economic/technical context

✅ Traces every claim to its source (Git-style auditing)

Why this matters:


    "In 2023, 78% of Americans saw conflicting news about the same event" (Pew Research). We make these differences transparent.



🛠 Current Status


    Functional prototype: puurpl.github.io/sanity


    Core features working:
        RSS/Scraper pipeline (30+ sources → expanding to a few hundred or as many as it takes to support our mission)
        AI clustering of related articles
        Basic anti bias UI 
        Creating meta-articles with impartial explanations and tracking of media discrepencies (currently not integrated into the UI)

---

# Example of our analysis pipeline
def analyze_coverage(event):
    articles = scrape_sources(event)
    clusters = ai_cluster(articles)  # By topic/angle
    return generate_meta_report(clusters)

Seeking

Role	Contribution
Journalists	Validate bias detection methods
Python Devs	Improve scraping resilience
Designers	Make complex data intuitive
Funders	Cover server/API costs ($1,200/mo)

Get involved:


    Email: puurpl@zak.fyi



📊 Budget (First Year)

Category	Cost	Notes
Servers (Elasticsearch/Django)	$5,760	$480/mo
AI APIs (GPT-4, Claude)	$3,600	$300/mo
Scraping Tools	$1,200	Anti-bot evasion
Legal (LLC/Trademark)	$1,500	One-time
Total	$12,060	Detailed Budget

Fiscal sponsorship needed to receive tax-deductible donations.
