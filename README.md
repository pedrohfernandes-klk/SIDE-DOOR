# SIDE DOOR

**Questions for another way in.**

SIDE DOOR is a small text-card app for finding another entrance into whatever is stuck: a decision, task, habit, conversation, plan, conflict, creative block, practical problem, or ordinary loop.

It does not give answers.

It gives one clear question that changes the entrance.

## Concept

Most stuck situations are not solved by staring harder at the front door.

SIDE DOOR asks the user to enter from the side: through the hidden rule, the quiet cost, the first small move, the missing information, the repeated pattern, the better frame, or the part of the situation that has been treated as fixed too early.

The app is not a productivity coach, therapy tool, puzzle game, or idea generator.

It is a compact reframing machine.

## Core interaction

1. Think of something stuck.
2. Press **OPEN A SIDE DOOR**.
3. Read one question.
4. Answer it in one sentence.
5. Press again only if the first door is false.

The ritual should stay simple.

No scores.
No visible categories.
No streaks.
No input fields.
No complex modes.

## Current interface

The app is a single-file HTML machine with:

* title: **SIDE DOOR**
* subtitle: **questions for another way in**
* main button: **OPEN A SIDE DOOR**
* subtle button tag: **ASIDE**
* one central question card
* Copy button
* Clear button
* About panel
* animated door/hinge icon
* deck counter only in About

The dynamic door icon reacts when a new question is generated.

## Current deck

Current deck size:

**999 side-door questions**

The cards are question-only.

The visible category labels were removed to keep the experience clean and immediate. The deck may still be internally shaped by hidden families, but the user should only see the question.

## Card philosophy

A good SIDE DOOR card should feel like a small latch opening.

The user should think:

> “Ah. That is another way into the situation.”

Not:

> “What does that even mean?”

Cards should be:

* short
* clear
* practical
* universal
* immediately usable
* lightly surprising
* grounded in ordinary life
* useful for decisions, tasks, conversations, habits, plans, conflict, and creative blocks

Avoid cards that are:

* too abstract
* too surreal
* too therapeutic
* too corporate
* too clever
* too dependent on “this”
* too dependent on system jargon
* too similar to other cards
* too long to understand at a glance

## Strong card examples

Good SIDE DOOR cards sound like this:

* What is the cleanest next move?
* What is being protected by the delay?
* Which part has been treated as fixed too early?
* Who benefits if the situation stays vague?
* What information is already available but unused?
* What would make the next step easier to start today?
* Which hidden reward keeps the pattern alive?
* What is being called complicated because it is uncomfortable?
* Which part is asking to be simplified, not solved?
* What would change if the side door were already open?

## Language rules

Avoid naked **this** when possible.

Instead of:

> What is the simplest useful version of this?

Prefer:

> What is the simplest useful version of the problem?

Or better:

> What is the smallest useful move available now?

Useful nouns include:

* the problem
* the situation
* the current route
* the pattern
* the next move
* the delay
* the decision
* the obstacle
* the conversation
* the cost
* the rule
* the pressure
* the loop
* the first step

Use **this** only when the sentence still feels clear without context.

## Hidden deck families

The deck should continue to develop around practical side entrances:

### Small move

Questions that reduce the situation to the first usable step.

Example:

> What move feels too small to count?

### Hidden rule

Questions that expose the rule keeping the situation stuck.

Example:

> What rule is making the situation harder than it needs to be?

### Loop

Questions that reveal repeated patterns.

Example:

> What keeps pulling the problem back into place?

### Cost

Questions that name the price being paid.

Example:

> Which cost is being paid quietly?

### Information

Questions that reveal missing or unused facts.

Example:

> What information is already available but unused?

### Frame

Questions that change what kind of problem this is.

Example:

> What changes if the frame is the problem?

### Permission or refusal

Questions that expose the yes or no missing from the situation.

Example:

> Which refusal would make the situation cleaner?

### Practical friction

Questions that locate the actual obstacle to the next move.

Example:

> What physical friction is blocking the very next step?

### Side route

Questions that find the alternate entrance.

Example:

> Where is the easiest honest entrance?

## Tone

SIDE DOOR should be intelligent but plain.

It should not sound like:

* a therapist
* a corporate facilitator
* a mystical oracle
* a puzzle master
* a productivity guru
* a management consultant

It should sound like a precise, useful question arriving at the right angle.

## Technical structure

SIDE DOOR is a self-contained HTML file.

It uses:

* HTML
* CSS
* vanilla JavaScript
* embedded card deck
* embedded SVG favicon
* Google Fonts:

  * Saira Stencil One
  * IBM Plex Mono

No backend is required.

No build process is required.

No user account is required.

No data is saved.

## JavaScript behaviour

The app:

* stores the cards in a `CARDS` array
* randomly selects one question per button press
* keeps a short recent-history buffer to reduce immediate repetition
* displays the selected question in the output card
* animates the door icon on generation
* copies the current question plus the app tag
* resets to the idle question when Clear is pressed
* updates the deck counter in About

## Privacy

SIDE DOOR runs locally in the browser.

It does not collect, store, transmit, or analyse user data.

There is no account, no database, no analytics, and no tracking.

## Design direction

Preserve the current SPARK TOOLS family identity:

* single-page app
* dark terminal-like interface
* large title
* strong central button
* clean output card
* mobile-first layout
* counter only in About
* dynamic icon reaction
* minimal controls

For SIDE DOOR specifically, preserve:

* dark blue / cream / gold palette
* door/hinge visual metaphor
* quiet **ASIDE** button tag
* no visible category labels
* one-card mode

## Future development priorities

1. **Audit the 999-card deck**

Remove cards that feel too strange, too vague, too long, too corporate, or too similar.

2. **Strengthen ordinary usefulness**

The best cards should work for a task, habit, decision, conversation, argument, plan, project, or loop within five seconds.

3. **Reduce abstraction**

Prefer concrete words like move, rule, cost, delay, pattern, route, permission, question, and step.

4. **Keep the app simple**

Do not add a second step, visible categories, scores, badges, or user choices yet.

5. **Improve mobile readability**

Longer cards should remain readable without shrinking too aggressively.

6. **Preserve the ritual**

The game feeling should come from pressing the button, receiving one question, and answering it in one sentence.

## SPARK TOOLS context

SIDE DOOR belongs to **SPARK TOOLS**, a suite of small text-based browser instruments.

Its role in the family:

* **IDK MACHINE** generates ideas.
* **THE WRONG QUESTION** finds the question underneath the question.
* **COUNTERWEIGHT** gives the strongest fair objection.
* **GRANTED** temporarily grants a premise.
* **SIDE DOOR** finds another entrance into the stuck thing.

SIDE DOOR should not duplicate the others.

It should remain the practical reframing machine.

## Core principle

SIDE DOOR is not here to answer the user.

It is here to change the entrance.

© HRF 2026. All rights reserved.
