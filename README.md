# Lambda-Example

This project contains an AWS Lambda function implemented in `main.py`.

## Overview

The Lambda function is designed to receive text and return a version of the same text but with lower case and spaces substituted by '_'.  

## File Structure

- `main.py`: Contains the Lambda handler and core logic.

## Example Event

```json
{
  "input": "LOREM IPSUM"
}
```

```json
{
  "ouput": "lorem_ipsum"
}
```

## License

MIT License
