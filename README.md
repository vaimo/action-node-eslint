# GitHub Action for Node.js ESLint

This action is used to evaluate code quality using **ESLint**.

**Author:** Patryk Waluś (patryk.walus@vaimo.com)

## Supported Versions

- **v1**
    - ESLint action for Node.js projects.

## Usage

```yaml
- name: Run ESLint Code Analysis
  uses: vaimo/action-node-eslint@v1
  with:
    # Enable full analysis of all files (Optional, defaults to true)
    # If false, only modified files will be analyzed.
    full-analysis: ${{ inputs.full-analysis }}
```
