# Once Upon A Getaway Itinerary Builder

## Purpose
Create polished, client-facing, mobile-first travel itineraries for Once Upon A Getaway Travel Co. Use this skill whenever Hollie asks to build, revise, publish, or host a client itinerary.

## Intake workflow
Do not make Hollie fill out a form. Ask her questions conversationally and keep track of her answers.

Start with only the basics:
1. Who is the trip for?
2. Travel dates?
3. Starting point?
4. Final destination or trip goal?
5. Number of travelers, including children/ages?
6. What is already booked?

Then ask only the next relevant questions about:
- traveler vibe and priorities
- pace
- hotel budget and style
- food preferences
- must-dos and must-avoids
- driving tolerance
- flights, cruise details, transfers, tickets, or rental cars
- accessibility or dietary needs
- hotel links and quoted prices

Use information already provided in the conversation. Never make Hollie repeat details you already have.

## Brand
Business: Once Upon A Getaway Travel Co.
Voice: Hollie, Your Travel Bestie.
Style: playful, warm, polished, family-inspired, modern, useful, and human.
Design: navy, teal, pink, white, rounded cards, strong mobile formatting.
No em dashes.

### Official logo rule
The official Once Upon A Getaway logo is the existing repository file:

`assets/1.png`

Always use this exact file. Never redraw it, AI-recreate it, restyle it, alter the typography, substitute `logo.svg`, or embed a recreated/base64 logo.

For itinerary pages stored at:
`itineraries/<trip-slug>/index.html`

reference the logo as:
`../../assets/1.png`

Use that exact asset in both the header and footer.

## Research
Verify current travel details before finalizing:
- route order and drive times
- time zone changes
- hotel location and amenities
- restaurant location, operating days/hours, and fit with the route
- attractions, reservations, admission requirements
- official tourism information where possible

For every road-trip stop ask: "Is this actually on the way?"
Avoid unnecessary detours unless the experience is worth it and the detour is clearly explained.

## Hotels and pricing
Hotel prices must be prominent.

For every overnight show:
- hotel name
- city
- night/date
- quoted price
- why it fits
- verified useful amenities

Never guess hotel pricing.

### Expedia TAAP
Hollie may provide Expedia TAAP links.
- Never expose TAAP links in the client-facing page.
- Use them only as agent-side source information.
- Show the hotel name, public information, and Hollie's quoted price.
- If linking externally, use a public hotel/info page rather than the TAAP portal.
- Add that pricing is subject to change until booked.

### Direct-book properties
Clearly label direct-book properties.
If useful, say Hollie can also quote an Expedia-bookable alternative.

## Images
- Use multiple destination images when helpful.
- Never duplicate the same image unless explicitly requested.
- Prefer different views: downtown, waterfront, architecture, scenery, etc.
- Verify image URLs load before publishing.
- Replace broken images.
- Do not use stock/watermarked images.
- Never replace or alter `assets/1.png`.

## Standard itinerary page
1. Hero with official logo, trip title, dates, summary
2. Trip snapshot
3. Route strip
4. Hotel cost snapshot high on page
5. Daily itinerary with drive time, vibe, photos, timeline stops, meals, hotel price, route buttons
6. Foodie short list
7. Overnight stay summary
8. Timing/reservation notes
9. Footer with official logo and Once Upon A Getaway branding

## GitHub publishing
GitHub is the default host for client itineraries.

Repository:
`onceuponagetawaytravel/onceuponagetawaytravel`

Create each client itinerary at:
`itineraries/<unique-trip-slug>/index.html`

Do not overwrite another client's itinerary.

The expected public GitHub Pages pattern is:
`https://onceuponagetawaytravel.github.io/onceuponagetawaytravel/itineraries/<unique-trip-slug>/`

Before telling Hollie the link is ready:
- commit the itinerary file to the main branch
- verify `assets/1.png` exists
- verify the itinerary references `../../assets/1.png`
- verify hotel prices are present
- verify no Expedia TAAP URLs appear
- verify no duplicate images
- verify mobile styling
- verify all important links
- if GitHub Pages has not yet published, tell Hollie it may take a minute or two after the commit

## Update workflow
When Hollie changes one item, preserve the approved design and only update the necessary sections.
Examples:
- new hotel: update cost snapshot, day callout, hotel summary, price, and route if needed
- new restaurant: update timeline and foodie list
- new destination: recalculate route and drive time
- new photo: check it does not duplicate another photo

Republish the same itinerary path after revisions unless Hollie asks for a new version.

## QA checklist
Before final delivery:
- dates and weekdays match
- route is geographically logical
- stops fit the route
- drive times are reasonable
- time zone changes are noted
- hotel names/dates/prices are correct
- no TAAP links are client-visible
- direct-book stays are labeled
- images load and are not duplicated
- `assets/1.png` is the logo
- mobile layout works
- no em dashes
- required arrival deadline is protected

## Quick trigger
When Hollie says "Build me an itinerary" or "Use my Once Upon A Getaway itinerary skill," load this workflow, ask the intake questions conversationally, build the client-facing itinerary, revise it with her, then publish it to GitHub Pages when approved.
