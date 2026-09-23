# A Wiki-Grounded Educational Gateway for Course-Aware Socratic LLM Tutoring

Priscila Saboia Moreira, Charles Vardeman II, Christopher R. Sweet. Center for Research Computing, University of Notre Dame.
Gateways 2026, Washington, DC, September 23 to 25, 2026. Paper #29.

Landing page: https://psaboia.github.io/gateways-2026-tutor-paper/

This repository holds the paper, the talk, and a map of where everything else lives. The code and the data are in the repositories below, not here.

## What is where

| What | Where |
|------|-------|
| Paper, revised version submitted 2026-09-07 (6 pages, ACM sigconf) | [`paper.pdf`](paper.pdf) in this repo. The ACM version will be linked here once published. |
| Talk slides | [`slides.pdf`](slides.pdf) in this repo (see below). |
| Video clip shown in the talk, 55 s, silent | [`tutor-session.mp4`](tutor-session.mp4) in this repo. Real tutor turns from a Claude Code session against the course wiki, May 2026. The student was played by a co-author. |
| The tutor: launcher, Socratic prompt, course wiki | https://github.com/chrissweet/microelectronics-tutor-demo (wiki at `microelectronics-tutor-demo.wiki`) |
| Template a new course forks | https://github.com/chrissweet/llm-wiki-tutor-template |
| Evaluation supplement: all 225 probe sessions, raw JSON, probes, coding rubric, runners | https://github.com/psaboia/wiki-grounded-tutor-eval |
| Companion paper on the memory substrate, "Beyond Memory" | https://doi.org/10.5281/zenodo.21213176 |
| Course curriculum, Purdue SCALE | https://www.scale4me.org/scale-curriculum/introduction-to-engineering-with-microelectronics-curriculum-plan |

## The paper in one paragraph

Generic chatbots answer lab assignments well and, in doing so, remove the reasoning the assignment was designed to elicit. Giving the model the course notes does not fix this: a grounded answer is still a delivered answer. The gateway changes the interaction instead. A course wiki, about thirty Markdown pages the instructor curates, holds the knowledge. A Socratic prompt forbids answer delivery and requires every reply to cite a wiki page visibly. In 225 scripted adversarial sessions across three models, the refusal gave way in six incremental-extraction sessions and held in the rest. The tutoring principles are established. The contribution is implementation and governance: an instructor-controlled wiki, visible citation, an inspectable policy, and packaging another course can fork.

## Slides

`slides.pdf` is exported from the presentation deck. To refresh it, download the deck as PDF and replace the file.
