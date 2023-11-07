# Print Action Payload

This simple action prints its webhook event payload (context about the repo and workflow that have called it) and sets it as the output `payload`.

## Inputs

**No inputs are required.**

## Outputs

### `payload`

The webhook event payload or (if an error occured) the error message

## Example usage

```yaml
uses: dloetzke/print-action-payload@v1
```