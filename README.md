# Sistema de Classificação de Fraturas

#### Projeto da Disciplina PET1706 - TÓPICOS ESPECIAIS EM ENGENHARIA DE SOFTWARE (Redes Neurais Artificiais) - 2024.1 
###### Professora: [Rosana Rego](https://github.com/roscibely)

![Bacharel em Engenharia de Software]

Curso: [Bacharel em Engenharia de Software](https://engsoftwarepaudosferros.ufersa.edu.br/apresentacao/)

- UFERSA - Campus Pau dos Ferros

Este é um sistema de identificação de fraturas desenvolvido em Python utilizando OpenCV. O sistema utiliza técnicas de Processamento de Imagem e Machine Learning para identificar quais os tipos de fraturas apresentam em uma imagem.

## Funcionalidades Principais

- **Identificação de Fraturas**: O sistema é capaz de analisar imagens contendo partes do corpo humanos e classificar dentro de 10 possíveis fraturas: Avulsão; Triturada; Luxação; Galho verde; Linha fina; Impactado; Longitudinal; Obliqua; Patologica; Espiral.

- **Processamento de Imagem**: Utilizando OpenCV, o sistema realiza o pré-processamento das imagens, destacando as fraturas nas partes do corpo humano e classificando o tipo dentro das 10 classes pré-determinadas.

- **Modelo de Machine Learning**: O sistema utiliza um modelo de Machine Learning treinado previamente para classificação de fraturas. Este modelo foi treinado com uma variedade de imagens de diferentes tipos de fraturas.

## Requisitos de Sistema

- Python 3.x
- OpenCV
- Bibliotecas Python: NumPy, Streamlit, scikit-learn, etc. (detalhes podem ser encontrados no arquivo requirements.txt)

## Instalação

1. Clone o repositório do GitHub:

```bash
git clone https://github.com/ClassNeuralNetwork/Classificao_fratura.git
```

2. Navegue até o diretório do projeto:

```bash
cd projeto_fraturas
```

3. Instale as dependências usando pip:

```bash
pip install -r requirements.txt
```

## Contribuição

Contribuições são bem-vindas! Se você quiser contribuir para este projeto, por favor, abra uma issue para discutir as mudanças propostas ou envie um pull request.

## Equipe

- ![Marcos Oliveira](https://github.com/marcosoliv26)
- ![Lanuza Santos](https://github.com/LanuzaSantos)


## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT). Consulte o arquivo `LICENSE` para obter mais detalhes.
