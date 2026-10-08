# Learning

A learning environment that grades **understanding** instead of homework.
Students look at a visual for a concept, explain it in a chat with an agent,
and the agent grades how well they understand it.

## How it fits together

- **Subjects** – listed in [`subjects.md`](subjects.md). High school covers the
  core curriculum; college covers only true STEM plus philosophy and
  theoretical physics.
- **Concepts** – each subject has a simple list of concepts in
  `subjects/<level>/<subject>.md`, foundations first.
- **Grade** – every concept has a 0–100 grade. The agent fills it in after
  enough chatting with the student about that concept. It stays `—` until then.
- **Visual** – each concept gets one whiteboard-style visual: a drawing plus
  handwritten-style notes. It is the prompt the student explains. The
  `Whiteboard` column describes what it should show.
- **Movie** – later, each subject gets a movie built from its concept visuals.

## Status

Draft. Concepts are written for four subjects so we can align on the format
before doing the rest:

| Level | Subject | File |
|---|---|---|
| High school | Algebra I | [`subjects/high-school/algebra-1.md`](subjects/high-school/algebra-1.md) |
| High school | Biology | [`subjects/high-school/biology.md`](subjects/high-school/biology.md) |
| College | Classical Mechanics | [`subjects/college/classical-mechanics.md`](subjects/college/classical-mechanics.md) |
| College | Philosophy of Science | [`subjects/college/philosophy-of-science.md`](subjects/college/philosophy-of-science.md) |
