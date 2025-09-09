# Agente Socrático com Gemini

Este projeto cria uma **IA Socrática** usando a API do [Google Gemini](https://ai.google.dev/), que reflete internamente sobre frases filosóficas antes de dar uma explicação detalhada.  
A abordagem é inspirada no **método socrático**, incentivando a exploração de significados e interpretações antes de apresentar uma resposta final.

## Funcionalidades
- Recebe uma frase filosófica como entrada.  
- O modelo primeiro faz perguntas internamente para refletir sobre diferentes interpretações.  
- Em seguida, fornece uma resposta final detalhada e explicativa.  

## Pré-requisitos
Antes de rodar, você precisa ter instalado:

- Python 3.10+  
- [pip](https://pip.pypa.io/en/stable/)  
- Conta e chave de API do Gemini (Google AI Studio)  

## Instalação
Clone o repositório e entre na pasta:

    git clone https://github.com/seu-usuario/agente-socratico-gemini.git
    cd agente-socratico-gemini

Crie e ative um ambiente virtual (opcional, mas recomendado):

Linux/Mac:
    
    python -m venv venv
    source venv/bin/activate

Windows:
    
    python -m venv venv
    venv\Scripts\activate

Instale as dependências:

    pip install -r requirements.txt

## Configuração
Crie um arquivo **.env** na raiz do projeto e adicione sua chave da API Gemini:

    GEMINI_API_KEY=coloque_sua_chave_aqui

## Uso
Execute o script principal:

    python main.py

Digite uma frase filosófica quando solicitado e receba a reflexão seguida da explicação.
