# musical_instruments_recognition

Códigos referentes ao trabalho de conclusão de curso apresentado como requisito parcial para obtenção do título de Engenheiro Eletricista à Faculdade de Engenharia da Universidade do Estado do Rio de Janeiro, com ênfase em Telecomunicações

## Abstract

Due to the increased availability and distribution of music through streaming platforms, it becomes relevant the use of tools that improve the user experience, such as audio classification for creating, categorizing and recommending catalogs. In this project, it will be presented the temporal and spectral features of an audio signal, an introduction of machine learning models as well as an analysis of the extracted data from the polyphonic compositions IRMAS dataset for each selected musical instrument. Moreover, three multiclass classification methods will be developed, them being: Support Vector Machine, Random Forest and Artificial Neural Networks. Lastly, each model performance will be evaluated through its metrics and main features.

## Repository structure
```
├───code
│   └───__pycache__
├───data
│   ├───dump
│   ├───extracted_data
│   ├───instrument_sample
│   ├───IRMAS-Sample
│   │   ├───Testing
│   │   └───Training
│   │       ├───sax
│   │       └───vio
│   ├───IRMAS-TrainingData
│   │   ├───flu
│   │   ├───gel
│   │   ├───pia
│   │   ├───sax
│   │   ├───tru
│   │   └───vio
│   └───test_audio
│       ├───aspirador
│       ├───IRMAS
│       │   ├───escolhidas
│       │   │   ├───etapa 1
│       │   │   └───etapa 2
│       │   ├───IRTestingData-Part2
│       │   ├───Part1
│       │   └───Part3
│       ├───pedra
│       ├───trem
│       ├───trim
│       └───whole songs
├───images
│   ├───audio
│   ├───code_generated
│   │   ├───cols
│   │   ├───heat
│   │   ├───inst_samples
│   │   ├───models
│   │   ├───shap
│   │   └───sig_wave
│   ├───instrumentos
│   │   ├───guitar
│   │   ├───piano
│   │   ├───sax
│   │   ├───tru
│   │   └───violino
│   ├───machine learning
│   │   └───act_func
│   └───projeto
├───models
└───project
    ├───anteprojeto
    └───projeto
```