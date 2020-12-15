#### 1. Cypress Cheatsheet
- [pr-mattermost-developer-documentation-745](https://github.com/mattermost/mattermost-developer-documentation/pull/745)
- [pr-mattermost-webapp-7218](https://github.com/mattermost/mattermost-webapp/pull/7218)

Goal is to make it easier for contributors to write Cypress E2E, find an up-to-date best practices and ready to use (copy/paste) examples on how to work on particular section of the web application. The submitted cheatsheet is not yet complete. It’s just a starting point and the same will be applied for Detox.

#### 2. Webapp Insight with [Lighthouse]https://github.com/GoogleChrome/lighthouse)
Analyze webapp with [Lighthouse](https://github.com/GoogleChrome/lighthouse) and get an actionable insights to improve performance, accessibility and best practices.
- Can integrate in CI with [lighthouse-ci](https://github.com/GoogleChrome/lighthouse-ci), pass/fail on preset/adjustable assertions/threshold
- Can run before/after Cypress run on a regular basis

Playground at:
- http://lighthouse-test-server.dev.spinmint.com:9000/app/projects (maybe not be accessible in the future)
- https://github.com/saturninoabril/mm-lighthouse-ci
