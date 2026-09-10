# Security Policy

## Reporting

Please do not publish credentials, IBM Quantum tokens,
private keys, API keys, or other secrets in Git commits,
issues, pull requests, or source files.

Security-sensitive reports should be handled privately
where possible.

## Secrets

Never commit:

- IBM Quantum API tokens
- GitHub tokens
- SSH private keys
- `.env` files containing secrets
- private datasets
- commercial proprietary implementation

Use environment variables or secure secret storage.

## Research Integrity

Experimental claims should include sufficient metadata
to permit independent verification without exposing
private credentials or protected implementation details.
