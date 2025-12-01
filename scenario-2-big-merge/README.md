# Scenario 2: The Big Merge

## The Story

It's Wednesday afternoon, and you receive a notification:

> **@alexchen** has submitted Pull Request #127: "Major documentation update - new features and restructuring"
>
> +847 additions, -312 deletions across 18 files

You click through and see that Alex, an enthusiastic new contributor, has submitted a massive PR that includes:
- 3 brand new tutorials
- Updates to 8 existing documentation files
- Restructured navigation
- New code examples
- Updated API references

Your manager messages you:

> "This looks great, but can you review it? We need to merge by Friday for the release, but we can't afford to introduce errors or inconsistencies. Can you do a thorough review and work with Alex to get this ready?"

**Your mission:** Efficiently review this complex PR, identify issues, provide constructive feedback, and ensure it meets quality standards before merging.

## Scenario Overview

**Duration:** 45-60 minutes
**Difficulty:** Intermediate
**Focus:** AI-assisted PR review and collaborative feedback

## Learning Objectives

By completing this scenario, you will:

1. Learn to efficiently review large pull requests using AI assistance
2. Identify style inconsistencies, technical inaccuracies, and content issues
3. Provide constructive, actionable feedback to contributors
4. Validate cross-references and ensure documentation coherence
5. Balance thoroughness with speed in PR reviews
6. Develop effective PR review workflows

## The Pull Request

The `pr-content/` directory contains all the changes in this PR:

- **3 new files:** Three new tutorial documents
- **8 modified files:** Updates to existing documentation
- **1 deleted file:** An outdated guide being removed
- **Multiple code examples:** Python snippets need validation
- **Cross-references:** Many links between old and new content

## Your Tasks

### Task 2.1: High-Level PR Review (15 minutes)
**File:** [tasks/task-2.1-initial-review.md](tasks/task-2.1-initial-review.md)

Perform an initial high-level review of the PR to understand the scope, changes, and potential issues.

**Key Questions:**
- What is the overall goal of this PR?
- Does it accomplish what it claims to do?
- Are the changes appropriately scoped?
- What areas need detailed review?

### Task 2.2: Detailed Content Review (20 minutes)
**File:** [tasks/task-2.2-detailed-review.md](tasks/task-2.2-detailed-review.md)

Conduct a detailed review focusing on:
- Technical accuracy
- Style consistency
- Formatting issues
- Code example validation
- Completeness of explanations

### Task 2.3: Cross-Reference Validation (10 minutes)
**File:** [tasks/task-2.3-cross-references.md](tasks/task-2.3-cross-references.md)

Ensure all links, references, and navigation changes work correctly:
- Internal links point to correct locations
- Removed files don't have orphaned links
- New content is properly linked from existing docs
- Table of contents and navigation are updated

### Task 2.4: Constructive Feedback (15 minutes)
**File:** [tasks/task-2.4-feedback.md](tasks/task-2.4-feedback.md)

Write a comprehensive PR review with:
- Summary of overall assessment
- Specific issues organized by priority
- Constructive suggestions for improvement
- Positive feedback on what's done well
- Clear next steps for the contributor

## How to Approach This Scenario

### Step 1: Understand the Baseline
Review the `challenge-repo/` to understand the current state before the PR.

### Step 2: Review the Changes
Examine all files in `pr-content/` which represent the proposed changes.

### Step 3: Use AI Strategically
Use AI to:
- Compare before/after versions quickly
- Check consistency across multiple files
- Validate technical accuracy of code examples
- Generate detailed feedback

### Step 4: Think Like a Reviewer
Your goal is to:
- Ensure quality (catch errors)
- Maintain consistency (with existing docs)
- Help the contributor (constructive feedback)
- Move quickly (release deadline)

### Step 5: Write Actionable Feedback
Make your feedback:
- Specific (point to exact lines)
- Actionable (suggest concrete fixes)
- Prioritized (must-fix vs nice-to-have)
- Balanced (positive + constructive)

## Success Criteria

You've successfully completed this scenario when you can:

- ✅ Explain the purpose and scope of the PR
- ✅ Identify at least 10 specific issues across the changes
- ✅ Categorize issues by type and severity
- ✅ Validate that cross-references work correctly
- ✅ Provide clear, actionable feedback to the contributor
- ✅ Recommend whether to approve, request changes, or reject
- ✅ Estimate effort required for fixes

## Tips for Success

1. **Start with the big picture**: Understand what the PR is trying to accomplish before diving into details
2. **Use diff view mentally**: Think "what changed and why"
3. **Leverage AI for patterns**: Use AI to find consistency issues across files
4. **Validate, don't just trust**: Spot-check AI findings for accuracy
5. **Be specific and kind**: Good feedback is detailed and encouraging
6. **Prioritize ruthlessly**: Not everything needs to be fixed pre-merge

## Time Management

- **Task 2.1 (Initial Review)**: 15 minutes - Get the big picture
- **Task 2.2 (Detailed Review)**: 20 minutes - Find specific issues
- **Task 2.3 (Cross-References)**: 10 minutes - Validate links
- **Task 2.4 (Feedback)**: 15 minutes - Write comprehensive review
- **Buffer**: 10 minutes for synthesis and polish

## What's Different from Scenario 1?

In Scenario 1, you audited an entire repository.
In Scenario 2, you're reviewing *changes* - focusing on deltas, not the whole codebase.

This requires:
- Understanding what changed and why
- Considering impact on existing content
- Balancing thoroughness with speed
- Collaborating with a contributor

## What's Next?

After completing this scenario, you'll be ready to:
- Review PRs confidently and efficiently
- Provide valuable feedback that helps contributors improve
- Make informed approve/request changes decisions
- Move on to **Scenario 3: The Backlog Battle** where you'll manage a large issue backlog

## Need Help?

- **Stuck on a task?** Check the hints section in each task file
- **Want to see solutions?** Review the solution guides in `solutions/`
- **Questions about PR review best practices?** See `../../resources/best-practices.md`

---

**Ready to begin?** Start with [Task 2.1: High-Level PR Review](tasks/task-2.1-initial-review.md)
