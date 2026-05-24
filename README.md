# Physionet2018_Challenge_Submission

**Public.** The CDAC team's winning entry to the **Physionet 2018 "You
Snooze You Win"** challenge (arousal detection during sleep). Includes
trained models, the model definition, the data-extraction step, and the
inference script.

## Layout

```
ExtractData.py        prepare challenge data
ModelDefinition.py    PyTorch model + Normalizer / functional blocks
ProducePredictions.py inference / submission generation
TrainedModels/        winning checkpoints
LICENSE               noncommercial
```

## Required environment

Python 3 with `pytorch`.

## Status

Paper archive. Public.
