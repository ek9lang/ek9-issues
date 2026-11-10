# Reporting a security vulnerability in EK9

**Please do not report a security problem as a public issue.**

Report it privately through GitHub's private vulnerability reporting: open the **Security** tab of this repository
and choose **Report a vulnerability**. Only the EK9 maintainers can see what you send.

## What counts

Anything that could be abused, for example:

- the compiler or runtime doing something a program did not ask for (running code, reading or writing files,
  reaching the network);
- a way past EK9's safety guarantees: `sanitized` parameters, the URL policy, the capability declarations, or
  `Sensitive` values being revealed;
- an MCP tool or the IDE reaching outside the workspace it was given;
- a kit, a download or a package whose signature or checksum can be forged or bypassed;
- anything that exposes another person's data.

## What to include

- the EK9 version (`ek9 -V`) and the platform;
- the smallest program or steps that show the problem;
- what an attacker could do with it.

## What happens next

You will get an acknowledgement, and the problem will be fixed in a release before it is described publicly. You
will be credited in the advisory unless you ask not to be.
