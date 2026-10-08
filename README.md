# Singapore Heritage Quiz

Open `index.html` in a browser and select Start quiz on the welcome page to play. Keep the `images` folder beside it.
The site works offline and needs no installation or build step.

The quiz includes 30 questions in English, Chinese, and Malay. Wrong answers turn red
and allow another attempt. The correct answer turns green and reveals the Next
button. Answer positions shuffle each time a question is shown. The completion
screen includes a Play again button; no score is recorded.

To change the content, edit the `questions` array inside `index.html`.
Each question has four `options`, one matching `answer`, and a local `image` path.

Questions and pictures were imported from the supplied
[Google document](https://docs.google.com/document/d/1t98UgxOVPgFPkpC1DydU5H_neYXZ8liTGCBZY-_-zwI/edit?tab=t.0).
Question 5 had no explicit answer line; “Cassette tape / 录音带” was inferred
from its picture. Other supplied answer text, including “Tinkat,” was preserved.

For a local web preview, run `python3 -m http.server 8000 --bind 127.0.0.1`
from this folder, then open `http://127.0.0.1:8000`.
