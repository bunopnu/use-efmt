# Use Erlang Code Formatter

Use [efmt](https://github.com/sile/efmt) as a binary inside your GitHub actions 😁

## Usage

An exemplary usage is demonstrated below:

```yaml
- uses: bunopnu/use-efmt@v1.1.0
  with:
    version: "0.14.1" # https://github.com/sile/efmt/releases (without the "v" prefix)

- name: Check Formatting
  run: efmt --check
```
