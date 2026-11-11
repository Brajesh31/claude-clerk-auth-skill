# Clerk Authentication

Implementation patterns for integrating Clerk authentication into web applications.

## Capabilities

- Configure Clerk providers and environment variables.
- Implement sign-in and sign-up flows.
- Protect routes with middleware and server-side checks.
- Work with organizations, roles, and access control.
- Handle webhooks and synchronize user data.
- Apply framework-specific patterns, including Next.js App Router.

## Usage

Use this skill when adding or maintaining Clerk-based authentication. Follow the setup and implementation patterns in `SKILL.md`, check the current Clerk SDK version and framework conventions, and keep secrets in environment variables.

## Security considerations

Enforce authorization on the server for protected data and actions. Do not rely only on client-side UI state or middleware redirects. Verify webhook signatures, validate input, and avoid logging session tokens or secrets.
