# Prometheus

<p align="center">
    <strong>Legend has it that Prometheus sneakily pinched fire from the gods and handed it over to us humans. Now, in a much less mythical but equally cheeky move, we're swiping the blazing power of PyTorch from the elite halls of data science and handing it to you on a Github Repo.</strong>
</p>




## Project Structure

```plaintext
Prometheus/
│
├── core/                      # Core functionalities
│   ├── models/                # Neural network model definitions
│   │   ├── architectures/     # CNN, RNN, FNN architectures
│   │   └── factory.py         # Factory method to create user-defined models
│   │
│   ├── preprocessors/         # Data preprocessing operations
│   │   ├── normalizers.py
│   │   ├── encoders.py
│   │   ├── feature_engineering.py
│   │   └── data_insights.py  # Covariance, correlation tests
│   │
│   └── classroom/             # Training logic and configuration
│       ├── classroom.py
│       └── optimizers.py     # Definitions or wrappers for various optimizers
│
├── services/                  # High-level services 
│   ├── data_manager.py       # Handling data storage, retrieval, modifications
│   ├── model_manager.py      # Operations like saving, loading, converting models
│   └── validator.py          # Input validation and error handling
│
├── visualizers/              # Visualization of models, data, and training processes
│   └── visualizer.py
│
├── utils/                    # Utility functions and classes
│   └── error_messages.py     # Pre-defined error messages, codes, etc.
│
├── tests/                    # Unit tests and testing utilities
│
├── data/                     # Raw and processed data storage
│   ├── raw/
│   └── processed/
│
├── config/                   # Configuration files
│   └── default_config.py
│
└── main.py                   # Main entry point
