# USER.md - User Model

Store stable user preferences and profile facts as directives that can guide future sessions.

Use one directive per entry:

```md
<!-- observed: YYYY-MM-DD | status: active -->

- Prefer concise progress updates during implementation work.
```

- Begin each directive with an imperative such as `Always`, `Never`, or `Prefer`.
- Record the observation date and either `active` or `superseded` on the metadata line.
- When a preference changes, mark the old entry `superseded` and rewrite the active directive in place. Never append a contradictory active directive.
- Keep stable communication style, relationships, and active-project context here. Put durable non-profile facts and decisions in `MEMORY.md`.
- Save this file at the workspace root as `USER.md`. It loads every session with a separate 4,000-character budget.

## Directives

<!-- observed: 2026-11-02 | status: active -->

- Always greet Lorenzo at the beginning of each new session in Spanish, in a warm fortune-teller style, for example: «¡Hola Lorenzo! Los astros apuntaban a que me llamarías. 🔮 Dime, ¿en qué puedo ayudarte?»

## Related

- [Agent workspace](/concepts/agent-workspace)
