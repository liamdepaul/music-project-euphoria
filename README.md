# music-project-euphoria
music project track entitled euphoria
version: 0.1
python: 3.6
entrypoint: python runway_model.py
cuda: 9.2
framework: tensorflow
files:
    ignore:
        - image_dataset/*
build_steps:
    - pip install runway-python==0.1.0
    - pip install -r requirements.txt
