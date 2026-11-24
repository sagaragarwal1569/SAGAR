# Sagar

Say it your way. Sagar makes it clear.

Sagar is a small web page that turns rough words into clear writing. It was built for a second-year engineering student who is still building their English.

## Modes

- **Prompt**: rough words in, a clean prompt out. Choose ChatGPT, Gemini, Claude or any AI.
- **English**: fixes grammar and spelling and keeps your meaning.
- **Learn**: simple explanations with examples, a common-mistakes list and a practice question.
- **Code**: fixes errors and writes small programs, with copyable code blocks. Python, C/C++, Java and Web.

Each person's history is saved privately to their own Claude account. If that is not available, it is saved in the browser on that device.

## How it works

The whole app is one file, `sagar.html`. It has no server and no API key in the code. It asks Claude for answers through the page features that Claude gives to a published artifact:

- `sample` asks Claude to rewrite or explain.
- `db` and `user` keep each person's history, private to them.

## Run it

1. In Claude, publish `sagar.html` as an artifact with the `sample`, `db` and `user` capabilities.
2. Open the artifact link while signed in to Claude.
3. Share the link from the artifact's Share menu. Give people Contributor access so their history can be saved.

Opened as a plain file in a browser, the page loads but cannot reach Claude. It then shows a red message that says so.

## Files

- `sagar.html`: the page
- `logo/sagar-logo.svg` and `logo/sagar-logo.png`: the logo, a sun setting into the sea
