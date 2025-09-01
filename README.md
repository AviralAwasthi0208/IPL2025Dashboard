🏏 IPL 2025 Power BI Dashboard — Live Scores, Points Table & Analytics

Interactive IPL dashboard showing live scores, schedule, points table, Orange/Purple cap leaders, squads, and player records—built in Power BI with Power Query + DAX + HTML/CSS cards and published to Power BI Service.

🔥 Project Highlights (What’s inside)

4 pages: Home, Overview, Points Table, Squads with 25+ visuals and 5+ DAX measures

Live-like updates from structured web/CSV sources; single-click page navigator & slicers (Team, Date, Venue)

Custom Points & Position ranking (dense/unique rank), HTML/CSS match cards, player tiles, and records widgets

Optimized model (query folding, relationships) for fast rendering and neat mobile-ready layout

🧰 Tech Stack

Power BI Desktop / Service, Power Query (M), DAX, HTML/CSS (in HTML content visual)

Data sources: league schedule & match data (web/CSV), team & player metadata (logos, squads)

DashBoard Screenshots
<img width="1305" height="726" alt="home" src="https://github.com/user-attachments/assets/c3dcee3e-8084-492d-aad4-f538e9c51fd6" />
<img width="1313" height="722" alt="2" src="https://github.com/user-attachments/assets/1d1cbd51-88e1-41f7-a6f4-9aeb5de64c1d" />
<img width="1292" height="717" alt="Screenshot 2025-09-02 010337" src="https://github.com/user-attachments/assets/565cab25-95e7-422f-b970-50a42aca59c8" />


<img width="1297" height="706" alt="image" src="https://github.com/user-attachments/assets/c778fa33-ba95-4ef5-aa3b-9e4347444f16" />



📊 Key Features

Live/Result tabs for fixtures with team logos & match status

Points Table with auto Position ranking (Points → W/L as tiebreakers)

Orange/Purple Cap trackers and player records (Best Avg, Most Dots, Fastest 50/100, etc.)

Schedule panel: date/venue styled like official cards (top-right date)

Cross-page interactions and drill-through to team/player context

📁 Pages

Home – quick pitch, navigation chips, highlights

Overview – live fixtures, records hero card, schedule, players table

Points Table – league standings, W-L-NR, auto position rank

Squads – team roster with role, age, links

🚀 How to Run

Clone the repo and open IPL_Dashboard.pbix in Power BI Desktop.

In Transform data, confirm source paths/URLs; set parameters if provided (e.g., SeasonYear).

Click Refresh to load/transform data (Power Query) and recalc measures (DAX).

Publish: Home → Publish to Power BI Service; set scheduled refresh (Credentials → Anonymous/Web or as needed).

If using the HTML visual, ensure “HTML content” custom visual is allowed in the tenant/report.



Power Query Index fallback for stable sort on cards

Reusable measures for W, L, NR, Points, Caps, and player aggregates
