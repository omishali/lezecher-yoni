# אתר לזכרו של יוני תורג'מן ז"ל

Static memorial site based on the booklet "מיומנו של בחור ישיבה" (`../yoni.pdf`).

## Run locally

    cd site
    python3 -m http.server 8000

Then open http://localhost:8000

## Pages

- `index.html` – home: portrait, opening quote, about, family words, Rav Wieder's letter
- `diary.html` – diary excerpts organized by the Mesillat Yesharim traits
- `memories.html` – "קווים לדמותו": stories from friends, חניכים and family
- `dedications.html` – dedications, with a gallery of the handwritten scans
- `essay.html` – Yoni's essay "אשר יעשה אותם האדם וחי בהם"

Plain HTML/CSS, no build step. It can go on GitHub Pages as is.
