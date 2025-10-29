# EDSea 2025 Schedule and Scores
This repo is for sharing a spreadsheet with a list of artists and their sets for EDSea 2025, plus a feature to rate them to assist your group with planning who you'd like to see.

*This list is accurate and up-to-date as of October 28, 2025*

Requests for stylistic changes (e.g., different colors) will not be addressed, but for issues with inaccurate information, please use the issues tracker above.

The spreadsheet was originally adapted to work in Microsoft Excel.  All of the information should appear in Google Sheets, however, the scoring function may not function properly.

# Context and How to Use:
* The primary key for the spreadsheet is the artist.  Each artist appears only one time, with a single score, whether or not they have multiple sets (to help prioritize which artists you want to see in case of a scheduling conflict), and the days/times/locations of their sets to the right.  An artist with multiple sets will have multiple entries across their row for columns G-P.
* The score exists to help groups prioritize who they may or may not want to try and see perform.
  * The default behavior is 3 friends, providing 3 scores, with a range of 3 (low) to 15 (high).
  * Once all 3 friends rate the artist, the score will appear in column E.  The column is conditionally formatted to display a darker color for higher (more desireable) scores and a lighter color for lower (less desireable) scores.
  * If you wish to alter the scoring:
    * You will need a basic understanding of functions (sum, vlookup) in Excel/Sheets
    * There is a hidden sheet entitled "Ratings" where you can make changes to the numerical values.  You will also need to update this sheet if you change the wordings used for the ratings (e.g., you change "I'll Pass" or "Leaning Yes")
    * Individuals or pairs of friends can simply rank "Indifferent" in the unused columns
    * Those wishing to increase the size of their friends group will have to expand the column E equation/functions
* The color coding for the set locations (columns H, J, L, N, P) is conditional and matches the coloring on the official EDSea schedule.
* All times are as published by Insomniac and will follow Miami time (Eastern) for the duration of the event.
