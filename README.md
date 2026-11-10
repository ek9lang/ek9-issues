# EK9 issues

This is where to report a problem with EK9: the language and compiler, the IDE, the MCP tools, the documentation, or
installing it. Choose **New issue** and pick the form that fits; each form asks only for what is needed to reproduce
the problem.

- **The fastest route to a fix:** run `ek9 -reportbug` after a crash. It writes a report file with the crash
  fingerprint, your environment and the smallest program that shows the problem. It removes your home path, user
  name and host name, and it prints the form to use. Read the file before you paste it - issues here are public.
- **A security problem?** Do not open an issue. See [SECURITY.md](SECURITY.md) and use **Report a vulnerability** on
  the Security tab.
- **A question rather than a problem?** Search the Q&A at https://ek9.io/qa/ or with `ek9 -q <words>`.
- **Documentation:** https://ek9.io, or offline with `ek9 -docs` in a desktop installation.

Please search the existing issues first: the same problem often shows up in the compiler, the IDE and an MCP tool at
once, and it is one issue.
