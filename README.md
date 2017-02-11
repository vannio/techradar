# Techradar battery test

A looping website loader for Techradar's mobile device battery experiments.
This literally loads a bunch of websites, one after another, into an iframe to simulate hours of endless browsing.

### Example video:

[![Example video](https://img.youtube.com/vi/KNcTPHaLwDg/0.jpg)](https://www.youtube.com/watch?v=KNcTPHaLwDg)


### Notes
- Predefined list of sites need to be loaded in the same order for consistency
- Duration between switching websites must be the same
- Custom duration (in seconds) can be set via query string using the `seconds` key
- Do not include any intentional caching
