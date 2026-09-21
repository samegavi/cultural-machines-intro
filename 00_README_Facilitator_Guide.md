# Cultural Machines: An Introduction
### A six-session course on large language models
Based on Leif Weatherby, *Language Machines: Cultural AI and the End of Remainder Humanism* (University of Minnesota Press, 2025).

## What's in this folder

| Notebook | Session | Core idea | Main activity |
|---|---|---|---|
| 00_Before_the_Machine | *Lead* · Before the machine: structure without a subject | Meaning as a self-organising system (Saussure, Jakobson); the maths parallel (Pourciau) | Sorting statements, Saussure's chess, the zero, numbers from nothing, turning the word-map |
| 01_What_an_LLM_Does | What a language model actually does | Machines capture genre and style before truth | Tokens, next-word odds, the "impossible news story" experiment |
| 02_Words_Defined_by_Other_Words | Words defined by other words | Saussure's system of differences; the "ladder of reference" | Mapping arts vocabulary in embedding space |
| 03_Why_It_Feels_Like_Someone_Is_There | The Eliza effect | Intelligence as simulacrum | Chatting with a 1966-style ELIZA, then a modern model with swappable personas |
| 04_The_Poetic_Machine | Attention and the poetic function | Jakobson's poetic function; "general poetics" | Visualising attention; testing the pull of repetition and poetic forms |
| 05_Packaged_Meaning | Defaults, clichés, ideology | Packaged semantics; ideology made measurable | Default scans, gender lean by arts role, the language "tax", cliché hunting |
| 06_Language_as_a_Service | The future of cultural work | Language as a service; the return of rhetoric; the limits of "human-only" work | The new commonplaces, measuring your edits, mapping your job, closing debate |
| 07_Bonus_Shannon_Redundancy | *Bonus* · Shannon and language as redundant pattern | Information theory; redundancy as a theory of meaning; Chomsky vs Shannon | The guessing game, approximations to English, measuring surprise with GPT-2, "whose English?" |

Each notebook runs on its own. Participants need a free Google account and nothing else: no installation, no API keys, no payment.

## Opening the notebooks in Colab

**Simplest:** upload the `.ipynb` files to a shared Google Drive folder. Participants open one, choose *Open with → Google Colaboratory*, then *File → Save a copy in Drive* so they have their own editable version.

**Nicer for a public course:** put the notebooks in a public GitHub repository. Each one can then be opened directly with a link of the form
`https://colab.research.google.com/github/<your-org>/<repo>/blob/main/01_What_an_LLM_Does.ipynb`,
which you can embed in a course platform, email or slide.

## Technical notes for the facilitator

- Notebooks 1, 2 and 4 run comfortably on Colab's free CPU. For notebooks 3, 5 and 6, ask participants to switch to a GPU first: *Runtime → Change runtime type → T4 GPU*. It is free but occasionally unavailable at busy times; the notebooks still work on CPU, just more slowly.
- The first run of each notebook downloads the models (GPT-2 is about 500 MB, the Qwen chat model about 1 GB, the embedding model about 90 MB). On a slow connection, start the setup cells at the beginning of the session while you introduce the topic.
- The models are deliberately small and open. They are much weaker than ChatGPT, Gemini or Claude, which makes their defaults and habits easier to see. Say this explicitly at the start, and where participants have access to a commercial chatbot, invite them to repeat key prompts there and compare.
- Generated text is random. Two people running the same cell will get different results, which is useful for discussion ("what did yours say?").
- **Run every notebook yourself before teaching.** Library updates on Colab occasionally break things; if a cell fails, *Runtime → Restart session* and running from the top fixes most problems.
- Session 5 includes greetings in Twi, Swahili, Yoruba and French. Have native speakers check and correct them, and invite participants to add their own languages.

## Suggested session rhythm (90 minutes)

1. **10 min** · Framing: the session's idea, in your words, ideally with an example from the local arts scene.
2. **50 min** · Work through the notebook in pairs. Pairing works much better than solo for people new to code.
3. **25 min** · Group discussion using the questions at the end of each notebook.
4. **5 min** · One sentence each: what will you notice differently this week?

For a two-day intensive, run sessions 1–3 on day one and 4–6 on day two.

## On the ideas in the course

The notebooks present their arguments in plain language rather than dense theory; most participants will not need any outside reading. The facilitator can introduce each session's idea in their own words, ideally with an example from the local arts scene.

## Keeping it balanced

The course takes a deliberately provocative line about what language models mean for culture, including a critical view of some well-known sceptics such as Noam Chomsky, Emily Bender and Timnit Gebru. It is designed to let participants argue back: Session 6 closes with a structured debate, and readings from the other side are listed at the end of the relevant notebooks.
