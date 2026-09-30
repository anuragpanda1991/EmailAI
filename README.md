# EmailAI

Most people know what they want to say in an email, they just don't want to spend ten minutes figuring out how to phrase it. EmailAI fixes that. You type a rough description of what the email needs to cover, pick a tone, and it hands you back a finished, ready to send draft with a subject line already written in.

## How it works

The app runs entirely in the browser. There's no server and nothing to log into. When you click "Write the email," your description and chosen tone are sent straight to Google's Gemini API, and the response comes back as a properly formatted email that you can copy and use right away.

## What it does

You can describe your email however you'd naturally explain it to a friend, then choose a tone from friendly, formal, direct, apologetic, or persuasive, and a length from short, medium, or detailed. EmailAI puts together a complete draft including a subject line, and you can copy it to your clipboard with a single click. Since everything happens client side, there's no backend or database involved at all.

## Getting started

Open emailai.html in any browser, or visit the hosted version of the app. You'll need a Gemini API key, which you can create for free at aistudio.google.com without setting up any billing. Paste the key into the field provided, describe what your email should say, choose a tone and length, then click "Write the email" to get your draft. The key only ever lives in your browser tab and is used to call Gemini directly, it's never stored anywhere or sent anywhere else.

## Built with

The project is plain HTML, CSS, and JavaScript, calling the Gemini API (model: gemini-3.8-flash). There are no frameworks or build steps involved, which also makes it simple to deploy for free on any static hosting platform such as Netlify, Vercel, or GitHub Pages.
