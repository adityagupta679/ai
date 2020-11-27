# ai

Setting up python environment for development behind a firewall in an enterprise.

Setup files are downloaded beforehand in an internet based system  by listing required packages in a requirements.txt file and doing a simple pip download like this: 

```python
pip download -r requirements.txt
```
This downloads python packages in the directory this command is run. This directory can be now zipped and moved to the enterprise server. Follow steps in setup file to setup python running in server.
