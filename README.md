# tlg-eagan-kb-facts

Public mirror of The Little Gym of Eagan's customer-facing facts page
(hours, pricing, ages, policies), published solely so GHL's Voice AI
Knowledge Base web crawler can index it.

**Not the canonical source.** The real source lives in
`tlg-web-brand-kit/facts.html` (see the `ops` repo's
`runbooks/ghl-ai-call-agent.md` for the full design). This repo exists
only because `tlgeagan.com/robots.txt` has a blanket `Disallow: /` for
all bots except Googlebot/AdsBot, which also blocks GHL's own Knowledge
Base crawler — GHL's crawler doesn't appear to respect a scoped `Allow`
exception, so the page needed a home with no crawl restrictions at all.

When `tlg-web-brand-kit/facts.html` changes, re-copy it here as
`index.html` and push.
