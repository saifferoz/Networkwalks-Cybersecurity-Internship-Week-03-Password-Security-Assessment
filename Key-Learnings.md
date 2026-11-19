# Key Learnings

The following points are based on the two Week 03 module workflows and the supplied screenshots.

## Technical learnings

1. **Hash extraction is a preparation step.** A password-protected PDF can be represented by a crackable hash format for offline password auditing.
2. **A hash is not the original password.** The hash representation is an input to the audit process; it should still be treated as sensitive because it can enable offline guessing.
3. **John the Ripper and Johnny.** John the Ripper is the password-auditing tool referenced by PM1, while Johnny provides a graphical interface. The supplied evidence records Johnny's result rather than terminal commands.
4. **Dictionary attacks use candidate lists.** PM2's interface showed a built-in list of 100 candidate passwords and a separate option to upload a text wordlist.
5. **A successful match is target-specific.** The displayed match means a candidate worked for the controlled PDF used in the exercise. It does not establish the strength of unrelated passwords.
6. **Verification matters.** The PM1 evidence includes a protected-PDF password prompt, and the PM2 interface instructs the user to open the PDF with the matched password.
7. **Performance readings are contextual.** The PM2 screenshot captured 91 of 100 candidates tried at 9 passwords per second. This is a single observed state, not a universal benchmark.

## Practical and professional learnings

- Keep an evidence trail for each stage: extraction, tool input, test progress, and completion.
- Redact raw hashes, recovered passwords, and challenge flags before publishing screenshots.
- Distinguish what a screenshot proves from what is merely assumed. Avoid adding commands, configurations, or environment details that are not documented.
- Use only authorized sample files and controlled lab environments.
