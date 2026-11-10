# EK9 issues

This is where to report a problem with EK9: the language and compiler, the IDE, the MCP tools, the documentation, or
installing it. Choose **New issue** and pick the form that fits; each form asks only for what is needed to reproduce
the problem.

- **The fastest route to a fix:** the smallest program that shows the problem, the exact message or output, and
  `ek9 -V`. Remove anything private first (paths, names, keys, company code) - issues here are public. After an
  internal compiler error, `ek9 -reportbug` writes this report for you, with your paths and names removed: paste
  the file it names.
- **A security problem?** Do not open an issue. See [SECURITY.md](SECURITY.md) and use **Report a vulnerability** on
  the Security tab.
- **A question rather than a problem?** Search the Q&A at https://ek9.io/qa/ or with `ek9 -q <words>`.
- **Documentation:** https://ek9.io, or offline with `ek9 -docs` in a desktop installation.

Please search the existing issues first: the same problem often shows up in the compiler, the IDE and an MCP tool at
once, and it is one issue.
