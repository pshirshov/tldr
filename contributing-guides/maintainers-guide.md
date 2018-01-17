# Maintainer's guide

The following guidelines are meant to provide a general basis
for the behavior expected of tldr-pages maintainers:

## I. Responding to contributions

- When responding to issues or pull requests,
  remember that you're temporarily the face of the tldr-pages project.
  **Be welcoming and friendly**, and if you don't know how to answer,
  ping other maintainers who you think might have a say.

- **Help keep the project responsive**.
  New discussion threads (issues or pull requests)
  should receive a response within 3 days, ideally.
  You can respond yourself
  or ask other members to provide their thoughts/opinions.
  In addition, if possible, try to hang around in the
  [Gitter chat room](https://gitter.im/tldr-pages/tldr)
  on a regular basis as well, or at least show up every now and then.

- **Know when and how to say no**.
  Sometimes requests or contributions need to be declined,
  at least in their current form.
  The project has developed multiple guidelines over time to handle edge cases
  — get acquainted with them, and point them out when necessary.
  Be polite, but firm: it saves everyone's time and patience
  to make expectations clear early.

- Always remember to **thank every contribution**,
  even when it can't be accepted (in fact, especially then).
  Keep in mind that
  [every form of contribution](https://github.com/kentcdodds/all-contributors)
  (pull request, feature request, bug report, etc.)
  is a voluntary gift of time offered to the tldr project
  by someone who cares about it,
  so make sure it's clear that that we don't take it for granted.

- Try to **keep the entire contribution process web-based**, if possible,
  to ensure it is accessible and straightforward.
  If you're comfortable with git, consider offering to perform
  interactive rebases or other command-line operations
  on behalf of contributors,
  or assisting them if they want to do it themselves.

## II. Handling PRs

- When merging PRs, use the **merge strategy that produces a clean git history**:
  If there's a single commit in the PR,
  or if the multiple commits are not semantically independent changes,
  use the `Squash and merge` method.
  If the PR author took the time to craft
  individual, informative messages for each commit,
  use the `Rebase and merge` method,
  to honor that work and preserve the history of the changes.
  For less clear-cut cases, a simple heuristic you can follow
  is that if there are more "dirty" commits than "clean" commits,
  then prefer squash, else do a rebase.

- Although having push access allows committing directly to the repository,
  please **create pull requests for all of your changes**,
  except the simplest ones (e.g. typo fixes).
  This ensures that the entire process that regular contributors go through
  is also exposed to maintainers,
  who can then identify and address bottlenecks or inconveniences.
  Similarly, **avoid merging your own PRs** unless approved by other maintainers.