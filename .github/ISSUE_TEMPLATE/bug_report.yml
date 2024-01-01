name: Report Bug
description: "Report a bug that does not abruptly end a game session or prevent the start of the game."
labels:
- "bug"
body:
- type: markdown
  attributes:
    value: 'Examples of this category include: item duping, item voiding, cannot craft item, behavior and description does not match.

    Please note if you merely want a change, e.g. think something is too OP, you should use the Suggest a Change template instead.'
- type: input
  id: version
  attributes:
    label: Your Pack Version
    description: What version of the pack are you playing? If you're using an ancient version maybe first try updating the pack. We usually fix hundreds of issues per release, so there is a good chance your problem have been fixed already in the latest version. There are also usually Dev releases inbetween Official releases that may not show up on other platforms.
    placeholder: "Example: v0.0.0"
  validations:
    required: true
- type: textarea
  id: expectation
  attributes:
    label: Your Expectation
    description: What did you try to do, and what did you expect to happen? Attach screenshots if needed.
    placeholder: "Example: Trying to craft Foo. Expect to consume 1 Bar and get 1 Foo."
  validations:
    required: true
- type: textarea
  id: actual
  attributes:
    label: The Reality
    description: What happened instead? Attach screenshots if needed.
    placeholder: "Example: 1 Foo is crafted but no Bar is consumed."
  validations:
    required: true
- type: textarea
  id: proposal
  attributes:
    label: Your Proposal
    description: Please describe it briefly in one or two sentences.
    placeholder: "Example: Consume 1 Bar properly."
  validations:
    required: true
- type: checkboxes
  id: final
  attributes:
    label: Final Checklist
    description: Please mark them so we can better handle this report
    options:
      - label: "I can reproduce this problem consistently by follow the exact steps I described above, or this does not need reproducing, e.g. recipe loophole."
        required: true