# Accessibility

Praxity makes tools for people who build and review online courses. Some of
them exist to find accessibility barriers, so we treat a barrier in our own
tools, documentation or generated reports as a bug and fix it ahead of other
work.

This page applies to every public Praxity repository that does not have its
own ACCESSIBILITY.md.

## What we aim for

- Documentation, generated reports and web interfaces meet WCAG 2.2 level AA.
  This is a goal. No one has audited them yet, and we do not claim conformance.
- Every feature works from the keyboard.
- Command-line output reads in order with a screen reader and never relies on
  colour alone.
- Reports and dashboards work in light and dark colour schemes, at 200% zoom
  and at 320 CSS pixels wide.

Each repository's README lists the operating systems and runtimes it supports.

## Known barriers

Open issues labelled
[`accessibility`](https://github.com/search?q=org%3APraxity+label%3Aaccessibility+is%3Aopen&type=issues)
list the barriers we know about.

## Report a barrier

Open an issue in the repository and start the title with "Accessibility:".
Tell us what you were trying to do, what happened, and the operating system,
browser and assistive technology you used.

If GitHub issues do not work for you, email
[hello@praxity.io](mailto:hello@praxity.io).

Leave out private course content and learner data unless you have permission
to share it.

## Contributing

Pull requests that change a report, page or interface should say how the
change was checked with a keyboard and, where it applies, a screen reader.

## Ownership

The Praxity maintainers keep this page and review it when a project's
interface or report format changes.
