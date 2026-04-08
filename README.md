# AI Agent Skills 🔐

> A focused skill library for secure API review, built around OWASP guidance and practical remediation patterns.

## Overview ✨

This repository currently ships one curated skill: an OWASP-focused assistant for reviewing APIs, identifying security weaknesses, and shaping safer design decisions.

### What this skill helps with 🧭

- API security review
- OWASP Top 10 risk identification
- Authentication and authorization checks
- Input validation and injection defenses
- Rate limiting, logging, and sensitive data handling
- Secure API design and remediation advice

## Featured Skill 🛡️

<table>
	<tr>
		<td><strong>OWASP Secure API</strong></td>
		<td>Security-first guidance for reviewing endpoints, auth flows, data handling, and common API attack surfaces.</td>
	</tr>
</table>

Primary instructions live in [owasp-secure-api-skill/SKILL.md](owasp-secure-api-skill/SKILL.md).

Supporting references:
- 📘 [owasp-secure-api-skill/references/owasp-top10.md](owasp-secure-api-skill/references/owasp-top10.md)
- 📗 [owasp-secure-api-skill/references/secure-api.md](owasp-secure-api-skill/references/secure-api.md)

## Repository Structure 🗂️

```text
.
├── README.md
└── owasp-secure-api-skill/
    ├── SKILL.md
    └── references/
        ├── owasp-top10.md
        └── secure-api.md
```

## How to Use 🚀

1. Load [owasp-secure-api-skill/SKILL.md](owasp-secure-api-skill/SKILL.md) as the main instruction source.
2. Use [owasp-secure-api-skill/references/owasp-top10.md](owasp-secure-api-skill/references/owasp-top10.md) when the task is vulnerability-focused.
3. Use [owasp-secure-api-skill/references/secure-api.md](owasp-secure-api-skill/references/secure-api.md) when the task is about API design, auth, validation, rate limiting, or response handling.

## Design Intent 🎨

The README is intentionally minimal and high-signal:
- Clear first impression
- Quick path to the skill files
- Accurate structure that matches the repository
- Easy to extend if more skills are added later

## Contributing 🤝

Keep updates aligned with the actual repo layout and the skill’s current behavior. If you add more skills, expand the featured section and update the structure block.

## License 📜

MIT
