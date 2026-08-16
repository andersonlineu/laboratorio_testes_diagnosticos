# Laboratório de Testes Diagnósticos

[![DOI](https://zenodo.org/badge/1335466423.svg)](https://doi.org/10.5281/zenodo.21966633)

**Tecnologia educativa digital interativa para o ensino de testes diagnósticos**

**Autor e desenvolvedor:** Anderson Lineu Siqueira dos Santos
**Versão:** 1.0.0
**Ano:** 2026
**Idioma:** Português
**Licença:** MIT

## Acesso à tecnologia

A tecnologia educativa pode ser utilizada diretamente pelo navegador:

https://andersonlineu.github.io/laboratorio_testes_diagnosticos/

## Apresentação

O **Laboratório de Testes Diagnósticos** é uma tecnologia educativa digital interativa desenvolvida para apoiar o ensino e a aprendizagem dos principais conceitos relacionados à avaliação e à interpretação de testes diagnósticos.

A ferramenta reúne, em um único ambiente, uma simulação clínica, uma calculadora baseada na tabela 2×2 e um nomograma de Fagan interativo. Os resultados são apresentados numericamente, em frequências naturais, em tabelas, em representações gráficas e em frases interpretativas.

A proposta é facilitar a compreensão de conceitos que, muitas vezes, são apresentados de forma excessivamente abstrata ou restrita à memorização de fórmulas. Por meio da interação direta com os parâmetros, o estudante pode modificar valores, comparar cenários e observar imediatamente as consequências das alterações realizadas.

A tecnologia procura aproximar os cálculos epidemiológicos do raciocínio clínico, ajudando o estudante a compreender que um resultado de teste não deve ser interpretado isoladamente como sinônimo de presença ou ausência de doença. O resultado modifica uma probabilidade que já existia antes da realização do teste.

## Finalidade educativa

A principal finalidade da tecnologia é apoiar o desenvolvimento do raciocínio clínico e epidemiológico relacionado aos testes diagnósticos.

O recurso permite demonstrar, de maneira visual e prática, que:

* sensibilidade e especificidade são medidas relacionadas ao desempenho do teste diante da condição estabelecida pelo teste de referência;
* o valor preditivo positivo e o valor preditivo negativo dependem da probabilidade pré-teste ou da prevalência da doença;
* as razões de verossimilhança dependem da sensibilidade e da especificidade;
* um mesmo teste pode apresentar diferentes valores preditivos quando aplicado em populações com prevalências distintas;
* um resultado positivo não significa obrigatoriamente que o paciente tenha a doença;
* um resultado negativo não elimina completamente a possibilidade de doença;
* a interpretação clínica depende tanto do desempenho do teste quanto da probabilidade de doença antes da sua realização;
* frequências naturais podem tornar a comunicação dos resultados mais compreensível;
* os verdadeiros positivos, falsos positivos, falsos negativos e verdadeiros negativos possuem consequências clínicas distintas.

## Público-alvo

A tecnologia foi desenvolvida principalmente para estudantes e professores das áreas da saúde, especialmente:

* medicina;
* enfermagem;
* epidemiologia;
* saúde coletiva;
* medicina baseada em evidências;
* bioestatística;
* pesquisa clínica;
* áreas relacionadas à avaliação de tecnologias em saúde.

Também pode ser utilizada em atividades de educação permanente, capacitação de profissionais, revisão de conteúdos e discussão de estudos de acurácia diagnóstica.

## Organização da tecnologia

O Laboratório de Testes Diagnósticos está organizado em três áreas principais:

1. **Simulação clínica**;
2. **Calculadora por tabela 2×2**;
3. **Nomograma de Fagan interativo**.

As três áreas estão relacionadas, mas podem ser utilizadas de maneira independente, conforme o objetivo da aula ou da atividade de aprendizagem.

# 1. Simulação clínica

A área de simulação clínica permite construir uma população hipotética a partir de quatro parâmetros:

* probabilidade pré-teste;
* sensibilidade;
* especificidade;
* tamanho da população simulada.

A **probabilidade pré-teste** representa a estimativa da probabilidade de doença antes de se conhecer o resultado do teste. Dependendo da situação apresentada, ela pode representar a prevalência da doença na população ou uma estimativa individual baseada em história clínica, sinais, sintomas, fatores de risco e dados epidemiológicos.

A **sensibilidade** representa a proporção de pessoas com a doença que apresentam resultado positivo.

A **especificidade** representa a proporção de pessoas sem a doença que apresentam resultado negativo.

Os valores podem ser modificados utilizando controles deslizantes ou por digitação direta. Sempre que um parâmetro é modificado, todos os resultados relacionados ao cenário são recalculados automaticamente.

## Cenários predefinidos

A simulação oferece três configurações iniciais:

* **Triagem**;
* **Confirmação diagnóstica**;
* **Equilibrado**.

Esses cenários podem ser utilizados como ponto de partida para discussões em sala de aula. O professor também pode construir seus próprios casos, modificando livremente os parâmetros.

## Medidas calculadas

A partir dos valores informados, a tecnologia calcula:

* valor preditivo positivo;
* valor preditivo negativo;
* razão de verossimilhança positiva;
* razão de verossimilhança negativa;
* acurácia;
* taxa de falso positivo;
* taxa de falso negativo;
* probabilidade residual de doença após um teste negativo.

O **valor preditivo positivo — VPP** corresponde à probabilidade de doença entre as pessoas que apresentaram resultado positivo.

O **valor preditivo negativo — VPN** corresponde à probabilidade de ausência da doença entre as pessoas que apresentaram resultado negativo.

A **razão de verossimilhança positiva — RV+** informa quanto um resultado positivo é mais provável entre pessoas com a doença do que entre pessoas sem a doença.

A **razão de verossimilhança negativa — RV−** representa a relação entre a probabilidade de resultado negativo nas pessoas com doença e a probabilidade de resultado negativo nas pessoas sem doença.

## Interpretação do resultado individual

A simulação permite alternar entre a interpretação de um teste positivo e de um teste negativo.

Para o teste positivo, a tecnologia apresenta:

* probabilidade de doença após o resultado positivo;
* interpretação em linguagem natural;
* quantidade esperada de verdadeiros positivos;
* quantidade esperada de falsos positivos.

Para o teste negativo, apresenta:

* probabilidade residual de doença;
* valor preditivo negativo;
* redução da probabilidade de doença;
* interpretação clínica em linguagem natural.

Essa funcionalidade ajuda a reforçar que o resultado do teste modifica a probabilidade de doença, mas não determina sozinho o diagnóstico.

## Frequências naturais

A tecnologia converte os percentuais em números esperados dentro da população simulada.

Os resultados são distribuídos em:

* verdadeiros positivos — VP;
* falsos positivos — FP;
* falsos negativos — FN;
* verdadeiros negativos — VN.

A apresentação em frequências naturais permite visualizar:

* quantas pessoas com doença seriam corretamente identificadas;
* quantas pessoas com doença receberiam resultado negativo;
* quantas pessoas sem doença receberiam resultado positivo;
* quantas pessoas sem doença seriam corretamente classificadas como negativas.

Os valores apresentados na população simulada são exibidos como números inteiros, facilitando a interpretação didática.

## Tabela da população simulada

Os desfechos são organizados em uma tabela contendo:

* resultados positivos;
* resultados negativos;
* pessoas com doença;
* pessoas sem doença;
* totais das linhas;
* totais das colunas;
* total da população.

Essa representação possibilita relacionar os parâmetros de desempenho do teste com a estrutura tradicional da tabela 2×2.

## Mapa dos desfechos

O mapa dos desfechos apresenta visualmente a participação proporcional dos quatro resultados possíveis:

* verdadeiro positivo;
* falso positivo;
* falso negativo;
* verdadeiro negativo.

Cada desfecho é representado por uma cor e ocupa uma parcela proporcional da população simulada.

Essa visualização permite identificar rapidamente a magnitude dos acertos e erros produzidos em cada cenário. Também ajuda a demonstrar que um teste com boa sensibilidade pode produzir muitos falsos positivos quando utilizado em uma população com baixa prevalência, especialmente quando a especificidade não é elevada.

## Comparação entre cenários

A tecnologia permite guardar os parâmetros atuais como **Cenário A**. Depois disso, o usuário pode modificar os controles e criar um **Cenário B**.

A comparação apresenta:

* probabilidade pré-teste;
* sensibilidade;
* especificidade;
* valor preditivo positivo;
* valor preditivo negativo;
* razão de verossimilhança positiva;
* razão de verossimilhança negativa.

Os valores dos dois cenários são apresentados com cores diferentes e com indicações sobre quais medidas aumentaram, diminuíram ou permaneceram iguais.

Essa funcionalidade permite demonstrar que, quando somente a prevalência é modificada:

* a sensibilidade permanece igual;
* a especificidade permanece igual;
* a RV+ permanece igual;
* a RV− permanece igual;
* o VPP se modifica;
* o VPN se modifica.

# 2. Calculadora por tabela 2×2

A segunda área permite inserir diretamente os resultados observados de uma tabela 2×2.

A tabela organiza os resultados do **teste índice** em relação à classificação estabelecida pelo **teste de referência**.

As linhas representam os resultados positivo e negativo do teste índice. As colunas representam a presença e a ausência da doença segundo o teste de referência.

O usuário deve informar:

* verdadeiro positivo — VP;
* falso positivo — FP;
* falso negativo — FN;
* verdadeiro negativo — VN.

A tabela inicia com todos os campos vazios. Os totais e os indicadores somente são apresentados quando os quatro valores são preenchidos. Caso um dos campos seja apagado, os resultados também são ocultados.

Esse comportamento evita que uma tabela incompleta seja interpretada como um conjunto válido de resultados.

## Resultados da tabela 2×2

Depois do preenchimento, a tecnologia calcula automaticamente:

* total de testes positivos;
* total de testes negativos;
* total de pessoas com doença;
* total de pessoas sem doença;
* total da população estudada;
* prevalência observada;
* sensibilidade;
* especificidade;
* valor preditivo positivo;
* valor preditivo negativo;
* razão de verossimilhança positiva;
* razão de verossimilhança negativa.

Também é apresentada uma leitura rápida em linguagem natural, indicando a proporção de pessoas com doença que testaram positivo e a proporção de pessoas sem doença que testaram negativo.

A ferramenta permite importar para a tabela os valores produzidos na simulação clínica, relacionando os parâmetros teóricos aos números esperados na população.

## Fórmulas utilizadas

### Sensibilidade

`Sensibilidade = VP ÷ (VP + FN)`

### Especificidade

`Especificidade = VN ÷ (VN + FP)`

### Valor preditivo positivo

`VPP = VP ÷ (VP + FP)`

### Valor preditivo negativo

`VPN = VN ÷ (VN + FN)`

### Razão de verossimilhança positiva

`RV+ = sensibilidade ÷ (1 − especificidade)`

### Razão de verossimilhança negativa

`RV− = (1 − sensibilidade) ÷ especificidade`

### Prevalência observada

`Prevalência = (VP + FN) ÷ (VP + FP + FN + VN)`

A organização da tabela também ajuda a diferenciar medidas condicionadas ao estado da doença das medidas condicionadas ao resultado do teste.

Sensibilidade e especificidade partem da classificação definida pelo teste de referência. Os valores preditivos partem dos grupos formados pelo resultado do teste índice.

# 3. Nomograma de Fagan interativo

A terceira área apresenta um nomograma de Fagan dinâmico.

O nomograma permite transformar:

* uma probabilidade pré-teste;
* uma razão de verossimilhança;

em uma:

* probabilidade pós-teste.

O nomograma possui três escalas:

1. probabilidade pré-teste;
2. razão de verossimilhança;
3. probabilidade pós-teste.

O usuário pode modificar a probabilidade pré-teste e a razão de verossimilhança utilizando barras de controle ou digitando os valores diretamente.

A probabilidade pré-teste pode variar de **0,1% a 99,9%**. A razão de verossimilhança pode variar de **0,001 a 1.000**.

A escala da razão de verossimilhança é logarítmica. Uma única linha reta parte da probabilidade pré-teste, passa pela razão de verossimilhança e alcança a probabilidade pós-teste.

A linha e os pontos são atualizados dinamicamente quando os parâmetros são modificados.

O usuário também pode transferir para o nomograma a RV+ ou a RV− calculada na simulação clínica.

## Fundamento probabilístico

O nomograma representa graficamente a aplicação do teorema de Bayes por meio das odds.

### Conversão da probabilidade pré-teste em odds

`Odds pré-teste = probabilidade pré-teste ÷ (1 − probabilidade pré-teste)`

### Cálculo das odds pós-teste

`Odds pós-teste = odds pré-teste × razão de verossimilhança`

### Conversão para probabilidade pós-teste

`Probabilidade pós-teste = odds pós-teste ÷ (1 + odds pós-teste)`

A tecnologia realiza os cálculos automaticamente e apresenta a probabilidade pós-teste em formato percentual e gráfico.

# Possibilidades de utilização pedagógica

A tecnologia pode ser empregada em:

* aulas expositivas dialogadas;
* demonstrações realizadas pelo professor;
* resolução de casos clínicos;
* aprendizagem baseada em problemas;
* aprendizagem baseada em equipes;
* sala de aula invertida;
* atividades em laboratório de informática;
* estudo autônomo;
* revisão de conteúdos;
* avaliação formativa;
* educação permanente de profissionais de saúde.

Durante uma aula, o professor pode solicitar que os estudantes façam previsões antes de modificar os parâmetros.

Algumas perguntas que podem orientar a atividade são:

* O que acontece com o VPP quando a prevalência aumenta?
* O que acontece com o VPN?
* A sensibilidade é modificada quando somente a prevalência muda?
* A especificidade é modificada?
* As razões de verossimilhança se alteram?
* Quantos falsos positivos são esperados em uma população de baixa prevalência?
* Um resultado negativo é suficiente para afastar a doença?
* Qual é a probabilidade pós-teste após um resultado positivo?
* O mesmo teste possui a mesma interpretação em populações diferentes?

# Características técnicas

A tecnologia foi desenvolvida em um único arquivo HTML, utilizando:

* **HTML** para a estrutura do conteúdo;
* **CSS** para a interface, as cores, a responsividade e a apresentação visual;
* **JavaScript** para os cálculos, as comparações, as atualizações dinâmicas e o nomograma.

Os cálculos são realizados diretamente no navegador do usuário.

A utilização não exige:

* instalação de programas adicionais;
* criação de conta;
* autenticação;
* banco de dados;
* processamento em servidor.

Depois de baixado, o arquivo HTML também pode ser aberto localmente.

A interface foi planejada para funcionar em computadores, tablets e telefones celulares. Em telas menores, os componentes são reorganizados para facilitar a leitura.

# Privacidade

A tecnologia não foi desenvolvida para coletar, transmitir ou armazenar dados pessoais ou informações clínicas.

Os valores informados são processados diretamente no navegador. Mesmo assim, recomenda-se utilizar dados fictícios, exemplos didáticos ou informações agregadas durante atividades educacionais.

# Escopo e limitações

O Laboratório de Testes Diagnósticos é uma tecnologia educativa. Sua finalidade é apoiar o ensino, a aprendizagem, a demonstração de conceitos e a realização de simulações.

Os resultados dependem dos valores informados pelo usuário.

A tecnologia não:

* estima automaticamente a probabilidade pré-teste de um paciente;
* avalia a qualidade dos estudos de acurácia;
* verifica a validade do teste de referência;
* substitui protocolos assistenciais;
* substitui julgamento clínico;
* estabelece diagnósticos;
* apresenta recomendações terapêuticas.

Na simulação, sensibilidade e especificidade são tratadas como parâmetros definidos. Na prática, o desempenho de um teste pode variar conforme a população, o espectro clínico, o estágio da doença, o ponto de corte, a técnica de execução, a qualidade da amostra e as características do teste de referência.

O uso em situações reais deve ser acompanhado da avaliação da qualidade das evidências e da adequação dos parâmetros ao contexto clínico.

# Código-fonte

O código-fonte está disponível neste repositório e encontra-se no arquivo:

`index.html`

O arquivo reúne a estrutura da página, a formatação visual, as fórmulas, as funções de cálculo, a lógica da simulação e a programação do nomograma de Fagan.

Repositório:

https://github.com/andersonlineu/laboratorio_testes_diagnosticos

Tecnologia em funcionamento:

https://andersonlineu.github.io/laboratorio_testes_diagnosticos/

# Autoria

**Anderson Lineu Siqueira dos Santos**

# Licença

Este projeto é disponibilizado sob a licença MIT. Consulte o arquivo `LICENSE` para conhecer os termos de utilização, modificação e distribuição.
