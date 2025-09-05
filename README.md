# Care Unity — my original charity website (posted as-is)

I built this about two years ago as part of my web development module. 

**Live site:** https://einsstark.github.io/Care-Unity-Charity-Website/  

**Report (Zenodo):** https://zenodo.org/records/17059708?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6IjM4ZjM1M2JjLTEwYmYtNDZkOC05MGRmLTlmNGZlZmFjYWVlMyIsImRhdGEiOnt9LCJyYW5kb20iOiI2OWUwYzlhZDBjZWJhMmUyOWUwMDQ5ZWU3MTFhNTQ1YiJ9.rM1TatrGFJt4q8ytEfqQG_97WxIqS299yqcT8GHGH2xlEZwvkLlF9EO2XwgynHAddEY9OF_9rrsF95_M6A74Fg

## What it is
- Plain HTML/CSS pages: homepage, about, campaigns, contact, donate (placeholder), privacy, cookies, terms
- One shared header + footer pulled into pages with a tiny `fetch()` include

## What I learned then
- Start with foundations: clear structure; shared UI in one place
- Fixed widths look fine on a laptop… then break on phones (lesson noted)
- Basics effects: readable type, alt text, obvious links

## Run locally (because of the `fetch()` includes)
```bash
python3 -m http.server 8000
# then visit http://localhost:8000/homepage.html
