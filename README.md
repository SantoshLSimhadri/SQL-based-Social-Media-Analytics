# SQL-based-Social-Media-Analytics

Analytical Marketing Analyst with 2+ years of experience in campaign performance analysis, media optimization, and reporting. Skilled in leveraging data from platforms like Google DV360 and Meta Ads to evaluate ROI, CAC, LTV, and other KPIs that guide strategic marketing investments. Adept at building dynamic dashboards in Tableau and Power BI to provide real-time insights for brand and executive teams. Strong collaborator with cross-functional teams and vendor partners, combining technical skills in SQL and Excel with a data storytelling mindset to improve marketing effectiveness and budget efficiency

Tech & Setup
Database: MySQL / MariaDB (works with any ANSI-compliant RDBMS with minor tweaks)

Data Model (high level)
Users – profile & join date
Posts – author, content, timestamp
Comments – who commented on which post & when
Likes – who liked which post & when
Followers – follower → following relationships (directed)
(Relational DDL + FKs are defined in the script.) 
Social_Media_Analytics
What You Can Analyze (Query Catalog)
Engagement
Post with the most likes / posts above average likes
Posts with more comments than likes
Recent post by user; total comments on a post
Influence & Network
Most-followed user
Users who liked their own posts (self-interaction)
Users who comment on posts outside their follow graph
Behavior & Coverage
Users who never posted / never liked
Users who liked every post by a specific creator
Top commenter behavior on a single post
(See queries 1–26 in the script for ready-to-run SQL.) 
Social_Media_Analytics
🔍 Example Insights (from the included queries)
Identify Top Creators by total likes across their posts (creator ROI proxy)
Spot High-Discussion Posts where comments exceed likes (conversation > virality)
Track Superfans who like every post by a creator (loyalty signal)
Surface Silent Accounts (no posts/likes) to inform onboarding nudges
All of these are provided as parameterizable SQL SELECTs in the script
