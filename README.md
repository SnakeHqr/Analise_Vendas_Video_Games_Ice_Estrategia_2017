# -Ice-Video-Game-Sales
Estudo de caso analítico completo para a loja online Ice, com o objetivo de identificar padrões de sucesso em vendas de jogos para planejar campanhas publicitárias de 2017. O projeto envolveu a limpeza e pré-processamento de um grande dataset histórico, análise de tendências de mercado por plataforma e gênero, criação de perfis regionais .

🎮 Análise de Vendas Globais de Video Games (Ice): Estratégia de Campanhas 2017

Descrição do Projeto

Estudo de caso analítico completo para a loja online Ice, com o objetivo de identificar padrões de sucesso em vendas de jogos para planejar campanhas publicitárias de 2017. O projeto envolveu a limpeza e pré-processamento de um grande dataset histórico, análise de tendências de mercado por plataforma e gênero, criação de perfis regionais (NA, EU, JP) e a realização de testes de hipóteses estatísticas.

O foco principal foi determinar o período de dados relevante, avaliar a influência das avaliações (Crítica e Usuário) sobre as vendas e prever os possíveis sucessos.

🎯 Objetivos de Negócio

Recomendar as plataformas e gêneros mais lucrativos para investimento em 2017.

Determinar a influência real das avaliações de Críticos vs. Usuários nas vendas.

Identificar padrões de consumo regional para personalizar campanhas em NA, EU, e JP.

Metodologia e Ferramentas

1. Preparação de Dados e Engenharia de Features

Tratamento de Missing Values: Estratégias para lidar com valores ausentes em pontuações e, especificamente, com a abreviação TBD ("to be determined") nas classificações.

Cálculo de Vendas Totais: Agregação das vendas regionais (NA, EU, JP, Outras) em uma única coluna Total_Sales.

Definição do Período Relevante: Análise do ciclo de vida das plataformas para definir o dataset apropriado para modelagem de 2017.

2. Análise Exploratória e Estatística

Ciclo de Vida de Plataformas: Identificação de plataformas que estão crescendo, diminuindo ou saindo do mercado (plataformas "mortas").

Distribuições de Vendas: Uso de Diagramas de Caixa (Box Plots) para comparar a variabilidade de vendas entre as plataformas.

Correlação: Cálculo da correlação entre as pontuações (Crítica e Usuário) e as vendas para plataformas populares, como PS4 e XOne.

3. Teste de Hipóteses

Implementação do Teste T de Student para avaliar a igualdade de médias entre grupos, com um nível de significância (alfa) de 0.05.

Hipótese 1: As classificações médias dos usuários das plataformas Xbox One e PC são as mesmas.

Hipótese 2: As classificações médias de usuários para os gêneros Action (Ação) e Sports (Esportes) são diferentes.

Ferramenta

Uso

Python

Linguagem de programação central.

Pandas & NumPy

Limpeza, manipulação e cálculo de métricas.

Matplotlib & Seaborn

Visualização (Box Plots, Scatter Plots, Distribuições).

SciPy

Implementação do Teste T de Student.

💡 Resultados Chave (Recomendações para 2017)

Plataformas Chave: O investimento deve ser focado nas plataformas da geração mais recente (PS4, XOne), visto que o ciclo de vida das vendas em gerações antigas (PS3, X360) já está em declínio acentuado.

Fator Crítico: As Avaliações de Críticos têm uma correlação significativamente mais forte com o volume de vendas do que as Avaliações de Usuários, o que deve orientar as decisões de marketing e aquisição de títulos.

Segmentação Regional: A análise do perfil de usuário revelou diferenças claras, como a forte preferência por jogos Role-Playing (RPG) no Japão em comparação com os gêneros Action e Shooter na América do Norte e Europa.
