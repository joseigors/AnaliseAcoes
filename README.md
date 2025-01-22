Análise de Ações - Aprimoramento de Conhecimentos em Análise de Dados
📖 Sobre o Projeto
Este repositório contém uma análise de retornos históricos de ações da Bolsa de Valores Brasileira (B3). O objetivo principal deste projeto foi aprimorar os meus conhecimentos em análise de séries temporais e estatísticas aplicadas a dados financeiros, enquanto praticava e desenvolvia habilidades em Python.

Dados contendo informações erradas devido a fonte, não tomar como recomendações e sim como didática.

A análise foca em identificar padrões de performance de ações, especialmente observando o comportamento após dias de queda, e calcular métricas importantes, como a média dos retornos e o desvio padrão dos retornos, para entender a volatilidade das ações.

Este foi um projeto leve e prazeroso, uma forma de continuar praticando sem perder o ritmo, ao mesmo tempo que aprofundei meus conhecimentos sobre análise financeira e estatísticas.

🧰 Tecnologias Utilizadas
Python: Linguagem utilizada para manipulação e análise dos dados.
Pandas: Biblioteca usada para manipulação de dados.
Matplotlib e Seaborn: Utilizadas para a visualização dos dados, especialmente para gerar histogramas e gráficos de distribuição.
Jupyter Notebook: Ambiente de desenvolvimento utilizado para a análise interativa.

⚙️ Funcionalidades
Filtragem de Dados: Uma análise simples como filtrar as ações que tiveram um retorno negativo no dia anterior e realiza a análise desses ativos.
Cálculo de Métricas:
Média dos Retornos: Média dos retornos diários das ações após um dia de queda.
Desvio Padrão dos Retornos: Medição da volatilidade dos retornos dessas ações.
Visualização: Geração de histogramas para entender a distribuição dos retornos dos ativos analisados.

📊 Resultados Obtidos
Se o seu objetivo é buscar ações com boa recuperação após quedas, B3SA3, WEGE3 e BBDC4 são as mais promissoras, pois apresentam altos retornos médios e um risco relativamente moderado.
Se você tem um perfil mais conservador, pode preferir ações com menor volatilidade, como WEGE3 e ITUB4, que apresentam menor risco com retornos ainda interessantes.
ELET3, por outro lado, apresenta um desempenho pior em termos de média dos retornos, além de uma maior volatilidade, o que pode não ser tão atraente para investidores que buscam estabilidade após quedas.

🚀 Como Rodar o Projeto
Para rodar o projeto localmente, você precisará de um ambiente Python com as bibliotecas necessárias. Siga os passos abaixo:

Clone o repositório:
git clone https://github.com/joseigors/AnaliseAcoes.git

Navegue até o diretório do projeto:
cd AnaliseAcoes

Instale as dependências:
pip install yfinance

bibliotecas necessárias:
pip install pandas matplotlib seaborn

Execute o Jupyter Notebook para interagir com o código:
jupyter notebook
