# Push to Codepost.io Action

This action copies the submission of a student to codepost and auto triggers any associated tests.

## Inputs

### `codepost-api-token`

An API token created on codepost.

### `course-id`

The id of the course we are pushing to.

## Example Usage

```
uses: actions/codepost-bju-push
with:
  codepost-api-token: ${{ secrets.CODEPOST }}
  assignment-id: 1
```