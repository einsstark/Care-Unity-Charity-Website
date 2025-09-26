# Care Unity — my original charity website (posted as-is)

I built this about two years ago as part of my web development module. 

<img width="1700" height="851" alt="image" src="https://github.com/user-attachments/assets/8cb1fae6-60d1-484a-b68b-171279c2f2e8" />

<img width="1710" height="826" alt="image" src="https://github.com/user-attachments/assets/30e185e3-d93b-4354-bb91-e18ca865a9fc" />

<img width="1705" height="858" alt="image" src="https://github.com/user-attachments/assets/d9ab435b-b405-4f0c-9650-78f0f87bc1f7" />


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
