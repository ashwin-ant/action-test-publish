# Action Test Publish

This repository contains two GitHub Actions for testing:

## 1. Echo Action

A simple action that echoes a message.

**Location**: `echo-action/`

**Usage**:
```yaml
uses: your-username/action-test-publish/echo-action@main
with:
  message: "Your message here"  # Optional, defaults to "Hello from GitHub Action!"
```

## 2. File Processor Action

An action that processes files with basic operations.

**Location**: `file-processor-action/`

**Usage**:
```yaml
uses: your-username/action-test-publish/file-processor-action@main
with:
  file_path: "path/to/file"  # Optional, defaults to "README.md"
  operation: "count"         # Optional: "count" or "print", defaults to "count"
```

Each action is located in its own directory and can be referenced independently in GitHub workflows.