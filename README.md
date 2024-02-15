# Projeto de Previsão de Preços de Aluguéis Temporários em Nova York

## Introdução

Este projeto tem como objetivo criar um modelo preditivo para prever os preços de aluguéis temporários na cidade de Nova York. O desafio é parte de uma colaboração entre a Indicium e um cliente interessado na criação de uma plataforma de aluguéis temporários na cidade. A análise exploratória dos dados do maior concorrente foi solicitada para fundamentar a estratégia de precificação e validar um modelo preditivo.


# Passo a Passo para Configuração do Ambiente Virtual e Instalação das Dependências

Este documento descreve os passos necessários para configurar um ambiente virtual Python e instalar as dependências listadas no arquivo `requirements.txt`.

## Configuração do Ambiente Virtual

1. **Instale o Virtualenv (caso ainda não tenha instalado):**
   - Execute o seguinte comando para instalar o virtualenv via pip:
     ```
     pip install virtualenv
     ```

2. **Crie um Ambiente Virtual:**
   - Navegue até o diretório do seu projeto e execute o seguinte comando para criar um ambiente virtual:
     ```
     virtualenv venv
     ```

3. **Ative o Ambiente Virtual:**
   - Para ativar o ambiente virtual no Windows, execute:
     ```
     venv\Scripts\activate
     ```
     Para ativar no Linux/Mac, execute:
     ```
     source venv/bin/activate
     ```

## Instalação das Dependências

1. **Instale as Dependências Utilizando o Arquivo `requirements.txt`:**
   - Com o ambiente virtual ativado, execute o seguinte comando para instalar todas as dependências listadas no arquivo `requirements.txt`:
     ```
     pip install -r requirements.txt
     ```

## Execução do Projeto

Com todas as dependências instaladas corretamente, você está pronto para executar o projeto.

## Desativação do Ambiente Virtual

Quando você terminar de trabalhar no projeto, você pode desativar o ambiente virtual:

### Observação

O projeto foi desenvolvido no Google Colab para garantir a estabilidade de execução, especialmente em dispositivos com restrições de memória. Recomenda-se utilizar o Google Colab para reproduzir o projeto de forma consistente, porém, caso deseje executar localmente, certifique-se de possuir os recursos adequados para evitar problemas de desempenho ou falta de memória.
