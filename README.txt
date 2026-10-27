BASELINE — AD-FREE ESPN SPORTS SCORES

Open index.html in Chrome, Firefox or Edge. Choose a sport, league and date. Click a match to see available statistics and box scores.

Uses ESPN's undocumented, public site.api.espn.com endpoints. No API key, login, ads, telemetry or backend. Requires internet.

For a more reliable local setup, run a small static server from this folder:
  python -m http.server 8080
Then open http://localhost:8080

Host on a static web host (e.g. GitHub Pages) for access from your phone. Mobile browsers can Add to Home Screen.

Important: ESPN's undocumented API and cross-origin rules may change, and some ESPN competitions may not have the expected league slug or game details. College FBS requests use groups=80; men's and women's college basketball request groups=50. If a league returns no results, it may be out of season or the endpoint/league slug is unsupported.

For personal use only. This is an independent app and is not affiliated with ESPN.
