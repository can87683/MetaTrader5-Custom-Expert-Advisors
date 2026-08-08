# MetaTrader5-Custom-Expert-Advisors
MetaTrader5 Custom Expert Advisors

# BSD-C-3 License

# ai_trader.mq5
An EA using an ONNX model in files folder for generating signals directly without any other indicators.

An ONNX model is needed by exporting from a self-trained TFT model on MT5 data or a foundation time series model like Amazon-Chronos-2 or Google TimesFM. 

# Autoset_SL_TP EA
Two EAs for ND100 and SP500 are provided to auto SL/TP

They can be modified easily for other symbols or incorporated into other trading EAs

Tuue/optimize with a demo account until it works as expected in your charts

# Use
This script can be run in a Python venv with required dependencies

Do "python mt5_connector.py will show required wheels in terminal

For instalnce, just do "pip install setproctitle" if crashes on "no module named setproctitle"

Each venv of python verions may have different requirements.

So just install the misisng wheels one-by-one
