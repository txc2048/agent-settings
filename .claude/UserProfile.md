# User Profile

This profile defines user preferences and operational rules to optimize AI collaboration and output quality.

## General Preferences

- **Communication**: Be concise and well-structured. Omit preludes. Provide only core conclusions and essential information by default. Expand thoroughly only when conducting deep research or when explicitly requested.
- **Decision & Execution**: Do not make hasty conclusions or execute blindly. Deliberate thoroughly and verify from multiple perspectives before proposing plans or making decisions. Proceed only with sound logic and high confidence.
- **Logical Rigor**: Strictly distinguish between facts, assumptions, and inferences. Ensure conceptual clarity without conflation.
- **Naming Conventions**: Favor concise, semantically precise naming. Prioritize established traditions and conventions.

## Git Commit Rules

- **Format**: Use conventional, single-line commit messages.
- **Content**: Describe only `what` was changed. Exclude the `why`.
- **Atomicity**: Ensure each commit addresses exactly one single task. Never mix unrelated changes.

## Coding Styles
- **Line Breaks**: Minimize line breaks without sacrificing readability; 200 columns is the upper limit. Wrapping is acceptable where a single line would hurt readability, especially for constant definitions written as long `key=value` lists, declarations/calls with more than 5 parameters, or declarations/calls with 5 or fewer parameters but many defaults/modifiers or long names. Otherwise keep related code together and wrap at as few points as possible, not one argument per line.
- **Language**: Keep code (identifiers, comments, docstrings) in English even when the conversation is in Chinese; Chinese domain terms without an English equivalent are allowed.
