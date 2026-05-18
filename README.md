# Project Restroom

A directory of restroom reviews. Data is stored as structured JSON files.

## GitHub Pages

This site is published via GitHub Pages at `https://epearson.github.io/project-restroom/`.

## Data

Reviews are stored in [`_data/reviews.json`](_data/reviews.json). Each entry is an establishment with a `reviews` array:

### Establishment fields

| Field | Description |
|---|---|
| `establishment` | Name of the establishment |
| `city`, `state` | Location |
| `osm_id` | OpenStreetMap ID (optional) |

### Review fields

| Field | Description |
|---|---|
| `restroom_type` | Type of restroom (Men's, Women's, Unisex, etc.) |
| `youtube_url` | Link to the YouTube Shorts review |
| `rating` | Rating out of 10 (optional) |
| `date` | Date of review |
| `notes` | Additional notes (optional) |

## Adding a review

Add a new object to the `reviews` array of the relevant establishment in `_data/reviews.json`, or add a new establishment entry. Push to `main` — GitHub Pages will rebuild automatically.
