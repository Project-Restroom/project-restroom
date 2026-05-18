# How to add reviews without destroying everything

Add a new restroom review from this YouTube Short: <URL>

Fetch the page and parse the title for the pattern Establishment - City, State - Restroom Type
Extract the verdict (rating) and date from the page metadata/description
Add a new entry to _data/reviews.json following the existing structure: an establishment object with establishment, city, state, and a reviews array containing an object with restroom_type, youtube_url, rating, date, and notes
If the establishment already exists in the file, append to its reviews array instead of creating a duplicate
If the OpenStreetMap id is found, show it. Don't edit the reviews.json yet. It need to be reviewed first.
Do not modify any other fields or files