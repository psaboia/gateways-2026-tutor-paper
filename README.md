# A Wiki-Grounded Educational Gateway for Course-Aware Socratic LLM Tutoring

Priscila Saboia Moreira, Charles Vardeman II, Christopher R. Sweet. University of Notre Dame.
Gateways 2026, Washington, DC, September 23 to 25, 2026. Paper #29. Published open access (CC BY 4.0) in the ACM proceedings, DOI [10.1145/3859208.3859222](https://doi.org/10.1145/3859208.3859222).

Landing page: https://psaboia.github.io/gateways-2026-tutor-paper/

This repository holds the talk and a map of where everything else lives. The code and the data are in the repositories below, not here.

## What is where

| What | Where |
|------|-------|
| Paper | [`paper.pdf`](paper.pdf) in this repo, the author's version, identical in content to the published one. Published open access (CC BY 4.0) in *Gateways in the Age of AI (GATEWAYS '26)*, ACM, https://doi.org/10.1145/3859208.3859222. The DOI becomes active when the proceedings appear in the ACM Digital Library. |
| Talk slides | [`slides/`](https://psaboia.github.io/gateways-2026-tutor-paper/slides/) on the landing page: the deck as presented, 11 slides, arrow keys or click to move, N for speaker notes, F for fullscreen. The video plays on its slide. |
| Video clip shown in the talk, 55 s, silent | [`tutor-session.mp4`](tutor-session.mp4) in this repo. Tutor turns generated live by the Claude Code tutor against the course wiki, May 2026. The student was role-played by a co-author, not a student. |
| The tutor: launcher, Socratic prompt, course wiki | https://github.com/chrissweet/microelectronics-tutor-demo (wiki at `microelectronics-tutor-demo.wiki`) |
| Template a new course forks | https://github.com/chrissweet/llm-wiki-tutor-template |
| Evaluation supplement: all 225 probe sessions, raw JSON, probes, coding rubric, runners | https://github.com/psaboia/wiki-grounded-tutor-eval |
| The llm-wiki memory substrate the course wiki is built on, newest version, as a plugin | https://github.com/LA3D-LLM-Agents/llm-wiki-colab |
| The first version of the substrate, a GitHub template | https://github.com/crcresearch/llm-wiki-memory-template |
| Companion paper on the memory substrate, "Beyond Memory" | https://doi.org/10.5281/zenodo.21213176 |
| Course curriculum, Purdue SCALE | https://www.scale4me.org/scale-curriculum/introduction-to-engineering-with-microelectronics-curriculum-plan |

## The paper in one paragraph

Generic chatbots answer lab assignments well and, in doing so, remove the reasoning the assignment was designed to elicit. Giving the model the course notes does not fix this: a grounded answer is still a delivered answer. The gateway changes the interaction instead. A course wiki, about thirty Markdown pages the instructor curates, holds the knowledge. A Socratic prompt forbids answer delivery and requires every reply to cite a wiki page visibly. In 225 scripted adversarial sessions across three models, the refusal gave way in six incremental-extraction sessions and held in the rest. The tutoring principles are established. The contribution is implementation and governance: an instructor-controlled wiki, visible citation, an inspectable policy, and packaging another course can fork.

## Cite

Priscila Saboia Moreira, Charles Vardeman II, and Christopher R. Sweet. 2026. A Wiki-Grounded Educational Gateway for Course-Aware Socratic LLM Tutoring: Built on the llm-wiki Pattern. In *Gateways in the Age of AI (GATEWAYS '26), September 23–25, 2026, Washington, DC, USA*. ACM, New York, NY, USA, 6 pages. https://doi.org/10.1145/3859208.3859222

```bibtex
@inproceedings{saboiamoreira2026wikitutor,
  author    = {Saboia Moreira, Priscila and Vardeman, Charles, II and Sweet, Christopher R.},
  title     = {A Wiki-Grounded Educational Gateway for Course-Aware {S}ocratic {LLM} Tutoring: Built on the {llm-wiki} Pattern},
  booktitle = {Gateways in the Age of AI (GATEWAYS '26), September 23--25, 2026, Washington, DC, USA},
  series    = {GATEWAYS '26},
  publisher = {Association for Computing Machinery},
  address   = {New York, NY, USA},
  year      = {2026},
  isbn      = {979-8-4007-3218-8},
  doi       = {10.1145/3859208.3859222},
  numpages  = {6}
}
```

## Slides

`slides/index.html` is a self-contained HTML deck: one `<section>` per slide on a 1920x1080 canvas scaled to the window, Google Fonts for EB Garamond and IBM Plex Sans, figures beside it, and the video clip from the repo root. No build step. Edit the HTML directly.
