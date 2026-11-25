# Calculadora de Idade

Aplicação desktop desenvolvida em Python para calcular a idade de uma
pessoa a partir da data de nascimento e de uma data inicial informada
pelo usuário.

O programa apresenta a diferença entre as datas em anos, meses e dias.
Também informa o dia da semana em que a pessoa nasceu e verifica se o
ano de nascimento foi bissexto.

## Integrantes do grupo

-   **Getúlio Portela Leal**
-   **José Adriano Moreira**

## Objetivo do projeto

Desenvolver uma ferramenta simples e intuitiva para realizar o cálculo
de idade por meio de uma interface gráfica, colocando em prática
conceitos de programação em Python, criação de interfaces, funções,
tratamento de erros e manipulação de datas.

## Funcionalidades

-   Seleção da data inicial por meio de um calendário.
-   Seleção da data de nascimento por meio de um calendário.
-   Cálculo da idade em anos, meses e dias.
-   Identificação do dia da semana correspondente ao nascimento.
-   Verificação se o ano de nascimento é bissexto.
-   Validação das datas informadas.
-   Exibição de mensagens de erro quando as datas são inválidas ou
    quando a data de nascimento é posterior à data inicial.

## Tecnologias e bibliotecas

O projeto foi desenvolvido utilizando:

-   **Python 3** --- linguagem de programação.
-   **Tkinter** --- criação da interface gráfica.
-   **tkcalendar** --- seleção de datas por calendário.
-   **python-dateutil** --- cálculo da diferença entre datas com
    `relativedelta`.

## Requisitos

-   Python 3 instalado.
-   Bibliotecas `tkcalendar` e `python-dateutil`.

## Instalação das dependências

No terminal, execute:

``` bash
pip install tkcalendar python-dateutil
```

O módulo `tkinter` normalmente já acompanha a instalação padrão do
Python. Em algumas distribuições Linux, pode ser necessário instalá-lo
separadamente pelo gerenciador de pacotes do sistema.

## Como executar

1.  Baixe ou clone este repositório.
2.  Abra a pasta do projeto no terminal ou em uma IDE, como o PyCharm ou
    o Visual Studio Code.
3.  Instale as dependências indicadas acima.
4.  Execute o arquivo:

``` bash
python CALCULADORA_IDADE.py
```

A janela da Calculadora de Idade será aberta. Selecione a data inicial e
a data de nascimento e clique em **Calcular**.

## Organização do código

O código está organizado em partes:

-   **Definição das cores:** configura a identidade visual da aplicação.
-   **Lista dos dias da semana:** permite apresentar o dia
    correspondente à data de nascimento em português.
-   **Função `eh_bissexto(ano)`:** verifica se determinado ano é
    bissexto.
-   **Criação da janela e dos frames:** configura a janela principal e
    divide a interface em áreas.
-   **Função `parse_data(texto_data)`:** interpreta a data no formato
    dia/mês/ano.
-   **Função `calcular()`:** valida as datas, calcula a diferença com
    `relativedelta` e atualiza os resultados exibidos.
-   **Componentes da interface:** campos de data, rótulos de resultado e
    botão de cálculo.

## Interface

A aplicação possui uma interface gráfica com cabeçalho, campos para
seleção das datas, área de apresentação da idade calculada e informações
complementares sobre o nascimento.

## Considerações finais

O desenvolvimento deste projeto permitiu aplicar conhecimentos de Python
na construção de uma aplicação com interface gráfica. A atividade também
envolve o uso de bibliotecas externas, a criação e utilização de
funções, a validação de dados e o tratamento de situações de erro.

------------------------------------------------------------------------

**Projeto:** Calculadora de Idade\
**Integrantes:** Getúlio Portela Leal e José Adriano Moreira
