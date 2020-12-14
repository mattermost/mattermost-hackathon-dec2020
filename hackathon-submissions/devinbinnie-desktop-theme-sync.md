Integration of webapp themes into the desktop. This will replace the existing light/dark theme with whatever theme the webapp is using.

Based on the existing BrowserView code since we're moving to that.
Done for the 2020 MM Hackathon.

What's done:
- Desktop app changes theme when the webapp theme changes via Account Settings or between teams
- Desktop app changes theme when different servers are selected
- Theme is pulled down directly from the server on initial load

What's not done:
- Websocket stuff to update the theme on prefs change (I really wanted to do this :()
- A bug that pops up parsing the JSON sometimes
- Exact choice of colour mapping from webapp theme > desktop theme (just took a general stab at it)
- Various other edge cases

PRs:
- Desktop: https://github.com/mattermost/desktop/pull/1428
- Webapp: https://github.com/mattermost/mattermost-webapp/pull/7219