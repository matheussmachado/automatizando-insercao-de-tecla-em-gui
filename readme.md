# INSERINDO AUTOMATICAMENTE TECLA DO COMPUTADOR.

  
## Sobre o projeto

![ezgif com-gif-maker](https://user-images.githubusercontent.com/63216146/125514927-3fb7b1d7-c2fb-496d-85e1-1a5d3f760e3f.gif)


O projeto consiste em **inserir automaticamente a tecla do teclado do computador**, de modo virtual, através de comando que podem ser configurados pelo usuário. Os comandos atualmente são: inicializar a inserção, pausar a inserção, finalizar o programa.  

O gif acima ilustra o processo:

Ao inserir o comando 'a', é inserido automaticamente a saída **typing... **. Em seguida, ao inserir o comando 'p' é pausado o processo de inserção. Depois, é repetido o comando 'a' de inserção e por fim é acionado o comando 'f' que finaliza o programa. Para cada comando, o status na primeira linha do terminal é alterado.

## Por que?
  

Esse projeto foi concebido da necessidade de aprender a utilizar ferramentas que permitem esse tipo de interação com o sistema operacional.
  

## Como executar esse projeto

### Pré-requisitos

- Python 3.9+

### Instalando

Após obter este repositório. No diretório do Projeto:  

  - Crie e ative o ambiente virtual do Python 3;

- instale as dependencias do projeto: `pip install -r requirements.txt`;

- verificar o arquivo **command_config.json** e se quiser, alterar os comandos pré determinados;

- execute o programa: **run.py**