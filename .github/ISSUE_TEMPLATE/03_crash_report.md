---
name: Crash Report
about: Report an application crash or freeze
title: "[CRASH] Application crash or freeze"
labels: crash, bug
assignees: ''
---

## Crash Description

**What were you doing when the crash occurred?**
Describe your actions leading up to the crash.

**Did the application:**
- [ ] Crash completely (closed unexpectedly)
- [ ] Freeze (unresponsive)
- [ ] Partial freeze (slow/laggy)

---

## Crash Details

**Crash Type:**
- [ ] Immediate crash
- [ ] Delayed crash (after X minutes/actions)
- [ ] Random/unpredictable
- [ ] Reproducible (happens every time)

**Error Message (if shown):**
```
Paste any error messages here
```

---

## Steps to Reproduce

**If reproducible, please provide exact steps:**

1. [Step 1]
2. [Step 2]
3. [Step 3]
...
X. Crash occurs

---

## Environment

**OS & Version:**
- [ ] Windows 10
- [ ] Windows 11
- [ ] macOS 10.13+
- [ ] Ubuntu/Linux (specify version)

**Nexus IDE Version:** 1.0.0

**System Resources at Time of Crash:**
- RAM: (e.g., 2GB free, 8GB total)
- Disk: (e.g., 500MB free)
- CPU: (if notably high usage)

---

## Crash Logs

**Error Log from Diagnostics:**

To retrieve crash information:
1. Reopen Nexus IDE
2. Go to Diagnostics → Error Log
3. Copy all recent crash-related entries
4. Paste below:

```
Paste crash log here
```

**System Event Log (Windows only):**
If available, check Windows Event Viewer for application crashes:

```
Paste relevant system events here
```

**Crash Dump (if available):**
Location of crash dump file (if applicable):
```
/path/to/crash/dump
```

---

## Recovery

**Did crash recovery help?**
- [ ] Yes, recovered sessions appeared
- [ ] No, nothing was recovered
- [ ] Didn't prompt for recovery
- [ ] Lost unsaved work

**Was a recovery folder created?**
If yes, provide location:
```
/path/to/recovery/folder
```

---

## Frequency

**How often does this crash occur?**
- [ ] First time
- [ ] Rare (few times a month)
- [ ] Occasional (few times a week)
- [ ] Frequent (daily)
- [ ] Always (100% reproducible)

---

## Activity at Time of Crash

What were you doing?
- [ ] Editing code
- [ ] Using AI features
- [ ] Git operations
- [ ] Searching/navigating
- [ ] Settings changes
- [ ] Opening/closing files
- [ ] Other: _______________

**File type(s) open:**
- [ ] JavaScript/TypeScript
- [ ] Python
- [ ] Java
- [ ] C/C++
- [ ] HTML/CSS
- [ ] Other: _______________

**AI Provider in use:**
- [ ] OpenAI
- [ ] Ollama
- [ ] Gemini
- [ ] None

---

## Recent Changes

**Did anything change recently?**
- [ ] Just updated Nexus IDE
- [ ] Recently installed extensions
- [ ] Recently changed settings
- [ ] Changed AI provider
- [ ] No recent changes

**If updated:** From which version? _____________

---

## Workarounds

**Have you found any workarounds?**
If you've found a way to avoid the crash, describe it:

---

## Attachments

**Files to attach:**
- [ ] Crash dump file
- [ ] Project files (if relevant)
- [ ] Configuration files
- [ ] Screenshots

---

## Checklist

- [ ] I have searched existing crash reports to avoid duplicates
- [ ] I am using the latest version of Nexus IDE
- [ ] I have provided crash logs or diagnostics
- [ ] I have described steps to reproduce (if possible)
- [ ] I have checked the troubleshooting guide
- [ ] I have allowed crash recovery to run if prompted