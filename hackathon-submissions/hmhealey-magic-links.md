### Hackathon 2020 - Magic Link Sign-in

Remembering passwords is hard, so I added magic link sign-in to Mattermost. Instead of entering your username and password, you can request an email containing a link that will log you into Mattermost.

A video demo of what this looks like is available [here](https://community-daily.mattermost.com/files/x8zrxjy4bibktm68mojrcasn7r/public?h=eQcOd9RxtYq7uC75D46Oo2yE2AuSlekHJ-zjZzPQDh4).

In the future, we could use this to make sign-in from other devices easier like WhatsApp where you scan a QR code to log into other devices. We could easily convert the sign-in link to a QR code that can be scanned on a mobile device to log in without the user having to re-enter their login credentials or go through SSO again.

#### What should work

- Signing in with an email link
- Being able to request an email link by entering your username or email
- Toggling the feature from the System Console
- Emailed links expire after 5 minutes

#### What still needs to be done

- A lot of cleanup and TODOs to resolve
- Tests

#### Links
- https://github.com/mattermost/mattermost-redux/tree/hh_hackathon-magic-links
- https://github.com/mattermost/mattermost-webapp/tree/hh_hackathon-magic-link
- https://github.com/mattermost/mattermost-server/tree/hh_hackathon-magic-links
