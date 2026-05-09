# AI Prompt Quality Checker

A lightweight, single-file tool that scores any AI prompt across 5 dimensions and suggests an improved version — no backend, no API key, no setup required.

## What It Does

Paste any prompt you'd use with ChatGPT, Claude, or any other AI tool. The checker scores it out of 100 across:

- **Clarity** — Is the task specific and unambiguous?
- **Context** — Does it give the AI enough background?
- **Constraints** — Are there length, tone, or exclusion rules?
- **Success Definition** — Does it describe what good output looks like?
- **Risk Level** — How likely is the AI to hallucinate facts?

It then generates an improved version of your prompt with the weak spots patched.

## How to Use

1. Download `PromptChecker.html`
2. Open it in any browser
3. Paste your prompt and click **Analyse**

No installation. No dependencies. No internet connection required after the file loads.

## Tech

- Pure HTML, CSS, and vanilla JavaScript
- All scoring logic runs client-side
- Session-based rate limiting (5 uses per session via `sessionStorage`)
- Zero external dependencies

## Limitations

Scoring is based on keyword and pattern matching, not AI inference. It reliably catches structural weaknesses (missing context, no constraints, vague tasks) but won't catch semantic issues or domain-specific problems. Treat scores as a structural checklist, not a guarantee of output quality.

## Built By

[Aakash Sethi](https://linkedin.com/in/aakash-sethi) — Growth & GTM  
[Portfolio](https://aakashsethi.lovable.app)
