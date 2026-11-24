# Sagar

Say it your way. Sagar makes it clear.

Sagar is a small web page that turns rough words into clear writing. It was built for a second-year engineering student who is still building their English.

**Open it:** https://sagaragarwal1569.github.io/SAGAR/

## Modes

- **Prompt**: rough words in, a clean prompt out. Choose ChatGPT, Gemini, Claude or any AI.
- **English**: fixes grammar and spelling and keeps your meaning.
- **Learn**: simple explanations with examples, common mistakes and a practice question.
- **Code**: fixes errors and writes small programs, with copyable code blocks. Python, C/C++, Java and Web.

## First time you open it

Sagar uses Google's Gemini to answer, and each person uses their own free key.

1. Open https://aistudio.google.com/apikey and sign in with a Google account.
2. Press **Create API key** and copy it.
3. Paste it into Sagar and press **Save key**.

The key is saved in your own browser only. It is never in this code. Do not share it. If you think it leaked, delete it in AI Studio and make a new one.

On Google's free plan, what you type may be used by Google to improve its products. Keep private details out.

History is saved on your own device only. Each phone or laptop needs the key pasted once.

## Add it to your phone

Open the page in Chrome, choose the three-dot menu, then **Add to Home screen**. It gets the Sagar logo.

## Two versions

- `index.html`: the website above. It runs on GitHub Pages or from any web server, and talks to Gemini with your own key.
- `sagar.html`: a version for Claude. It runs as an artifact inside Claude and uses the person's Claude account, with private saved history. It does not work as a plain web page.

## Files

- `index.html`, `manifest.webmanifest`: the website
- `sagar.html`: the Claude version
- `logo/`: the logo (a sun setting into the sea) as SVG and PNG, plus phone icons
