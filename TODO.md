# To-do

Everything still needed to go from a curriculum draft to students actually
learning. Workstreams are in rough build order.

## 1. Content

- [x] Concept lists with key ideas for 8 subjects
- [ ] Concept lists for the remaining subjects in [`subjects.md`](subjects.md)
- [ ] Confirm or swap the ★ track picks in [`track-options.md`](track-options.md)
- [ ] Decide whether Modern Health becomes a third capstone
- [ ] Accuracy review of every concept's key ideas

## 2. Visuals

- [x] Visual style and reusable patterns ([`resources.md`](resources.md))
- [x] One visual idea per concept for the 8 drafted subjects
- [ ] Choose the build format: HTML/SVG animation (lightweight, interactive,
      runs on a page) or Manim (renders video, ready for the movies)
- [ ] Build the pilots: π unrolling, unit circle → sine, sine waves → square
      wave
- [ ] Build each concept's visual, then check it for accuracy
- [ ] Record audio for Spanish (pronunciation, phrases, songs)
- [ ] Alt text for every visual

## 3. Prompts

- [ ] **Visual prompt template** – turns an inventory entry into a finished
      visual in the agreed style
- [ ] **Explanation prompt per concept** – the question shown with the visual,
      e.g., "What is this circle doing, and why does it stop where it does?"
- [ ] **Follow-up guidance per concept** – what to probe when an answer is
      vague or sounds memorized
- [ ] **Grading prompt** – the agent compares the student's explanation to the
      concept's key ideas, decides when it has enough evidence, and gives a
      0–100 grade with a short reason quoting the student

## 4. The tutor skill

The agent itself, written as a Claude skill (`SKILL.md`) so every session runs
the same way.

- [ ] Session flow: show visual → student explains → follow-ups → grade
- [ ] **Teach, not just test:** when a student is stuck, replay the visual,
      give a hint or a simpler sub-question, point to an outside resource,
      then let them explain again
- [ ] **Come back later:** revisit concepts after a few days and let the grade
      rise or fall
- [ ] **Order:** use the tracks so a concept unlocks after the ones it builds
      on, and mention cross-links ("you saw this curve in Algebra")
- [ ] **Integrity:** keep grading live and conversational, since pasted
      AI answers don't hold up under follow-up questions

## 5. Student records

The `Grade` columns in the subject files are a template. Real grades need
their own storage.

- [ ] Per-student record: grade per concept, date, and quoted evidence
- [ ] Grade history, so progress over time is visible
- [ ] Privacy: who can see which student's records

## 6. Teacher view

- [ ] Class dashboard: grades per concept, and where most students are stuck
- [ ] Drill-down to one student's explanations

## 7. Testing and calibration

Run the agent through each subject, then write the rules we settle on into
that subject's `Grading rules` section.

- [ ] Sample answers per concept at several levels (strong, partial,
      memorized, wrong) to check the agent grades them consistently
- [ ] Re-run after any prompt change to catch grading drift

| Subject | Concepts | Visuals | Prompts | Tested |
|---|---|---|---|---|
| Algebra (HS) | ✅ | idea | | |
| Biology (HS) | ✅ | idea | | |
| Spanish (HS) | ✅ | idea | | |
| Classical Mechanics | ✅ | idea | | |
| Engineering | ✅ | idea | | |
| Philosophy of Science | ✅ | idea | | |
| String Theory | ✅ | idea | | |
| Computers & AI | ✅ | idea | | |

## 8. Movies

- [ ] One movie per subject: its visuals played in track order (see
      [`connections.md`](connections.md)), with narration added
