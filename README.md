# geomojology

Community standard for emoji based map point symbologies

## What is this?

Unlike [geomoji](https://github.com/zacharlie/geomoji), which acts as a GIS-related alternative to a system such as [gitmoji](https://gitmoji.dev/), geomojology is a community standard for emoji based map point symbologies.

What that means is basically implementing a standard (and concise) collection for typical points of interest on maps in various contexts.

## Why?

Mostly, to make things simple and easy for map users and developers.

Firstly, there are not a lot of font symbols that are available cross-platform by default. Ensuring that the fonts are available for all implementations of a map project across various platforms is a significant challenge, even when leveraging openly licensed type faces.

As smaller screen devices and web technologies proliferate, it makes sense to have a standard and intuitive "universal reference" available for generic map implementations and common use cases or contexts (e.g. base maps/ disaster maps/ topographic maps).

By leveraging font based symbols and using unicode emoji icons as symbol graphics, the user experience can be greatly improved.

The concept may be thought of as the emoji based version of the [chizukigou](https://en.wikipedia.org/wiki/List_of_Japanese_map_symbols) used in Japanese cartography.

## Doesn't a map legend do that?

Absolutely. The map legend does precisely what geomojology intends to, with a few caveats, namely:

- Legends are context specific and not typically transferrable, especially between agencies across international borders
- Legends and symbols are not standardised (users have to "learn" each legend in order to effectively read the related map)
- Legends are not always practical (especially on large collections of points of interest, or on small screen devices like a smartwatch)
- Legends are not optimal solutions for managing i18n, l10n, and a11y

## Functions

Geomojology alleviates these issues by:

- Providing a standard for map point symbologies which any user familiar with the standard can instantaneously make sense of
- Instead of including a legend for POIs, a simple reference to the geomojology service can be used for all pois
- Emoji are rendered in the native context of the device, browser, or application, rather than a generic font library which renders the same across different platforms
- Emoji are inclusive and not language specific
- No external font libraries or package dependencies are required for effective symbology, regardless of platform

## Collections

Legends and maps are often context specific. It makes sense to have a number of standard collections which perform this function across a variety of contexts.

Todo: find matching emojis

### General

Default topics and categories expected to be outlined here:

-  Airplane Airports and airfields
-  Beaches
-  Bridges
-  Buildings and industrial facilities
-  Cemeteries, mausoleums, and crematoria
-  Culture and heritage sites (Landmarks, Monuments, Museums, Libraries, Galleries)
-  Ecological sites (Protected Areas, Research Facilities, Game Parks, Zoos, Aquariums)
-  Emergency services and other health care facilities
-  Entertainment and Leisure (Campsites, Casinos, Sporting arenas and events)
-  Gas stations and fuel facilities
-  Government Offices
-  Hospitals
-  Hotels and accommodation
-  Infrastructure (Light houses, substations)
-  Law enforcement agencies
-  Parking facilities
-  Ports and maritime infrastructure
-  Religious sites and buildings
-  Restaurants and bars
-  Schools and educational institutions
-  Shops, malls, and markets
-  Tourist Attractions
-  Transportation
-  Vegetation (Alien)
-  Vegetation (Endemic)
-  Vehicles, craft, and vessels
-  Other

### Disasters

-  Avalanche
-  Drought
-  Earthquake
-  Flood
-  Flashflood
-  Fog
-  Heatwave
-  Impact event
-  Landslide
-  Limnic eruption
-  Mudslide
-  Sinkhole/ Subsidence
-  Tsunami
-  Volcanic eruption
-  Wildfire
-  Storms (General)
-  Blizzard/ Snowstorm/ Icestorm
-  Electrical storm/ Thunderstorm
-  Hailstorm
-  Tornado
-  Windstorm/ Hurricane/ Tropical Cyclone
-  Nuclear disaster
-  Infrastructure failure
-  Terrorist attack
-  Civil unrest
-  Act of war
