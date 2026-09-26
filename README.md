# Monitoramento de Desastres Naturais: Global Solutions 2025.1

Aplicação de console em **Python** para registrar desastres naturais ligados à água (enchentes, tempestades, ciclones) e consolidar o perfil das pessoas afetadas, para **priorizar o atendimento de populações vulneráveis**.

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)

> Projeto da Global Solutions 2025.1, disciplina **Database Application & Data Science**, do curso de Data Science da FIAP (Prof.ª Patrícia Angelini). Trabalho em dupla.

## Funcionalidades

**Entrada de dados**, para cada desastre:

- tipo, país, cidade, bairro e rua;
- total de pessoas afetadas;
- quantidade de crianças, adultos, idosos, pessoas com mobilidade reduzida e feridos.

**Validação:** a soma das categorias precisa bater exatamente com o total informado. Se não bater, o programa avisa se a soma excede ou fica abaixo do total e pede os valores de novo.

**Relatório final:**

- total de desastres registrados;
- total geral de pessoas afetadas;
- totais por categoria;
- categoria mais afetada;
- desastre com mais pessoas afetadas, com o endereço completo.

## Como executar

Requer apenas Python 3, sem bibliotecas externas.

```bash
python monitoramento_desastres.py
```

Exemplo de sessão:

```text
Insira a quantidade de desastres registrados: 2
Tipo de desastre: Enchente
País: Brasil
Cidade: Porto Alegre
Bairro: Centro
Rua: Rua dos Andradas
Total de pessoas afetadas: 120
Número de crianças: 30
Número de adultos: 50
Número de idosos: 20
Número de pessoas com mobilidade reduzida: 10
Número de feridos: 10
...
```

## Próximos passos

- Persistir os registros em um banco de dados (Oracle ou SQLite) em vez de listas em memória.
- Tratar entradas inválidas (texto onde se espera número).
- Exportar os dados para CSV e analisá-los com pandas.

## Integrantes

- **Cynthia Emiko de Souza Takematu** (representante) · [GitHub](https://github.com/cynthiatakematu)
- Gabriel Scaraficci de Lima
