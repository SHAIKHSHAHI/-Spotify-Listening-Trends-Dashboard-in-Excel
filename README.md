# 🎧 Spotify-Listening-Trends-Dashboard-in-Excel
## Project Overview 

- This project presents an analysis of my Spotify streaming history using Microsoft Excel.
- It focuses on understanding listening behavior through timestamps and usage patterns.
-Milliseconds were converted into minutes to calculate total listening time.
- Date and time were extracted using functions like =TEXT(), =HOUR(), and =ROUND().
- New columns were added for Day, Month, Hour, and Platform.
- Data was summarized using pivot tables and visualized with line, bar, and pie charts.
- The analysis covers track trends across time and most played artists/platforms.
- The entire dashboard was created using only Excel on a mobile device.

## 📊 Key Insights

- Total listening time was 508.98 minutes (~8.48 hours).

- Listening time was calculated using: =ROUND(ms_played/60000, 2).

- Most active listening hours were between 9 PM to 11 PM, with 10 PM being the peak.

- Evening hours are the most preferred time for streaming music.

- Windows platform had the highest usage (346.67 minutes), followed by Web Player (162.31 minutes).

- Desktop was the preferred listening environment.

- Top artists included Arijit Singh, Shreya Ghoshal, and Taylor Swift.

- These artists appeared frequently, indicating consistent listening.

- September and October had the highest listening activity.

- Fridays and Saturdays saw the most songs played.

- Most tracks played were short (2–5 minutes).

- Tracks with 0 minutes may indicate skipped or unfinished plays.
## 🧠 Formulas Used:
- 👉 =ROUND(ms_played/60000, 2) → Milliseconds to Minutes
- 👉 =TEXT(Timestamp, "dddd") → Day
- 👉 =TEXT(Timestamp, "mmmm") → Month
- 👉 =HOUR(Timestamp) → Hour

## ✅ Conclusion
- It reflects strong command of Excel functions, time-series processing, and dashboard design. 
- The insights derived offer a personal perspective on music habits while showcasing practical analytical skills.
-  This dashboard stands as a simple yet impactful example of data storytelling using real-life data.
