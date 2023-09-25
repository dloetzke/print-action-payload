# Print Action Payload

This simple action prints its webhook event payload (context about the repo and workflow that has called it) and sets it as the output `payload`.

## Inputs

**No inputs are required.**

## Outputs

### `payload`

The webhook event payload

## Example usage

```yaml
uses: dloetzke/print-action-payload@v1
```