# Google-Scripts-Code
A repo of four Google Script codes to enhance Google Sheets functionality. Uses a combination of custom functions and triggers. These were designed for sheets with a very specific design and are non-functioning for sheets not of that design. However, these can be adapted for whatever your sheet needs, or can provide a jumping off point to add further functionality to your sheets.

1. Edit Tracker w/ Matching Columns Check
  An edit tracker that inserts email of who made the last edit and at what time/date.
  It compares values in the B column (up to next blank cell) with values in the I column, turning mismatches a bolded white.
  All matches revert back to original font.
  The comparisons happen on Open and on each Edit in the B column.
  Additional functionality of getting Hex number of values in B and inserting into column M. This would be used for sorting by color to see only mismatches or matches.

2. Edit Tracker - Simple
  Tracks cell edits, inserts email of who made the last edit and at what time/date.

3. Expiration Updater
  Tracks cell edits above line 19.
  Inserts today as edit date into cells 20 rows below
  Emails reminder to check groceries (Trigger set for Mondays between 8 and 9 am)

4. Restaurant Randomizer
  Picks random restaurant from list (column A) for a meal from Spreadsheet.
  Checks to make sure the restaurant has not been eaten at for at least a week.
  Authority checker for more expensive meals using dialogue pop-up compared with column B.
  
  
NOTE: Because you cannot directly download from Google Scripts, I saved these as .rtfs. Please take from them and copy and paste into Google Scripts.
