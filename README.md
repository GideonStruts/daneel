# 🤖 MaishaMoney AI

## Empowering Financial Journeys, One Cent at a Time

Empowering Financial Journeys, One Cent at a Time.

### [Demo site](https://650ee3b3a1f7c12fa3b56ebf--incredible-croquembouche-75bc92.netlify.app/).

## Features

- :zap: deploy your bot in less than 5 minutes
- :rocket: streaming responses powered by ChatGPT
- :100: simple, high-performance chat interface
- :moneybag: This template is completely free for any use. Use free OpenAI
  credits to get started, and deploy your site for free to Netlify.
- ⚛️ easy to customize: built with React, Tailwind and TypeScript

## Getting started

1. [Sign up for an OpenAI account](https://platform.openai.com/signup) and
   [get your API key](https://platform.openai.com/account/api-keys)
2. [Deploy to Netlify](https://app.netlify.com/start/deploy?repository=https://github.com/ascorbic/daneel),
   pasting the API key when prompted
3. [Customize your bot](#customizing-your-bot)
4. [Share your creation](https://github.com/ascorbic/daneel/discussions/categories/show-and-tell)

## Customizing your bot

### Name

Edit your site title and description in `src/App.tsx`

### Prompt

The prompt is set in `config.edge.ts`. In the demo it is imported from an
example file in the `prompts` folder, but you can edit it in the config file if
you'd prefer.

The important parts in this prompt are:

- who the bot is and what it should do.
- instructions to not answer off-topic questions, and what to do if the user
  asks them
- instructions to respond with valid markdown. This is optional, but it allows
  the bot to respond with formatted text.
- contextual information about the date and user location. These are optional
  but can help the bot to be more accurate.

### Design

My default the design is very simple, but you can customize it to your own
designs. The site is stule with [Tailwind](https://tailwindcss.com/), so you can
use any of the Tailwind classes to style your bot. The main components are:

- `src/routes/index.tsx` - the main chat interface
- `src/components/Welcome.tsx` - the welcome screen
- `src/components/ChatMessage.tsx` - the chat message component

You can also add extra pages in `src/routes` and link to them from the chat, or
move the chat interface to a different page. The chat interface is an
[Impala](https://github.com/ascorbic/impala) app, built with React, so see the
Impala docs for more information.

---

Released under the MIT license. Free for any use. ©
