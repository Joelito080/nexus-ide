---
name: AI Provider Issue
about: Report problems with AI integrations (OpenAI, Ollama, Gemini)
title: "[AI] Issue with [Provider Name]"
labels: ai, bug
assignees: ''
---

## AI Provider Issue

**Which AI provider are you experiencing issues with?**
- [ ] OpenAI (OpenCode)
- [ ] Ollama (Local Models)
- [ ] Google Gemini
- [ ] Multiple providers

---

## Issue Description

**What is the problem?**
Describe the issue you're experiencing with the AI provider.

**Expected Behavior:**
What should happen when using this AI provider?

**Actual Behavior:**
What actually happens instead?

---

## Provider Configuration

**OpenAI (if applicable):**
- [ ] API key is valid and has credits
- [ ] Model selected: _______________
- [ ] Org ID: (leave blank if using personal account)

**Ollama (if applicable):**
- [ ] Ollama is running (`ollama serve`)
- [ ] Model downloaded: _______________
- [ ] Server URL: localhost:11434 (or custom: _________)

**Gemini (if applicable):**
- [ ] API key is valid and active
- [ ] Model selected: _______________

---

## Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Step 3]
...
X. Issue occurs

---

## Error Messages

**Error Message Displayed:**
```
Paste error message here
```

**Console/Diagnostic Logs:**
Go to Diagnostics → Error Log and paste relevant entries:
```
Paste logs here
```

**Full Error Stack Trace (if available):**
```
Paste stack trace here
```

---

## Network & Connectivity

**Network Status:**
- [ ] Connected to internet
- [ ] Firewall/proxy in use: Yes / No (specify if yes)
- [ ] VPN/Corporate network: Yes / No

**For Ollama:**
- [ ] Can ping Ollama server from command line
- [ ] Ollama output:
  ```
  Paste ollama serve output here
  ```

**API Connectivity:**
- [ ] Can reach provider's website/API
- [ ] API status page shows no outages: Yes / No (link: ________)

---

## Testing

**What have you already tried?**
- [ ] Restarted Nexus IDE
- [ ] Checked API credentials
- [ ] Tested connection (Settings → AI Providers → Test)
- [ ] Restarted computer
- [ ] Disabled other extensions (if applicable)
- [ ] Checked internet connection
- [ ] Tried different AI model (for that provider)

**Results of your testing:**
```
Describe what you tried and the results
```

---

## Environment

**Nexus IDE Version:** 1.0.0

**OS & Version:**
- [ ] Windows 10
- [ ] Windows 11
- [ ] macOS 10.13+
- [ ] Ubuntu/Linux (specify version)

**System Resources:**
- RAM: _____ GB (available: _____ GB)
- Disk: _____ GB free
- Internet Speed: _____ Mbps

---

## Provider Status

**Have you checked provider status?**
- [ ] OpenAI Status: https://status.openai.com
- [ ] Ollama: Running locally
- [ ] Google Status: https://www.google.com/appsstatus

**Is the provider experiencing issues?**
- [ ] Yes (provide link/details)
- [ ] No
- [ ] Unknown

---

## Account Information (Don't Share Keys!)

**OpenAI (if applicable):**
- Account type: Free / Pro / Enterprise
- Subscription status: Active / Expired / Trial
- Have used this account before in Nexus IDE? Yes / No

**Ollama (if applicable):**
- Ollama version: _______________
- Models installed: _______________

**Gemini (if applicable):**
- Account type: Free / Paid
- Quota status: _______________

---

## Recent Changes

**What changed recently?**
- [ ] Updated Nexus IDE version
- [ ] Updated provider's app/library
- [ ] Changed network/internet setup
- [ ] Changed API key/credentials
- [ ] Switched computers/OS
- [ ] Nothing that I know of

**If updated:** From which version? _______________

---

## Workarounds

**Have you found any workarounds?**
(For example: switching to different model, restarting server, etc.)

---

## Screenshots

**If applicable, add screenshots:**
- Screenshot of error message
- Screenshot of settings panel
- Screenshot of diagnostics output

---

## Checklist

- [ ] I have checked the provider's status and documentation
- [ ] I have verified API credentials are correct
- [ ] I have provided all relevant error messages and logs
- [ ] I am using the latest version of Nexus IDE
- [ ] I have searched existing AI-related issues
- [ ] I have NOT included actual API keys (use [REDACTED])