# Wonder Kids GK

Learn with flip cards, then take the Challenge quiz — a kids' general knowledge app.

- **5 topics**: Amazing Animals, Space Adventure, Our Wonderful World, Science Fun, Sports & Yummy Food
- **Learn mode**: tap a card to flip it, swipe to the next one, with sounds and fun transitions
- **Challenge mode**: 5 questions per topic, including multi-answer "(pick 2)" questions
- **No scroll**: everything fits on one screen; double-tap anywhere for the controls
- **Themes**: Sunny Day, Ocean Dive, Midnight Stars (in Settings)
- **Works offline**: content falls back to the built-in copy when there is no network

## Play it

https://new-meta-monkey.github.io/wonder-kids-gk/

## Change the content

All topics, cards and questions live in `content.json`. It follows `content.schema.json`.

To add or change content:

1. Edit `content.json` and bump `version` by 1.
2. Push. No rebuild needed — the app fetches `content.json` on load.

Rules: ids are lowercase with hyphens and never renamed once published; facts are one short simple sentence each; `correct` holds the 0-based indexes of the correct options (one entry = single answer, two or more = multi-answer with `multi: true`); card photos are free stock URLs, preflight-checked, with the bundled image as offline fallback.
