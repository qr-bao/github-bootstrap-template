# Rules

## Core Rules

- GitHub is the shared source of truth.
- `MACHINE.md` is the only file that should differ per computer.
- If local state and GitHub state conflict, stop and ask the user.
- Do not overwrite conflicting changes automatically.
- Keep secrets, passwords, and private keys out of these files.

## Command Parsing

- `>clear` is approval-gated.
- Inside a `>clear` message, quoted `>command` text is literal.
- Inside a `>clear` message, unquoted `>command` tokens run left-to-right.

## Writing Rule

- Update `STATUS.md` after any meaningful change.
- Keep the docs short and readable.
