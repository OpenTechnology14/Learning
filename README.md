# Learning

A learning environment that grades **understanding** instead of homework.
Students look at a visual for a concept, explain it in a chat with an agent,
and the agent grades how well they understand it.

## How it fits together

- **Subjects** – listed in [`subjects.md`](subjects.md). High school covers the
  core curriculum; college covers only true STEM plus philosophy and
  theoretical physics. Subjects are kept large where possible.
- **Concepts** – each subject has 5–7 concepts in
  `subjects/<level>/<subject>.md`, foundations first.
- **Grade** – every concept gets a grade from 0 to 100. The agent decides when
  it has chatted enough to grade; until then the grade stays `—`. The rules for
  each subject are set while we test it and written into that subject's
  `Grading rules` section.
- **Visual** – each concept gets one whiteboard-style visual: a drawing plus
  handwritten-style notes. It is the prompt the student explains. The
  `Whiteboard` column describes what it should show. On hold for now; see
  [`TODO.md`](TODO.md).
- **Connections** – [`connections.md`](connections.md) shows what each track
  rolls up to: math to string theory and computers, biology to philosophy,
  language, and modern health.
- **Movie** – later, each subject gets a movie built from its concept visuals,
  following its track in `connections.md`.

## Status

Draft. Concepts are written for six subjects so we can align on the format
before doing the rest:

| Level | Subject | File |
|---|---|---|
| High school | Algebra | [`subjects/high-school/algebra.md`](subjects/high-school/algebra.md) |
| High school | Biology | [`subjects/high-school/biology.md`](subjects/high-school/biology.md) |
| High school | Spanish | [`subjects/high-school/spanish.md`](subjects/high-school/spanish.md) |
| College | Classical Mechanics | [`subjects/college/classical-mechanics.md`](subjects/college/classical-mechanics.md) |
| College | Engineering | [`subjects/college/engineering.md`](subjects/college/engineering.md) |
| College | Philosophy of Science | [`subjects/college/philosophy-of-science.md`](subjects/college/philosophy-of-science.md) |
