# DRL-Mobtest-SelectNLTest

Este guia fornece as instruções para a instalação e configuração do ambiente necessário para executar o DRL Mobtest.

## 1. Instalar Conda

Certifique-se de ter o [Conda](https://docs.conda.io/en/latest/miniconda.html) instalado antes de prosseguir.

## 2. Instalar Android Studio

Baixe e instale o [Android Studio](https://developer.android.com/studio) para executar o APK no dispositivo.

## 3. Instalar APK no Dispositivo

Para testar o aplicativo, instale o APK diretamente no dispositivo Android.

## 4. Instalar e Configurar o Ambiente

```sh
# Criar ambiente Conda com Python 3.8.5
conda create --name env python=3.8.5
```

```sh
# Ativar o ambiente Conda
conda activate env
```

```sh
# Instalar o pacote DRL Mobtest
pip install ./drlmobtest_elianecollins-0.0.2-py3-none-any.whl
```

```sh
# Instalar Torch e dependências
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
pip install torch==1.7.0+cu110 -f https://download.pytorch.org/whl/torch_stable.html
```

```sh
# Instalar Spyder
conda install spyder==5.3.1
```
```sh
# Instalar bibliotecas complementares
pip install matplotlib
pip install pillow==6.2.1
pip install tensorflow==2.2.0
```
```sh
# Instalar OpenAI API (opcional)
pip install openai
```
