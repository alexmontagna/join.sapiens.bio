# join.sapiens.bio

Five landing pages for [Sapiens](https://sapiens.bio), each its own idea, served by GitHub Pages:

| Address | Idea |
|---|---|
| [join.sapiens.bio/drift](https://join.sapiens.bio/drift/) | 150 lights orbit you and drift away as the years pass; tap one to bring it back |
| [join.sapiens.bio/antidote](https://join.sapiens.bio/antidote/) | Sapiens as the treatment for loneliness: a medicine box, a leaflet, a prescription |
| [join.sapiens.bio/times-left](https://join.sapiens.bio/times-left/) | Type who, their age and how often you meet: the times left, one dot each |
| [join.sapiens.bio/catch-up](https://join.sapiens.bio/catch-up/) | «We should catch up soon», one chat thread over sixteen months |
| [join.sapiens.bio/unfeed](https://join.sapiens.bio/unfeed/) | A loud feed falls apart under real physics, leaving only your people |

The bare address and any unknown path go to sapiens.bio.

- Push to `main` = deploy (GitHub Pages, `CNAME`). DNS: a DNS-only `CNAME join → alexmontagna.github.io` in Cloudflare.
- Each page is one self-contained `index.html` (fonts from Google Fonts; Anti-Feed's physics, matter-js 0.19.0, vendored in `unfeed/`).
- «Join the waiting list» opens `https://sapiens.bio/?waitlist`, the sign-in page on its waiting-list form. Links into
  sapiens.bio send their full address (`referrerpolicy="no-referrer-when-downgrade"`), so Admin › Visitors shows which
  page sent each visitor (`join.sapiens.bio/<slug>`).
- Every person on these pages is invented.
