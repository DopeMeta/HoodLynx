# Best setup for this kind of narrative

## Short answer

Don’t rely on one chat model’s memory.  
Use:

1. **This repo (`lore/`)** as the source of truth  
2. A strong writing model for drafts  
3. An image model for posters / Terminal art  

## Recommended split

| Job | Best approach |
|-----|----------------|
| Continuity / no hallucination | This HoodLynx `lore/` folder (always) |
| Caption + Terminal copy | Claude or GPT with `SCOPE.md` + `TERMS.md` + latest posts pasted in |
| Long arc planning | Same + `narrative-strategy.md` |
| Image generation | ChatGPT image / Midjourney / Flux — with locked prompts from `timeline/drafts` |
| Quick riffs | Any model, then **file the winner here** before it becomes canon |

## Why ChatGPT alone drifted

Long chats mix used + unused ideas.  
For ARG work, canon must be files, not scrollback.

## Practical workflow for HoodLynx

1. Read `SCOPE.md` + `TERMS.md`  
2. Draft post in model  
3. Check against last 2–3 confirmed posts  
4. Save winner into `posts/` or `timeline/drafts/`  
5. Only then generate art  

## Model note

For story continuity inside Cursor, keep using this project + agent with the lore files open.  
For pure prose polish outside Cursor, Claude and GPT both work — the differentiator is whether you feed them the canon files every time.
