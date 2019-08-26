# mppt_td3
An implementation of Twin delayed DDPG (https://spinningup.openai.com/en/latest/algorithms/td3.html) for maximum power point traking of a photovoltaic cell.


## Requirements: 

- tensorflow
- numpy
- python 3.5
- Gym Open AI
- Gym environment 'mppt-v0', 'mppt-v1' 

### Source: mppt-v0
Clone the mmppt-v0 gym environment from https://github.com/loavila/mppt-gym and install following the instructions.

It is recommendable installing in a python virtual environment (https://rukbottoland.com/blog/tutorial-de-python-virtualenv/)

## How to run:
In a console run:

``` 
python main.py

```

### Testing:

``` 
python simul_test_ddpg2.py



