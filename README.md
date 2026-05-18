# Project Restroom

A directory of restroom reviews. Data is stored as structured JSON files.

## GitHub Pages

This site is published via GitHub Pages at `https://epearson.github.io/project-restroom/`.

## Data

Reviews are stored in [`_data/reviews.json`](_data/reviews.json). Each entry contains:

| Field | Description |
|---|---|
| `establishment` | Name of the establishment |
| `city`, `state` | Location |
| `restroom_type` | Type of restroom (Men's, Women's, Unisex, etc.) |
| `youtube_url` | Link to the YouTube Shorts review |
| `rating` | Rating out of 5 (optional) |
| `date` | Date of review (optional) |
| `notes` | Additional notes (optional) |

## Adding a review

Add a new object to `_data/reviews.json` following the existing schema, then push to `main`. GitHub Pages will rebuild automatically.
