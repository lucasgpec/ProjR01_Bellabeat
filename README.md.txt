# Análise de Dados de Fitness para a Estratégia de Marketing da Bellabeat

![Bellabeat](https://i.imgur.com/gA0YhYx.png ) 
*Imagem conceitual de produtos Bellabeat*

## 1. Visão Geral do Projeto

Este é um projeto de análise de dados para o portfólio de Ciência de Dados, focado em um estudo de caso da **Bellabeat**, uma empresa de tecnologia de bem-estar. O objetivo é analisar dados de uso de dispositivos de fitness para identificar tendências e obter insights que possam guiar a estratégia de marketing da empresa.

A análise segue as seis etapas do processo de análise de dados: **Perguntar, Preparar, Processar, Analisar, Compartilhar e Agir**.

## 2. O Cenário de Negócios

A Bellabeat é uma empresa que fabrica dispositivos inteligentes focados na saúde e bem-estar de mulheres. Para se manter competitiva e expandir sua base de clientes, a empresa precisa de uma estratégia de marketing baseada em dados. Fui encarregado como analista de dados júnior de analisar os dados de uso de um concorrente (FitBit) para descobrir como os consumidores estão usando seus dispositivos e o que isso pode revelar para a Bellabeat.

**Pergunta Principal:** Quais são as tendências de uso dos dispositivos de fitness e como elas podem influenciar a estratégia de marketing da Bellabeat?

## 3. Estrutura do Repositório

Este projeto está organizado em pastas para facilitar a navegação e a reprodutibilidade da análise:

-   `📁 01_Metadados`: Contém a documentação sobre os conjuntos de dados, dicionários de variáveis e outras informações contextuais.
-   `📁 02_Datas`: Armazena os conjuntos de dados originais (`.csv`) e os dados limpos e processados.
-   `📁 03_Scripts`: Contém todos os scripts em R utilizados para a limpeza, transformação e análise dos dados.
-   `📁 04_Plots`: Guarda todos os gráficos e visualizações gerados durante a análise.
-   `📁 05_Relatorios`: Inclui o relatório final da análise, apresentações e as conclusões (a fase "Compartilhar").

## 4. Ferramentas e Pacotes Utilizados

-   **Linguagem de Programação:** R
-   **IDE:** RStudio
-   **Pacotes Principais (Tidyverse):**
    -   `readr`: Para importação dos dados.
    -   `dplyr`: Para manipulação e transformação dos dados.
    -   `tidyr`: Para organização e limpeza dos dados (formato tidy).
    -   `ggplot2`: Para a criação de visualizações e gráficos.
    -   `lubridate`: Para manipulação de datas e horas.

## 5. Como Reproduzir a Análise

Para executar este projeto em sua máquina local, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/lucasgpec/ProjR01_Bellabeat.git
    ```
2.  **Abra o projeto no RStudio:**
    Navegue até a pasta clonada e abra o arquivo `ProjR01.Rproj`. Isso irá configurar o diretório de trabalho automaticamente.

3.  **Instale as dependências:**
    Execute o comando abaixo no console do RStudio para instalar todos os pacotes necessários.
    ```r
    install.packages(c("tidyverse", "lubridate" ))
    ```
4.  **Execute os Scripts:**
    Abra e execute os scripts localizados na pasta `03_Scripts` na ordem apropriada para reproduzir toda a análise.

## 6. Principais Insights (Exemplo)

*(Esta seção deve ser preenchida com as suas descobertas!)*

-   **Frequência de Uso:** A maioria dos usuários utiliza o dispositivo entre 4 e 6 dias por semana, com uma queda de uso nos fins de semana.
-   **Relação entre Passos e Sono:** Foi observada uma correlação positiva entre o número de passos diários e a qualidade do sono.
-   **Tipos de Atividade:** A atividade mais registrada é a caminhada, representando mais de 80% dos minutos de atividade física.

## 7. Recomendações para a Bellabeat

*(Esta seção deve ser preenchida com suas sugestões baseadas nos insights)*

1.  **Marketing de Engajamento:** Criar campanhas de marketing focadas em manter os usuários ativos durante o fim de semana, como desafios ou recompensas.
2.  **Funcionalidades do App:** Desenvolver notificações no aplicativo Bellabeat que incentivem os usuários a atingirem suas metas de passos para melhorar a qualidade do sono.
3.  **Posicionamento de Produto:** Destacar nos materiais de marketing como os produtos Bellabeat podem ser grandes aliados para atividades cotidianas, como a caminhada.
