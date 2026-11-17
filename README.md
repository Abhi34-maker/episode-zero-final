# Episode Zero

A story starter for new writers. Tap ready-made answers to five questions and get a story concept, a four-act outline, the loose ends to tie up, a plan for episode one and a seven-day roadmap, plus a plain-text story brief to copy.

Built by Abhinand P Nair for a Pocket FM Growth Manager application. This is an independent prototype. It is not an official Pocket FM product and is not affiliated with Pocket FM.

**Please note:** this prototype was built with Claude, but it is not connected to Claude or any other AI. Everything in it is pre-written, so choose from the ready-made answers. The page says this on its first screen and on every question.

## View it

Demo: `https://YOUR-USERNAME.github.io/episode-zero/` (replace after you turn on GitHub Pages). It runs entirely in the browser. Open `index.html` to run it locally.

## The problem

A new writer often has a spark but does not know the genre, how to structure a long story, how to build a hero or what makes a good first episode. Many stop before they draft anything. This prototype covers the first ten minutes: from "I have an idea" to "I know what I am writing and what to do this week."

## What already exists

I checked before building. Pocket FM already offers writer tools, based on public pages and press coverage (I could not see inside the logged-in products):

- **Pocket CoPilot:** idea generation, plot-hole and logic checks, cliffhanger help, character and episode tracking, localisation. A report reposted on [GeekBlog](https://geekblog.net/tech-news/pocket-fm-gives-its-writers-an-ai-tool-to-transform-narratives-write-cliffhangers-and-more/) says writers have had it since 2024. See also the [CoPilot page](https://copilot.pocketfm.com/).
- **Sherpa:** a multi-agent system for long serialized fiction, with ideation, planning, research, drafting and feedback agents and long-term story memory. See [this report](https://www.entangledtext.com/news/pocket-fm-launches-sherpa-an-ai-system-for-hundreds-episode-fiction) and [this one](https://www.newsbytesapp.com/news/science/pocket-fm-launches-sherpa-ai-assistant-for-serialized-fiction-creators/tldr).

So a generator for outlines and plot-hole checks is not new. This prototype targets the step before those tools: a first-timer who does not yet have a concept. It ends in a story brief the writer can take into whatever tool they use next. I do not know whether Pocket FM already has a guided flow for this, so treat the gap as a hypothesis.

## How it works

There is no AI running in the page. Every question, option, piece of advice and template was written in advance, so the same answers always give the same result.

1. **Start:** an optional working title and one-line idea, kept in the writer's own words.
2. **Your answers:** five questions (feeling, listener, hero, conflict, how episode one ends). Each has three to five options with examples, and the writer taps the closest one.
3. **Concept:** a script-style title page, a starter logline the writer edits, key fields and a four-act outline with a notes box under each act.
4. **Loose ends:** five questions every story like this needs to answer, chosen from the writer's answers, each with a box for the answer.
5. **Episode one:** a self-check, a four-beat planner and three tips based on the writer's choices.
6. **Roadmap:** seven small daily tasks ending in a finished first-episode draft, and a copyable story brief that includes everything the writer typed.

I tested all 960 combinations of answers to make sure the assembled text reads cleanly.

## Design choices

- **Friendly by default.** Rounded shapes, plain language, one instruction per screen ("Tap the option that feels closest") and no blank page.
- **The writer stays in control.** The page gives structure, not content. The logline, act notes and answers are the writer's to write.
- **No invented specifics.** There are no episode counts or running times, because those depend on the platform.
- **Honest about saving.** Notes stay on the page and are not stored, so the page says to copy the brief before leaving.
- **Accessible basics.** Real radio buttons and checkboxes, visible keyboard focus, light and dark themes, and reduced motion respected.

## Look and feel

The accent colour, `#E51B4D`, was sampled from the Pocket FM logo supplied by the author. It is set once as `--brand` at the top of the stylesheet, and every coloured surface derives from it. I did not find published Pocket FM brand guidelines, so the type, shapes and layout are my own choices. The page does not use Pocket FM's logo or wordmark.

## Hypothesis and metric

Writers who reach a clear concept in one sitting are more likely to draft episode one within seven days. The measure would be the share of new writers who go from idea to first-episode draft within seven days. **This has not been tested with real writers.** No results are claimed.

## How AI was used

The questions, options, advice and code were drafted with Claude, then edited and checked by the author. The finished page is not connected to Claude or any AI. An earlier version called Claude live to ask adaptive questions and write the concept. This version replaces that with ready-made answers so it works anywhere, including a public GitHub page, with no key or backend.

## Limits

- The advice is general craft guidance, not a judgement of a particular story.
- A fixed set of options cannot capture every idea. Writers can add their own words in the logline and notes.
- Not tested with real writers and not integrated with any Pocket FM product.
- Not tested on every browser or screen size.
