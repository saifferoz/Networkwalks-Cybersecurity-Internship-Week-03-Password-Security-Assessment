# Networkwalks Cybersecurity Internship — Week 03
## Password-Security-Assessment

A portfolio record of two password-security assessment modules completed during a Cybersecurity Internship at **Networkwalks**.

This repository documents the workflows visible in the supplied internship screenshots. It covers:

- **PM1 — John the Ripper (JTR) / Johnny GUI:** a controlled password audit of a password-protected PDF.
- **PM2 — Networkwalks Hash Calculator and Password Cracker:** PDF hash extraction followed by a dictionary-based password test using the Networkwalks lab tools.

> **Evidence and accuracy note:** Documentation is based on the eight screenshots supplied for PM1 and PM2. The screenshots show the GUI workflow and successful completion states. They do not provide a complete terminal transcript, exact command history, or a reproducible lab file, so no unrecorded CLI commands or environment details are claimed here.

## Repository contents

| Path | Description |
|---|---|
| [`PM1-John-the-Ripper/`](PM1-John-the-Ripper/README.md) | PM1 objectives, tools, observed workflow, outcome, and sanitized screenshots |
| [`PM2-Networkwalks-Tools/`](PM2-Networkwalks-Tools/README.md) | PM2 objectives, tools, observed workflow, outcome, and sanitized screenshots |
| [`Key-Learnings.md`](Key-Learnings.md) | Technical and practical learning outcomes |
| [`Ethical-Considerations.md`](Ethical-Considerations.md) | Authorization, privacy, and responsible-use boundaries |
| [`.gitignore`](.gitignore) | Common local and temporary-file exclusions |

## Module summary

| Module | Focus | Evidence-based outcome |
|---|---|---|
| PM1 | PDF hash extraction and John the Ripper through Johnny GUI | Johnny displayed a completed PDF-format audit with one item cracked |
| PM2 | Networkwalks Hash Calculator and dictionary Password Cracker | The tool showed a successful dictionary match against the lab PDF hash |

## Evidence handling

The screenshots in this repository are **sanitized portfolio copies**. Password values, hash strings, and internship flag values visible in the original captures have been obscured. The original uploaded ZIP is not copied into this repository.

## Scope and limitations

- The target shown in the captures is a password-protected PDF prepared for the internship lab.
- PM1 includes a screenshot of a PDF hash extraction webpage and a Johnny GUI result. Although the supplied ZIP also contained a John the Ripper Windows distribution, the screenshots do not show a CLI command sequence; therefore, this repository does not invent one.
- PM2 screenshots show the Networkwalks Hash Calculator and Password Cracker interfaces, including a built-in list of 100 words and visible attack progress.
- No real user accounts, third-party systems, or production data are represented as authorized targets in this write-up.

## Responsible use

Only perform password auditing on files and systems you own or are explicitly authorized to assess. Do not publish recovered passwords, raw password hashes, private files, or challenge flags. See [Ethical Considerations](Ethical-Considerations.md).

---

**Internship:** Networkwalks — Cybersecurity Internship, Week 03  
**Project:** Password-Security-Assessment
