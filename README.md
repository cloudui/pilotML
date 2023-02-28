# Pilot ML Projects
In the process of becoming more familiar with implementation of Deep Learning and Machine Learning projects. Things I'm trying:
- TensorFlow
- Keras
- PyTorch
- Scikit-Learn

## Exporting Conda Environment 
```bash
# Preferred
conda env export | grep -v "^prefix: " > environment.yml
# Alternative
conda list -e > req.txt
```

## Setting up Conda Environment
Preferred method: 
```bash
conda env create -f environment.yml
# Set custom path if you want
conda env create -f environment.yml -p $(path)
```

Alternative:
```bash
conda create -n <environment-name> --file requirements.txt
```


