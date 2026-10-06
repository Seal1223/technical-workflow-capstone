# Security Notes

## Repository Classification

This repository is public and contains only intentionally sanitized technical-learning material.

Sensitive personal, family, professional, operational, credential, and private Homestead OS information must not be published here.

## Never Commit

Never commit:

- Passwords
- API keys
- Authentication tokens
- SSH private keys
- Private certificates or cryptographic keys
- Environment files containing credentials
- Sensitive personal or family information
- Sensitive professional or operational information
- Private Homestead OS security or infrastructure details

## GitHub Security Features Reviewed

- Secret scanning / secret protection
- Dependency security / Dependabot concepts
- Code scanning
- Repository visibility
- Branch protection / ruleset concepts

Advanced CodeQL, GitHub Actions security workflows, and enterprise repository controls are deferred beyond Phase 00.

## Secret Compromise Response

If a real credential is accidentally committed:

1. Treat the credential as compromised.
2. Revoke or rotate the credential immediately.
3. Clean the repository history if necessary.
4. Verify the replacement credential is not exposed.
5. Never assume deleting the visible line from the latest commit makes the secret safe.

## SSH Key Security

The public SSH key may be shared with services such as GitHub.

The private SSH key must remain private and must never be committed, uploaded, or shared.