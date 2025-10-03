Challenges in previous script which rendered it unusable.
•	Script found no images unless the browser was always kept in focus.
•	The script was not fault tolerant (that is we lost all data if script stopped midway).

Updated Script with Fix 
•	The new scraper is fault tolerant (keeps everything it already wrote even if it stops midway) and background friendly (keeps working while Chrome is minimized and we’re using other apps)
•	Writes to Excel as it goes (autosaves after each page/row).
•	Survives interruptions (Ctrl C, crash, power loss) with minimal loss.
•	Skips what it already finished when you re run it.
