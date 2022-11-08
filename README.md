# action-sleep
GitHub Action to Sleep that works on a multi-platform runners

Thanks to https://github.com/jakejarvis/wait-action for inspiring this action

```yaml
inputs:
  seconds:
    description: 'The number of seconds to sleep'
    required: true
```

## Usage:

```yaml
steps:
- uses: peternied/action-sleep@v1
  with:
    seconds: 30
```