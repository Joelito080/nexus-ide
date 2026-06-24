---
name: Git Integration Issue
about: Report problems with Git workflows and version control
title: "[GIT] Git integration issue"
labels: git, bug
assignees: ''
---

## Git Issue Description

**What is the problem?**
Describe the issue you're experiencing with Git integration.

**Expected Behavior:**
What should happen during this Git operation?

**Actual Behavior:**
What actually happens instead?

---

## Git Operation

**Which Git operation are you having trouble with?**
- [ ] Clone/Open repository
- [ ] Stage/Unstage changes
- [ ] Commit
- [ ] Push
- [ ] Pull
- [ ] Fetch
- [ ] Branch operations (create, switch, delete)
- [ ] Merge
- [ ] Merge conflicts
- [ ] Rebase
- [ ] View history
- [ ] Other: _______________

---

## Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Step 3]
...
X. Issue occurs

---

## Error Messages & Logs

**Error Message Displayed:**
```
Paste error message here
```

**Git Error Output:**
Go to Diagnostics → Error Log and paste Git-related entries:
```
Paste Git error logs here
```

**Full Error Details:**
```
Paste complete error output here
```

---

## Repository Information

**Repository Type:**
- [ ] Local repository only
- [ ] Connected to remote (GitHub, GitLab, Bitbucket, etc.)
- [ ] Remote: _______________

**Repository Size:**
- Number of commits: approximately _______
- Number of files: approximately _______
- Total size: approximately _______ MB

**Repository Status:**
- [ ] Clean working directory
- [ ] Uncommitted changes present
- [ ] Merge in progress
- [ ] Rebase in progress
- [ ] Conflict state

---

## Git Configuration

**Git Information:**
- Git version: (run `git --version`)
  ```
  Paste output here
  ```

**Git Config (local):**
(Run `git config --local --list` in your repo)
```
Paste git config here (exclude sensitive info)
```

**Git Config (global):**
(Run `git config --global --list`)
```
Paste git config here (exclude sensitive info)
```

---

## Authentication

**How are you authenticating with Git?**
- [ ] HTTPS with personal access token
- [ ] HTTPS with username/password
- [ ] SSH key
- [ ] OAuth/Other: _______________

**Authentication Issues?**
- [ ] Credentials appear to be correct
- [ ] Getting authentication errors
- [ ] Need to re-enter credentials
- [ ] Credentials not being saved

**For SSH:**
- [ ] SSH key properly added to ssh-agent
- [ ] Correct key permissions (400 or 600)
- [ ] Can connect manually: `ssh -T git@github.com`

---

## Testing

**What have you already tried?**
- [ ] Restarted Nexus IDE
- [ ] Refreshed Git panel
- [ ] Verified Git is installed
- [ ] Tested Git from command line
- [ ] Tried different repository
- [ ] Restarted computer
- [ ] Checked Git credentials
- [ ] Updated Git to latest version

**Results of your testing:**
```
Describe what you tried and the results
```

---

## Command Line Verification

**Does the same operation work in Git CLI?**
- [ ] Yes (works in CLI, fails in Nexus IDE)
- [ ] No (fails both in CLI and Nexus IDE)
- [ ] Haven't tested

**CLI Command and Output:**
(Run the git command from terminal and paste output)
```
$ git [your command here]
[output here]
```

---

## Environment

**Nexus IDE Version:** 1.0.0

**OS & Version:**
- [ ] Windows 10
- [ ] Windows 11
- [ ] macOS 10.13+
- [ ] Ubuntu/Linux (specify: _______)

**System Resources:**
- RAM available: _____ GB
- Disk space: _____ GB free

---

## Network & Connectivity

**Network Status:**
- [ ] Connected to internet
- [ ] Behind firewall/proxy: Yes / No (specify if yes)
- [ ] VPN in use: Yes / No

**Remote Connectivity:**
(Try to ping your Git remote)
- [ ] Can reach remote server
- [ ] Cannot reach remote server
- [ ] Getting timeout errors

---

## Recent Changes

**What changed recently?**
- [ ] Updated Nexus IDE
- [ ] Updated Git
- [ ] Changed network/internet setup
- [ ] Switched computers/OS
- [ ] Updated OS
- [ ] Changed Git credentials
- [ ] Nothing that I know of

**If updated:** From which version? _______________

---

## File/Path Information

**File Types in Repository:**
- [ ] Large binary files (>100MB)
- [ ] Many nested directories
- [ ] Special characters in filenames
- [ ] Symbolic links
- [ ] Submodules

**Working Directory Path:**
```
/path/to/repository
```

**Repository Structure:**
(Briefly describe folder layout if relevant)

---

## Workarounds

**Have you found any workarounds?**
(For example: using Git CLI, different approach, temporary solution, etc.)

---

## Screenshots

**If applicable, add screenshots:**
- Screenshot of error message
- Screenshot of Git panel
- Screenshot of Nexus IDE with error state

---

## Checklist

- [ ] I have verified the same operation works (or doesn't) in Git CLI
- [ ] I have checked my Git configuration and credentials
- [ ] I have provided relevant error messages and logs
- [ ] I am using the latest version of Nexus IDE
- [ ] I have searched existing Git-related issues
- [ ] I have verified internet connectivity
- [ ] I have NOT included sensitive info (passwords, keys, tokens)