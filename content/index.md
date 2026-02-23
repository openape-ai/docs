---
title: OpenApe Documentation
description: The security layer agents are missing. DNS-based identity and human-in-the-loop permissions for the Agentic Web.
navigation: false
---

::hero
---
announcement:
  title: Built on DDISA
  to: /getting-started
  icon: i-heroicons-arrow-right-20-solid
actions:
  - label: Get Started
    to: /getting-started
    icon: i-heroicons-rocket-launch
  - label: View on GitHub
    to: https://github.com/patrick-hofmann/dns-id
    target: _blank
    icon: i-simple-icons-github
    variant: subtle
---

#title
The security layer [agents are missing.]{.text-primary}

#description
AI agents are getting powerful. They send emails, move money, deploy code. OpenApe makes sure a human approves what matters — without slowing anything down.
::

::card-group
  ::card{title="OpenApe Auth" icon="i-heroicons-key" to="/ecosystem/auth"}
  DNS-based login for humans and agents. Passkeys for humans, Ed25519 for machines. One protocol, any domain.
  ::
  ::card{title="OpenApe Grants" icon="i-heroicons-shield-check" to="/ecosystem/grants"}
  Human-in-the-loop permission system. Agents request, humans approve — once, time-limited, or standing.
  ::
  ::card{title="Ecosystem" icon="i-heroicons-cube" to="/ecosystem"}
  Small, focused packages you compose as needed. Core, Auth, Grants, Nuxt modules, and `apes` CLI.
  ::
  ::card{title="Compliance" icon="i-heroicons-document-check" to="/security/compliance"}
  NIS2 and NIST CSF 2.0 compliant by design. Passkeys-only, phishing-proof, no bolt-on MFA.
  ::
::
