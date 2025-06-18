# Effective Engineering with Cline

A practical presentation on leveraging AI coding assistants for real-world development workflows, presented at JSNation.

## Overview

This presentation addresses common objections to AI coding tools and demonstrates three practical workflows that experienced engineers can use to dramatically improve their productivity with Cline, an autonomous coding agent.

## Key Topics Covered

### 🎯 **Why This Matters**
- Tech leaders are pushing for AI adoption
- Moving beyond "vibe coding" to practical engineering workflows
- How experienced engineers can gain the most from AI tools

### 🔄 **Three Core Workflows**

1. **Test Driven Development**
   - Using Cline to explore codebases and understand testing requirements
   - Creating structured markdown plans with checklists
   - Automated test generation and execution cycles

2. **PR Comment Handling**
   - Leveraging `gh` CLI to gather PR context and feedback
   - Systematic planning and execution of requested changes
   - Efficient handling of code review feedback

3. **Workflow Automation**
   - Identifying repetitive manual tasks
   - Creating reusable workflow files with slash commands
   - Sharing workflows across teams

### 💡 **Power User Insights**
- Always invest in the planning phase
- Leverage MCP servers for enhanced functionality
- Smart context window management strategies
- Best practices for auto-approve settings

## Real-World Examples

The presentation includes examples of tasks accomplished with Cline:
- Building this presentation using Slidev
- Handling merge conflicts
- Creating internal dashboards
- Debugging production issues
- Implementing cost-saving optimizations (saved $500/week on database reads)
- Writing documentation and RFCs
- Code quality improvements

## Getting Started

### Prerequisites
- Node.js and npm installed
- Cline extension for VS Code

### Running the Presentation

```bash
npm install
npm run dev
```

Then visit <http://localhost:3030> to view the slides.

### Files Structure
- `slides.md` - Main presentation content
- `components/` - Vue components for interactive elements
- `*.png` - Screenshots and visual examples
- `package.json` - Dependencies and scripts

## Key Takeaways

1. **Focus on Planning**: Always invest time in the exploration and planning phases
2. **Leverage Tools**: Use GitHub CLI (`gh`) and MCP servers for enhanced workflows
3. **Create Workflows**: Distill common patterns into reusable workflow files
4. **Review Changes**: Keep auto-approve for editing OFF to maintain control
5. **Context Management**: Use appropriate models and smart task handoffs

## Resources

- [Cline Documentation](https://docs.cline.bot/)
- [Cline Workflows Guide](https://docs.cline.bot/features/slash-commands/workflows)
- [Cline Prompt Library](https://github.com/cline/prompts)
- [Slidev Documentation](https://sli.dev/)

## About

This presentation demonstrates practical, production-ready workflows for using AI coding assistants effectively. It moves beyond basic code generation to show how experienced engineers can leverage AI for complex, real-world development tasks.

**Presenter**: [@pashmerepat](https://x.com/pashmerepat)  
**Event**: JSNation Amsterdam 2025
**Theme**: Effective Engineering with Cline
