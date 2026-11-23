# Halfway

Meet somewhere fair.

Halfway is a London-based web application that helps two people find a convenient place to meet based on public transport journey times.

Rather than choosing the geographical midpoint between two locations, Halfway compares estimated travel times to suggest meeting areas that work for both people.

## The Problem

Finding somewhere to meet in London isn't always straightforward.

A location that looks halfway on a map might take one person 15 minutes to reach and the other 45 minutes.

Halfway aims to make that decision easier by comparing public transport journeys and identifying meeting areas based on travel time rather than physical distance.

## How It Works

The planned application will allow users to:

Select two starting locations in London.

Compare public transport journey times to a set of potential meeting areas.

Choose between two recommendation modes:

Fairest Journey: Prioritises the smallest difference between both travellers' journey times.

Least Total Travel: Prioritises the shortest combined journey time.

View the top three valid meeting areas, with estimated journey times for each traveller.

Understand why a particular meeting area was recommended.

Recommendations will be based on the best option among the meeting areas evaluated, rather than every possible location in London.

## Tech Stack

The project is being developed using:

HTML5 — Semantic page structure and accessible forms.

CSS3 — Responsive layout and styling.

JavaScript — User interactions, API requests and recommendation logic.

TfL Unified API — Public transport journey estimates.

Vitest — Automated tests for the recommendation algorithm.

Git & GitHub — Version control and project management.

## Development Roadmap

[ ] Build an accessible interface for selecting two starting locations.

[ ] Retrieve and inspect a real journey using the TfL API.

[ ] Implement and test both recommendation algorithms.

[ ] Display recommended meeting areas and journey comparisons.

[ ] Deploy an initial version using clearly labelled sample data.

[ ] Integrate live TfL journey estimates.

[ ] Handle invalid inputs, unavailable journeys and API errors.

[ ] Test the application on desktop and mobile.

[ ] Publish the live application and document its limitations.

## Project Status

In development — initial setup.

The first milestone is to build a functional interface that captures two selected starting locations.

The long-term goal for the initial release is a publicly accessible application using real TfL journey estimates.

## Planned Limitations

To keep the initial release focused:

Only a predefined selection of London starting locations will be supported.

Meeting areas will be selected from a predefined list.

Journey estimates will depend on the information returned by TfL.

The application will not initially include maps, venue recommendations or user accounts.

## Future Improvements

Potential improvements after the initial release include:

Support for more London stations and meeting areas.

Interactive maps displaying recommended areas.

Nearby cafés, restaurants and other meeting venues.

More detailed journey preferences and accessibility options.

Support for groups of more than two people.

## Author

Developed as an independent software engineering project to explore full-stack development, API integration, algorithm design and user centred problem solving.
