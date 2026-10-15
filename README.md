# SRS Capture

Offline phone app for recording survey findings (photo + caption, area, status) and exporting them as a ZIP for the IRS Survey Recommendation Sheet generator (`srs_build.py`).

- Works with no internet once installed (Chrome → ⋮ → Add to Home screen).
- All survey data and photos stay on the phone (IndexedDB). Nothing is uploaded; this repo holds only the app code.
- Export: **Save ZIP** / **Share ZIP** → `srs_data.json`, `captions.csv`, `photos/`.

App: https://ashishpanwar4987.github.io/srs-capture/
