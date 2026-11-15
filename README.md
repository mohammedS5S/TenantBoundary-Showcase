
# TenantBoundary

### Automated Cross-Tenant Security Testing
**Cybersecurity Project | Node.js | JavaScript | Express**

TenantBoundary is an early-stage cybersecurity prototype that helps test whether multi-tenant web applications properly isolate customer data.

The project focuses on identifying potential cross-tenant authorization issues through automated API security checks.

## The Problem

Many SaaS platforms serve multiple organizations using shared infrastructure.

A security weakness in tenant-level authorization could allow a user from one organization to access another organization's private information.

TenantBoundary explores how automated testing can help identify these risks.

## How It Works

1. **Generate Test Scenarios** — Create cross-tenant access test cases automatically.
2. **Execute API Requests** — Test access boundaries using demo authentication tokens.
3. **Analyze Responses** — Check HTTP status codes and predefined data markers.
4. **Detect Potential Exposure** — Identify suspicious responses and possible data leaks.
5. **Generate Security Findings** — Produce findings with severity labels and supporting evidence.

## Current Features

- Automated cross-tenant test generation
- HTTP API security scanning
- Demo authentication and access control testing
- Predefined data exposure detection
- Security findings with supporting evidence
- Command-line scanning interface
- Automated unit and integration tests

## Testing Results

**28 automated tests passed | 0 failed**

The tests cover authentication, tenant isolation, scanning, findings generation, and intentional vulnerability detection in a controlled demo environment.

## Technology Stack

- JavaScript
- Node.js
- Express.js
- Git & GitHub
- Node.js Built-in Test Runner

## Project Status

**Active Development — Cybersecurity Prototype**

The current implementation uses predefined markers and expected HTTP responses. Findings require validation, and the prototype is not production-ready.

The full source code is maintained in a private repository. This public repository provides a technical overview of the project.
