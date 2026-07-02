# Spot-Finder

Discover and save the perfect spots around Steinkjer and Trøndelag.

## Overview

Spot-Finder is a tool to find, rate, save, and share great locations in the beautiful region around Steinkjer, Norway. Whether you're looking for hiking trails, fishing spots along the fjord or Steinkjerelva, scenic photography locations, quiet parking areas for nature access, or hidden gems for outdoor activities — this app helps you discover and remember them.

## The Area: Steinkjer's Surrounding Nature

Steinkjer lies at the head of the Beitstadfjord (part of the great Trondheimsfjord) in central Norway’s Trøndelag region. The town is cradled by a beautiful and varied landscape of fertile agricultural valleys, rolling hills, and dense boreal forests of pine, spruce, and birch.

The Steinkjerelva river flows through the area before emptying into the fjord, creating a rich corridor of wetlands, meadows, and woodlands. The surrounding nature offers excellent opportunities for hiking, fishing, berry picking, birdwatching, and boating in summer, while the hills and forests provide trails for cross-country skiing and snowshoeing in winter.

This blend of fjord, river, farmland, and accessible wilderness gives Steinkjer a distinctive charm — peaceful countryside right on the doorstep of more rugged outdoor terrain. The region serves as a natural gateway to both gentle recreational areas and deeper wilderness experiences typical of Innherred.

## Planned Features

- Interactive map with spots around Steinkjer, Levanger, and nearby areas
- Categories: Hiking, Fishing, Photography, Parking/Nature Access, Scenic Viewpoints, Foraging, Winter Activities
- User reviews, ratings, and photos
- Save favorites and create personal collections
- Filters by distance, season, difficulty, accessibility
- Offline support for downloaded maps and spots
- Share spots with friends or export lists

## Getting Started (Development)

```bash
git clone git@github.com:WKampfisk/Spot-Finder.git
cd Spot-Finder
```

## Tech Stack

**To be decided.** Current ideas:

- Simple static web app (HTML + Tailwind + Leaflet.js for map) for quick MVP
- Possible future: PWA, or integration with base44 platform
- Data: JSON-based spots initially, later database

Suggestions welcome!

## Example Spots (Initial Ideas)

- Steinkjerelva river access points for fishing
- Viewpoints overlooking Beitstadfjorden
- Forest trails near Ogndal or surrounding hills
- Parking areas with easy access to nature
- Hidden photo spots along the fjord

## AI / Expert Prompts

This repo includes a detailed system prompt for a local outdoor expert:

- `prompts/systemprompt-lokal-friluftsekspert-steinkjer.md`

The prompt turns an AI into the foremost local friluftsekspert for Steinkjer, with strict rules for accurate, quiet-spot-focused recommendations.

Intended for use in Spot-Finder features (chatbot, recommendations, data generation).

## Contributing

Pull requests welcome! Especially:
- Real local spot data (with GPS, verified details)
- Additions for local Steinkjer/Trøndelag spots
- Improvements to the expert prompt

## License

TBD
