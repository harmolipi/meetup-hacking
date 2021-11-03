# Meetup Hacking

Using a GET request to RSVP people to meetups.
URL: `curl https://www.meetup.com/Jax-Ex/events/281673210/?action=rsvp&response=yes`
1) RSVP to the event
`curl https://www.meetup.com/Jax-Ex/events/281673210/?action=rsvp&response=no`
2) Check status of event
`xdg-open 'https://www.meetup.com/Jax-Ex/events/281673210'`

## The plan
1. Build it in bash
2. Build it in Node
3. Put it into a React app

<!-- dpfcjsyccpbgb -->
`curl 'https://www.meetup.com/jax-code-and-coffee/events/dpfcjsyccpbgb/?action=rsvp&response=yes'`
`xdg-open 'https://www.meetup.com/jax-code-and-coffee/events/dpfcjsyccpbgb/'`
`xdg-open 'https://www.meetup.com/jax-code-and-coffee/events/dpfcjsyccpbgb/?action=rsvp&response=yes'`

Tried curl but it didn't work. Going to try something else.