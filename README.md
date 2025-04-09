# Python_Desafios_de_Codigo_02
Esse desafio de Código da Formação Cientista de Dados do Programa Oracle One, abrange Funções e Estruturas de Dados em Python

# Análise de Dados de Experimentos com Fungos

Este repositório contém um conjunto de scripts em Python que auxiliam na análise de dados coletados durante experimentos sobre o comportamento de uma cultura de fungos. O objetivo é avaliar a relação entre pressão e temperatura em um ambiente controlado, ajudando a determinar as melhores condições para os testes.

## Funcionalidades

- **Divisão de Colunas**: Uma função que recebe listas de pressão e temperatura, calcula a razão entre elas e trata exceções como:
  - Tamanhos diferentes das listas (ValueError)
  - Divisão por zero (ZeroDivisionError)

- **Verificação de Pontuação**: Uma função que avalia uma lista de palavras e verifica se há pontuações não tratadas, lançando uma exceção caso encontre.

- **Conversão de Listas para Float**: Uma função que converte elementos de uma lista para o tipo float, tratando erros de entrada inválida.

## Estrutura do Repositório

/analisador_fungos

│ 

├── README.md # Este arquivo 

  ├── analise_fungos.py # Script principal para análise de dados 
  
  └── requisitos.txt # Dependências do projeto


  
## Instalação

Para executar os scripts, você precisará ter o Python instalado em sua máquina. Você pode instalar as dependências necessárias usando o `pip`. 

```bash
pip install -r requisitos.txt

```

## Uso

Divisão de Colunas

Para usar a função de divisão de colunas, você pode importar o módulo e chamar a função divide_colunas:

```bash
from analise_fungos import divide_colunas

pressoes = [100, 120, 140, 160, 180]
temperaturas = [20, 25, 30, 35, 40]

resultados = divide_colunas(pressoes, temperaturas)
print(resultados)
```

## Verificação de Pontuação

Para verificar se há pontuações em uma lista de palavras:

```bash
from analise_fungos import verificar_pontuacao

lista_palavras = ['Python', 'é', 'uma', 'linguagem,', 'de', 'programação']
verificar_pontuacao(lista_palavras)
```

## Conversão de Listas para Float
Para converter uma lista de strings para floats:

```bash
from analise_fungos import converter_para_float

lista = ['10', '20.5', '30']
resultado = converter_para_float(lista)
print(resultado)
```

## Contribuição
Contribuições são bem-vindas! Se você deseja contribuir para este projeto, siga os passos abaixo:

Faça um fork deste repositório.
Crie uma nova branch (git checkout -b feature/nome-da-sua-feature).
Faça suas alterações e commit (git commit -m 'Adicionando nova funcionalidade').
Envie para o repositório remoto (git push origin feature/nome-da-sua-feature).
Abra um Pull Request.

## Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

## Contato
Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

Luiz Andre de Souza  - landresouza36@gmail.com

GitHub: brodyandre
