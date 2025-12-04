# GitHub Copilot for Repository Management Quest

## Quest Overview

Welcome to the **GitHub Copilot for Repository Management Quest** - an interactive learning experience designed for content developers who want to master GitHub Copilot's native features for repository management workflows. This quest simulates real-world scenarios using **real Microsoft Learn documentation**, covering common challenges like taking over unfamiliar repositories, triaging issue backlogs, and managing complex pull requests.

**What makes this quest unique:** You'll work with actual Microsoft Learn modules while mastering GitHub Copilot's workspace agent, issue analysis, PR summarization, and automated code generation features.

## 🎯 Two-Part Lab Structure

This quest is designed as **two 60-minute labs** that can be completed independently or as a full learning experience:

| Lab | Duration | Focus | Scenarios |
|-----|----------|-------|-----------|
| **[Part 1: Fundamentals](part-1-fundamentals/README.md)** | 60 min | Core Copilot skills | Workspace setup + Scenarios 1-2 |
| **[Part 2: Advanced](part-2-advanced/README.md)** | 60 min | Advanced automation | Custom agents + Scenarios 3-4 |

**Start here:** Choose the lab that matches your experience level and time available!

## Learning Objectives

By completing this quest, you will:

1. **Master GitHub Copilot workspace exploration** - Use Copilot's @workspace agent to quickly understand unfamiliar repositories and Microsoft Learn documentation structures
2. **Implement efficient issue management** - Use Copilot to analyze issues, categorize, prioritize, and suggest fixes
3. **Develop advanced PR review skills** - Leverage GitHub Copilot's PR summaries, review suggestions, and inline chat for efficient pull request reviews
4. **Create documentation standards** - Establish quality standards with Copilot-assisted reviews and automated checks
5. **Build practical workflows** - Develop repeatable processes using GitHub Copilot's native capabilities

## Quest Structure

This quest uses **real Microsoft Learn modules** from the `learn-pr/wwl/` folder and contains a foundational module plus four progressive scenarios:

### Module 0: Workspace Preparation
**Duration:** 15-20 minutes | **Covered in:** Part 1 (intro) + Part 2 (advanced)

Customize your GitHub Copilot workspace with agents and reusable prompts using examples from Microsoft Learn documentation.

- **Part 1 covers:** Task 0.1 - Introduction to agents and prompts
- **Part 2 covers:** Tasks 0.2-0.4 - Creating custom agents and prompt libraries

### Scenario 1: The Inheritance
**Duration:** 25-30 minutes | **Covered in:** Part 1

Take over an unfamiliar Microsoft Fabric documentation repository. Use Copilot to explore the module structure, identify issues, and create an improvement plan.

**Content:** Microsoft Fabric modules including lakehouses, medallion architecture, and semantic models

### Scenario 2: The Backlog Battle
**Duration:** 20-25 minutes | **Covered in:** Part 1

Triage 12 open issues in a Microsoft Learn repository. Categorize, prioritize, identify duplicates, and create fix proposals.

**Content:** Workflow-created issues covering broken images, outdated dates, accessibility, and more

### Scenario 3: The Big Merge
**Duration:** 25-30 minutes | **Covered in:** Part 2

Review a pull request adding new Copilot for Fabric documentation. Identify content issues, validate cross-references, and provide constructive feedback.

**Content:** Workflow-created PR with intentional issues to discover

### Scenario 4: The Agent Arsenal
**Duration:** 20-25 minutes | **Covered in:** Part 2

Build a comprehensive agent ecosystem with specialized documentation agents that work together for enterprise-scale workflows.

**Content:** Advanced agent patterns and workflow orchestration

## Prerequisites

- **Git fundamentals**: Basic understanding of repositories, commits, branches, and pull requests
- **Markdown knowledge**: Familiarity with markdown syntax and documentation
- **GitHub Copilot**: Active GitHub Copilot subscription (individual, business, or enterprise)
- **Tools**: VS Code with GitHub Copilot extension, Git client, GitHub account

**Optional but helpful:**
- Experience with documentation systems (MkDocs, Jekyll, Docusaurus)
- Basic Python knowledge for understanding utility scripts
- Prior experience with code review processes

## Getting Started

### Setup Requirements

1. **Install VS Code** - Download from https://code.visualstudio.com/
2. **Install GitHub Copilot extension** - From VS Code marketplace
3. **Activate GitHub Copilot** - Sign in with your GitHub account
4. **GitHub account** - Required for forking and running workflows

### Repository Setup

1. **Fork this repository** to your own GitHub account:
   - Click the "Fork" button at the top-right of this repository
   - Choose your account as the destination for the fork

2. **Clone your fork** (replace `[your-username]` with your GitHub username):
   ```bash
   git clone https://github.com/[your-username]/github-repo-management-quest.git
   cd github-repo-management-quest
   code .
   ```

3. **Create sample content** by running the setup workflows:

   **Option A: Using GitHub Web Interface (Recommended)**
   - Go to your forked repository on GitHub
   - Navigate to the **Actions** tab
   - You'll see two workflows: "Setup Quest Issues" and "Setup Quest PR"
   
   **To create sample issues for Scenario 3:**
   - Click on "Setup Quest Issues" workflow
   - Click "Run workflow" button
   - Select "scenario-3" from the dropdown
   - Click the green "Run workflow" button
   - Wait for the workflow to complete (creates 8 sample issues)

   **To create sample PR for Scenario 2:**
   - Click on "Setup Quest PR" workflow  
   - Click "Run workflow" button
   - Select your preferred PR size (small/medium/large)
   - Click the green "Run workflow" button
   - Wait for the workflow to complete (creates 1 sample pull request)

   **Option B: Using GitHub CLI (if you have it installed)**
   ```bash
   # Create sample issues
   gh workflow run setup-quest-issues.yml --field scenario=scenario-3

   # Create sample PR
   gh workflow run setup-quest-pr.yml --field pr_size=medium
   ```

4. **Verify setup**:
   - Check the **Issues** tab - you should see 8 sample issues labeled "quest-sample"
   - Check the **Pull requests** tab - you should see 1 sample PR labeled "quest-sample"

## Time Commitment

- **Part 1 (Fundamentals)**: ~60 minutes
- **Part 2 (Advanced)**: ~60 minutes
- **Complete quest**: ~2 hours total
- **Self-paced**: Complete parts independently on your own schedule
- **Requires**: Active VS Code session with GitHub Copilot

## Next Steps

Ready to begin? Choose your starting point:

- 🚀 **[Part 1: Fundamentals](part-1-fundamentals/README.md)** - Start here if you're new to GitHub Copilot or want to learn the core skills
- ⚡ **[Part 2: Advanced](part-2-advanced/README.md)** - Jump here if you're comfortable with Copilot basics and want advanced automation

Or dive into individual scenarios:
- [Scenario 1: The Inheritance](scenario-1-inheritance/README.md)
- [Scenario 2: The Backlog Battle](scenario-2-backlog-battle/README.md)
- [Scenario 3: The Big Merge](scenario-3-big-merge/README.md)
- [Scenario 4: The Agent Arsenal](scenario-4-agent-arsenal/README.md)

---

**Quest Version:** 2.0
**Last Updated:** 2025-12-04
**Content:** Microsoft Learn
**Estimated Completion Time:** 2 hours (1 hour per part)
**Difficulty Level:** Beginner to Advanced
