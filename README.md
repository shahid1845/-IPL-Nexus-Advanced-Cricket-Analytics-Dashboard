# -IPL-Nexus-Advanced-Cricket-Analytics-Dashboard
IPL Nexus is a premium, high-performance web application designed to transform raw Indian Premier League (IPL) data into actionable visual insights. Built with React, Tailwind CSS, and Recharts, it offers a sophisticated dark-mode interface for cricket enthusiasts and data analysts to explore match trends, player performance, and team statistics.
✨ Key Features

🚀 Instant Demo Mode: Pre-loaded with a sample dataset so users can explore the UI immediately without manual uploads.

📊 Dynamic Visualizations:

Match Victories: Vertical bar charts showing top-performing teams.

Toss Strategy: Pie charts analyzing "Bat vs Field" decisions.

Player Analytics: Identification of leading run-scorers and wicket-takers.

📂 Big Data Support: High-speed CSV parsing engine capable of handling years of historical IPL data (matches & deliveries).

🔍 Smart Filtering: Real-time filtering by Season and Team with automatic KPI recalculations.

📱 Responsive Design: Fully optimized for mobile, tablet, and desktop viewing.

🛠️ Tech Stack

Frontend: React (Hooks, Memoization for performance)

Styling: Tailwind CSS (Modern Dark Aesthetic)

Charts: Recharts (SVG-based responsive charts)

Icons: Lucide-React

🚀 How to Use

View Results: Open the app to see the default 2023-2024 sample statistics.

Upload Your Own Data: * Click the "Data Source" button in the top right.

Upload your matches.csv and deliveries.csv files.

The dashboard will instantly "ingest" and visualize your local data.

Filter: Use the control panel to drill down into specific seasons or your favorite team's history.

📂 Data Format Requirement

To use the custom upload feature, ensure your CSVs follow the standard Kaggle IPL dataset structure:

Matches: Must contain season, team1, team2, winner, toss_decision.

Deliveries: Must contain match_id, batter, bowler, batsman_runs, is_wicket.

Created for the cricket community to bring data-driven insights to every match.
