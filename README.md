# Frequency Encoder

A frequency encoder for pandas DataFrames compatible with scikit-learn pipelines.

## Installation

```bash
pip install git+https://github.com/crisbebop/frequency_encoder.git

pip install frequency_encoder
```

## Usage  

```
from frequency_encoder import FrequencyEncoder
import pandas as pd

# Example usage
df = pd.DataFrame({'col1': ['a', 'b', 'a', 'c', 'b']})
encoder = FrequencyEncoder()
df_encoded = encoder.fit_transform(df)
print(df_encoded)

```
## Usage example in a kaggle dataset
https://www.kaggle.com/crisbebop/frequency-encoder-example
