# Bootstrap Prompt

Copy and paste this into your LLM CLI (opencode, Claude, etc.) to bootstrap a new project.

---

Read the LLXML kernel I've provided. You have access to:
- `seed.txt` - the philosophical anchor
- `self.xml` - the format specification
- `skills/` - workflows and processes
- `spec/harness.xml` - context assembler template

I want to bootstrap a new project called `{PROJECT_NAME}`.

Follow the bootstrap.xml skill:
1. Create the project structure (main/, META/, ctx/)
2. Initialize git in main/
3. Create the ll.xml manifest
4. Help me write a META/backstage.xml tailored to my project

My project is: {BRIEF_DESCRIPTION}

Start by creating the directory structure, then we'll work on the backstage together.
