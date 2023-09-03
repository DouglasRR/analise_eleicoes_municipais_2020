# Pré-processamento e Análise de Dados Eleitorais

##Descrição

Este projeto realiza o pré-processamento e análise de dados eleitorais do estado de São Paulo. Os dados são manipulados de forma eficiente para atender às restrições de memória RAM, incluindo limpeza de nomes, criação de tabelas auxiliares e visualização interativa de resultados.

##Passo a Passo

1. **Preparação de Dados e Manipulação Inicial**
    - Baixe as bases de dados de eleições.
    - Pré-processamento cuidadoso para adequação à memória RAM.
    - Exclusão de tuplas não relacionadas a São Paulo.
    - Criação de tabelas auxiliares para municípios, gênero, faixa etária e grau de escolaridade.

2. **Limpeza de Nomes**
    - Implementação da função `limpar_nome` para remover caracteres especiais.
    - Aplicação da função aos nomes dos candidatos.

3. **Manipulação de Dados Adicionais**
    - Criação de tabelas para cargos, tipos de voto, partidos e candidatos.
    - Mapeamento de nomes de candidatos para um identificador único (`ID_CANDIDATO`).
    - Exportação otimizada de dados para arquivos CSV e Excel.

4. **Visualização Interativa de Dados**
    - Implementação de pesquisa interativa por municípios e candidatos.
    - Uso da biblioteca IPython Widgets para criar elementos interativos.
    - Exibição de candidatos mais votados em municípios e municípios onde os candidatos tiveram mais votos.

## Requisitos

- [Python](https://www.python.org/downloads/)
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
- [Widgets IPython](https://ipywidgets.readthedocs.io/en/stable/user_install.html)
- [Dados](https://drive.google.com/file/d/1GGuBidgzo-94Bp2IOjngXPaX9rA5ZX8j/view?usp=gmail)

## Executando o Projeto

1. Faça o download das bases de dados de eleições.
2. Coloque os arquivos de dados no mesmo diretório do script Python.
3. Execute o script Python para pré-processamento e visualização interativa.
4. Observe a saída interativa no Jupyter Notebook para explorar os resultados.

## Recursos Adicionais

- [Documentação do Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html)
- [Documentação do IPython Widgets](https://ipywidgets.readthedocs.io/en/stable/index.html)

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar pull requests.

##Contato

Se você tiver dúvidas ou sugestões, entre em contato:

Douglas
douglas.rioram04@gmail.com