# MAPE-validators

MAPE-validators is a collection of validators for JSON representations
of models used in self-adaptive systems. Each model comes with a
`description.md` file that provides documentation on the model.

The validators use the
[voluptuous](https://github.com/alecthomas/voluptuous) library.

## Dependencies

Dependencies are listed in `requirements.txt`. You will probably want
to install them with `pip`.

## Usage

Import the desired models in your MAPE-K components (analysis,
knowledge base, etc.), and make sure to validate all models you
receive as JSON objects.
