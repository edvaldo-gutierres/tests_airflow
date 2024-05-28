# tests_airflow
Repositório para testes de uso do Airflow


# Instalação

## Apache Airflow com o WSL

Este guia fornece instruções para configurar o Apache Airflow utilizando o WSL (Windows Subsystem for Linux).

## Instalar o Astro

Para instalar o Astro, execute o seguinte comando:

```sh
curl -sSL install.astronomer.io | sudo bash -s
```

## Criar Pasta para o Projeto

Crie uma nova pasta para o seu projeto:

```sh
mkdir <nome_pasta>
```

## Iniciar o Astro

Inicialize o Astro na pasta criada:

```sh
cd <nome_pasta>
astro dev init
```

## Abrir o VsCode

Abra o Visual Studio Code na pasta do projeto:

```sh
code .
```

## Configurar o Docker

1. Abra o Docker.
2. Vá em `Settings` > `Resources` > `WSL Integration`.
3. Verifique se a opção `Ubuntu` está ativada.

## Inicializar o Ambiente no WSL

Para iniciar o ambiente, execute o seguinte comando:

```sh
astro dev start
```

## Instalar Python e Pandas

Para instalar o Python e a biblioteca Pandas, execute os seguintes comandos:

```sh
sudo apt install python3-pip
pip install pandas
pip install requests
```