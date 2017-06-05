# coreml-scikit-example

Apple CoreML example with scikit-learn.

This is a simple example on how to export a Scikit-Learn model (logistic regression in this case) to the CoreML file, load it back and make predictions on it

## Usage

It seeems that the [coreml package](https://pypi.python.org/pypi/coremltools) only supports Python 2.7 for now

I recommend using a virtual env before installing pip requirements

```shell
pip install -r requirements.txt
python main.py
```

## Disclaimer

The code should be a working example but it's not fully tested as prediction on CoreML models can only be done on macOS 10.13

The code should raise the following exception `Exception: Model prediction is only supported on macOS version 10.13`
