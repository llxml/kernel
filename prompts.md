# Bootstrap Prompt

Copy and paste this into your LLM CLI to bootstrap a dev environment.

---

Read the LLXML kernel I've provided (seed.txt, self.xml, skills/, spec/).

Follow skills/bootstrap.xml to transform this kernel into a full dev environment:

1. Create dev/llxml/ - the kernel in development mode with META structure
2. Create dev/apps/saddle/ - a starter harness project
3. Initialize git repos, create manifests, set up backstage.xml
4. Read spec/harness.xml and implement the saddle harness in TypeScript

Target directory: {TARGET_DIR}

Execute the bootstrap steps. Create all files and directories.
