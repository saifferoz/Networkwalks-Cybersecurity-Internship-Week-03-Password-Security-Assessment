# Ethical Considerations

Password auditing is a dual-use cybersecurity activity. The same techniques used to evaluate password resilience can be misused to access private files. The work documented here is presented as a controlled internship lab exercise.

## Authorization

- Test only files, accounts, and systems that you own or for which you have explicit, documented permission.
- Keep exercises within the scope and rules defined by the internship or lab provider.
- Do not use extracted hashes to attempt access to unrelated documents or accounts.

## Privacy and sensitive data

- Treat password hashes as sensitive data: offline guessing can be performed against them.
- Never publish recovered passwords, raw hashes, private documents, or challenge flags.
- The screenshots in this repository have been sanitized to obscure those values.
- Do not upload confidential documents to external hash-extraction services unless the owner has approved that service and its data-handling terms.

## Safe testing practices

- Use dedicated test documents and non-production data.
- Store test files and results securely, and remove them when no longer required by the lab.
- Avoid testing against live services or other people's accounts.
- Stop if authorization or scope is unclear.

## Reporting

A professional assessment report should describe the method and outcome without disclosing credentials. Where a password is recovered, report the finding securely to the authorized owner and recommend stronger, unique passwords and appropriate document-protection practices.

## Disclaimer

This repository is for educational and portfolio purposes. It does not grant permission to test any third-party file, account, or system. The author is not responsible for unauthorized use of the techniques described.
