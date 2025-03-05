# Toric Code for Quantum Error Correction
Simulation of stabilizer measurement in the toric code using [Stim](https://github.com/quantumlib/Stim).

## Requirements
```bash
pip install numpy
pip install stim
```

## TODO
- [ ] Move circuit building functions to class to eliminate global variables and make experiments easier
- [ ] Add error decoding using Pymatching
- [ ] Find code threshold under qubit-level depolarizing noise
- [ ] Add more realistic circuit-level noise