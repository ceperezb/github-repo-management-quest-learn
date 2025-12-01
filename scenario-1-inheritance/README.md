# Scenario 1: The Inheritance

## The Story

It's Monday morning, and you've just received an urgent message from your manager:

> "Hey! Sarah left the company unexpectedly last Friday, and we need you to take over the TechFlow documentation repository. It's critical for our product launch next month. The repository has been maintained by different people over the years, and honestly, we're not sure what state it's in. Can you do a quick assessment and let us know what we're working with? Thanks!"

You navigate to the repository and see a mix of markdown files, some Python scripts, various guides, and tutorials. There's no clear organization, commit messages are inconsistent, and you have no idea what's outdated or current.

**Your mission:** Understand what you've inherited, identify critical issues, and create an actionable plan to bring this repository up to standard.

## Scenario Overview

**Duration:** 30-45 minutes
**Difficulty:** Beginner to Intermediate
**Focus:** AI-assisted repository exploration and content auditing

## Learning Objectives

By completing this scenario, you will:

1. Learn to efficiently explore unfamiliar repositories using AI assistance
2. Identify documentation quality issues (broken links, outdated content, inconsistencies)
3. Create comprehensive content audit reports
4. Establish documentation standards and guidelines
5. Develop a systematic approach to repository takeover

## The Challenge Repository

The `challenge-repo/` directory contains a realistic documentation repository with:

- **15+ markdown files** covering various topics
- **Documentation scattered** across multiple directories
- **Python utilities** for link checking and content validation
- **Inconsistent formatting** and style
- **Some broken links** and outdated references
- **Missing or incomplete** documentation in places
- **No clear contribution guidelines** or standards

## Your Tasks

### Task 1.1: Repository Exploration and Mapping (15 minutes)
**File:** [tasks/task-1.1-explore.md](tasks/task-1.1-explore.md)

Use AI to quickly understand the repository structure, content organization, and purpose of different files. Create a visual map or outline of what exists.

**Key Questions to Answer:**
- What types of documentation exist?
- How is the content organized?
- What are the main topics covered?
- Are there any Python utilities? What do they do?
- What's the overall documentation philosophy?

### Task 1.2: Content Quality Audit (15 minutes)
**File:** [tasks/task-1.2-audit.md](tasks/task-1.2-audit.md)

Identify specific quality issues including broken links, outdated content, formatting inconsistencies, and technical accuracy problems.

**What to Look For:**
- Broken internal and external links
- Outdated version numbers or deprecated features
- Inconsistent heading styles
- Missing images or assets
- Incomplete sections or TODO markers
- Contradictory information across files

### Task 1.3: Generate Audit Report (10 minutes)
**File:** [tasks/task-1.3-report.md](tasks/task-1.3-report.md)

Create a comprehensive audit report summarizing your findings, prioritizing issues, and recommending next steps.

**Report Should Include:**
- Executive summary
- Issues categorized by severity (critical, high, medium, low)
- Quantitative metrics (broken links count, files needing updates, etc.)
- Prioritized action plan
- Estimated effort for fixes

### Task 1.4: Documentation Standards Document (15 minutes)
**File:** [tasks/task-1.4-standards.md](tasks/task-1.4-standards.md)

Create or update a documentation standards file to prevent future quality issues and ensure consistency.

**Standards Should Cover:**
- Markdown formatting conventions
- File naming and organization
- Link checking requirements
- Review and approval process
- Style guide references
- Accessibility requirements

## How to Approach This Scenario

### Step 1: Set Up Your Environment
```bash
cd scenario-1-inheritance/challenge-repo
# Familiarize yourself with the repository structure
ls -R
# Or use your file explorer
```

### Step 2: Use AI Strategically
Don't try to manually read every file. Instead, use AI to:
- Summarize large files quickly
- Identify patterns across multiple files
- Find specific issues (broken links, inconsistencies)
- Generate reports from your findings

### Step 3: Work Through Tasks Sequentially
Each task builds on the previous one. Follow the instructions in the task files.

### Step 4: Document Your Process
Keep notes on:
- What prompts worked well with your AI assistant
- What patterns you discovered
- What would you do differently next time

### Step 5: Check Solutions
When you're done, review the solution guides to see alternative approaches and best practices.

## Success Criteria

You've successfully completed this scenario when you can:

- ✅ Explain the repository structure and content organization
- ✅ Identify at least 10 specific quality issues
- ✅ Categorize issues by type and severity
- ✅ Create a professional audit report
- ✅ Draft comprehensive documentation standards
- ✅ Estimate effort required for remediation
- ✅ Articulate a clear plan for repository improvement

## Tips for Success

1. **Think like an auditor**: Be systematic and thorough
2. **Use AI for speed**: Let AI handle repetitive analysis tasks
3. **Validate AI findings**: Spot-check AI recommendations for accuracy
4. **Prioritize ruthlessly**: Focus on high-impact issues first
5. **Be specific**: Vague findings aren't actionable
6. **Consider the audience**: Who will use this documentation?

## Time Management

- **Task 1.1 (Explore)**: 15 minutes - Don't get lost in details
- **Task 1.2 (Audit)**: 15 minutes - Focus on finding issues
- **Task 1.3 (Report)**: 10 minutes - Be concise and actionable
- **Task 1.4 (Standards)**: 15 minutes - Create reusable templates
- **Buffer**: 10 minutes for review and reflection

## What's Next?

After completing this scenario, you'll be ready to:
- Apply these exploration techniques to any unfamiliar repository
- Conduct professional content audits
- Establish quality standards for documentation teams
- Move on to **Scenario 2: The Big Merge** where you'll review a complex PR

## Need Help?

- **Stuck on a task?** Check the hints section in each task file
- **Want to see solutions?** Review the solution guides in `solutions/`
- **Questions about AI prompts?** See `../../resources/ai-prompts.md`

---

**Ready to begin?** Start with [Task 1.1: Repository Exploration](tasks/task-1.1-explore.md)
