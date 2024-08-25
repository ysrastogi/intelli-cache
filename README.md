# IntelliCache


## Overview

IntelliCache is a Django-based web application designed to simplify the process of downloading, managing, and running inference on Hugging Face transformer models locally. This tool provides an intuitive interface for data scientists and machine learning engineers to work with state-of-the-art NLP models efficiently.

## Features

- **Model Download**: Easily download Hugging Face models to your local machine.
- **Version Management**: Keep track of different versions of your models.
- **Inference API**: Run inference on your models through a simple REST API.
- **Caching System**: Efficiently cache frequently used models for faster access.

## Requirements

- Python 3.8+
- Django 3.2+
- Django Rest Framework
- Hugging Face Transformers library
- PyTorch or TensorFlow (depending on the models you use)



## Configuration

You can configure the application by modifying the `settings.py` file. Key settings include:

- `MODELS_DIR`: Directory where downloaded models are stored.
- `MAX_CACHED_MODELS`: Maximum number of models to keep in memory cache.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Hugging Face](https://huggingface.co/) for their amazing transformer models and libraries.
- [Django](https://www.djangoproject.com/) for the robust web framework.
- [Django Rest Framework](https://www.django-rest-framework.org/) for the powerful tools to build Web APIs.
