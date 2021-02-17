# sample-action (Hello World docker action)
- This is a repository for creating and testing a custom GitHub action.
- This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: aamir7tide/sample-action@v1
with:
  who-to-greet: 'Some name'
