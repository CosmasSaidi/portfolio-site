# Cross-Site Scripting (XSS) Fundamentals (Concept Notes)

## Scope
This note summarizes XSS as a client-side risk caused by unsafe handling of untrusted input in browser-rendered contexts.

## Core Concept
XSS happens when untrusted input is rendered as executable browser content instead of plain text.

## High-Level Types
- Reflected: input appears immediately in response output
- Stored: unsafe input is persisted and later rendered
- DOM-based: client-side scripts process untrusted data unsafely

## Security Impact
- Session security risk
- User trust and interface integrity risk
- Exposure of client-side data contexts

## Defensive Controls
- Context-aware output encoding
- Strong input validation strategy
- Safe DOM APIs over unsafe HTML insertion
- Content Security Policy as defense-in-depth

## Practical Learning Outcome
- Recognize common rendering-risk patterns
- Describe XSS impact in defensive terms
- Recommend practical hardening controls

*Concept-focused documentation only. No direct payloads or platform solutions included.*
