# annual-leave-tracker

Work's HR tool doesn't allow me to see a full year view so I built an AI slop application to do it for me. Also helps with planning AL around limits.

Future iteration ideas:

1. Add a limiter so you can't go above a value you specify.
1. See someone else's calendar to sync up holiday?
1. Customisable colours?

School holiday dates are underlined using Flintshire County Council's published term dates. The dates are derived from term starts, finishes, and half terms; school-specific training days are not included. [Source: Flintshire school holidays and training days](https://www.flintshire.gov.uk/en/Resident/Schools/School-Holidays--Training-Days.aspx).

For a local preview, run `python3 -m http.server 8000` and open `http://localhost:8000`. On localhost, sign-in is bypassed and leave selections and allowance are stored in that browser only; deployed versions continue to use Firebase authentication and Firestore.
