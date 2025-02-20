# 🍜 KNoodle

KNoodle is KNoWS' Solid-based alternative to Doodle.
It allows you to find time slots that work for different people,
by using their availability calendar which is made available through a Solid pod.

## Run locally via HTTP server

1. Install dependencies via `npm i`.
2. Run HTTP server via `npm start`.

## Suggested changes for your use case

1. Update the variable `employeesUrl` in `js/index.js` to point to your list of people that will use KNoodle.
2. Update the method `fetchParticipantWebIDs` in `js/utils.js` to extract the people from the data that is found at `employeesUrl`.
3. Update the variable `participants` in `js/index.js` to remove the dummy people.

## Development

- You find all HTML of the application in `index.html`.
- You find the frequently asked questions page in the folder `faq`.
- You find all used libraries in the folder `lib`.
- You find all custom JavaScript in the folder `js`.

## License
This code is copyrighted by [Ghent University – imec](http://idlab.ugent.be/) and released under the [MIT license](http://opensource.org/licenses/MIT).