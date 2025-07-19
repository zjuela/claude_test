# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a Claude Code playground repository designed for learning and experimenting with Claude Code capabilities. The primary goal is to help users master Claude Code through hands-on practice and exploration.

## Key Claude Code Features to Explore

### 1. Multi-Tool Usage
- Claude Code can call multiple tools in parallel for better performance
- Example: Running `git status`, `git diff`, and `npm test` simultaneously

### 2. Task Management
- Use TodoWrite tool for complex multi-step tasks
- Helps track progress and maintain organization
- Particularly useful for tasks with 3+ steps

### 3. Search and Navigation
- **Grep**: Fast pattern search across files
- **Glob**: Find files by name patterns
- **Task**: For complex searches requiring multiple rounds
- **Agent**: Best for open-ended searches like "which file does X?"

### 4. File Operations
- **Read**: View file contents (supports images)
- **Edit/MultiEdit**: Make precise changes to existing files
- **Write**: Create new files (prefer editing existing files)
- **NotebookRead/NotebookEdit**: For Jupyter notebooks

## Common Learning Exercises

1. **Basic File Operations**
   ```bash
   # Create a simple project structure
   mkdir -p src/components src/utils tests
   ```

2. **Code Analysis**
   - Ask Claude Code to analyze code patterns
   - Request refactoring suggestions
   - Explore different programming paradigms

3. **Project Setup**
   - Initialize various project types (Node.js, Python, etc.)
   - Set up testing frameworks
   - Configure linting and formatting

4. **Git Workflow**
   - Practice creating meaningful commits
   - Explore pull request creation with `gh pr create`
   - Learn about commit message best practices

## Best Practices for Claude Code Mastery

### Effective Communication
- Be specific and concise in requests
- Use "what" instead of "how" when possible
- Provide context when needed

### Tool Selection
- Use Task tool for complex searches
- Batch operations when possible
- Let Claude Code choose appropriate tools

### Common Patterns
```bash
# When exploring a new codebase
# 1. Use Glob to find relevant files
# 2. Use Grep to search for patterns
# 3. Use Read to examine specific files

# For debugging
# 1. Read error messages carefully
# 2. Check file paths are absolute
# 3. Verify dependencies are installed
```

## Useful Commands to Try

```bash
# System information
uname -a
pwd
ls -la

# Project initialization examples
npm init -y                    # Node.js
python -m venv venv           # Python
cargo init                    # Rust
go mod init example           # Go

# Common development commands
npm install
npm test
npm run lint
python -m pytest
cargo build
go test ./...
```

## Tips for Learning

1. **Start Simple**: Begin with basic file operations before complex projects
2. **Experiment Freely**: This is a playground - try different approaches
3. **Observe Patterns**: Notice how Claude Code approaches different tasks
4. **Ask Questions**: Request explanations for Claude Code's decisions
5. **Practice Workflows**: Try common development workflows repeatedly

## Advanced Features to Explore

- **Extended Thinking**: For complex problem-solving
- **Memory Management**: Understanding CLAUDE.md usage
- **MCP (Model Context Protocol)**: For external tool integration
- **Hooks**: Custom commands that execute on events
- **Slash Commands**: Custom prompts like `/compact`

## Notes for Claude Instances

When working in this playground:
- Encourage experimentation and learning
- Explain your reasoning when asked
- Suggest learning exercises based on user interests
- Be patient with beginners
- Demonstrate best practices through examples
- Use the TodoWrite tool to show task planning
- Highlight efficient tool usage patterns