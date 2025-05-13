# TimeOfDayHTML
Dynamic HTML webpage that visually responds to the time of day by changing its background color.

## Functionality

The JavaScript script runs automatically when the page loads and checks the current hour of the day (based on the client’s local time). It changes the background color of the webpage depending on the following time periods:

- **Morning (6am – 12pm):** Mistry Rose (`#FFE4E1`)
- **Afternoon (12pm – 6pm):** Light Blue (`#ADD8E6`)
- **Evening (6pm – 9pm):** Peru (`#CD853F`)
- **Night (9pm – 6am):** Midnight Blue (`#191970`)

The transition between background colors is smooth and animated for a better visual experience.

**Live URL:** 

Deployment was done using [GitHub Pages / InfinityFree / 000WebHost] (choose one and edit this line). The webpage loads correctly on both desktop and mobile devices.

## Design Choices

- **Colors** were chosen to symbolically represent different times of the day.
- **Centered layout** and simple text for clarity and readability.
- **Minimal styling** was used to keep the focus on the dynamic behavior.

## Known Issues

- Time detection relies on the user's **local device time**, which
