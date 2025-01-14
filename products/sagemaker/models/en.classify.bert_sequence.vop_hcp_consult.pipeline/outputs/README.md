# Output Format

The output consists of a JSON object with the following structure:

```json
{
    "predictions": [
        {
            "prediction": "label",
            "confidence": Score
        },
        {
            "prediction": "label",
            "confidence": Score
        },
        ...
    ]
}
```

### Explanation of Fields

- **predictions**: An array containing predictions corresponding to the input documents provided.

    - **prediction**: The predicted label for the input document.

    - **confidence**: The confidence score associated with the prediction, indicating the model's certainty in its prediction.

