# Relatório de Análise de Dados: Insights para a Estratégia Bellabeat

![Bellabeat](https://bellabeat.com/) 
  
## 1. Visão Geral do Projeto
  
Este é um projeto de análise de dados para o portfólio de Ciência de Dados, focado em um estudo de caso da **Bellabeat**, uma empresa de tecnologia de bem-estar. O objetivo é analisar dados de uso de dispositivos fitness para identificar tendências e obter insights que possam guiar a estratégia de marketing da empresa.

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

-   **Correlação Positiva entre Passos e Calorias Queimadas:** Uma relação clara onde o aumento da atividade (passos) leva a um maior gasto calórico. Esta é uma tendência fundamental para motivar usuários a se manterem ativos.
-   **Padrões de Atividade Variam ao Longo da Semana:** A atividade dos usuários não é constante, apresentando flutuações com dias de maior e menor engajamento. Isso sugere oportunidades para intervenções direcionadas.
-   **Importância do Sono para o Bem-Estar Geral::** Os dados de sono revelam padrões diversos, e a qualidade do sono é um fator crítico que pode influenciar os níveis de energia e atividade do dia seguinte.
-   **Diferentes Perfis de Usuários:** A segmentação dos usuários por nível de atividade (Sedentários, Levemente Ativos, Ativos Moderados, Muito Ativos) demonstra que existem comportamentos e necessidades distintas, exigindo abordagens personalizadas.

## 7. Aplicação dos Insights ao Bellabeat Leaf

O Bellabeat Leaf, como um monitor de atividade, sono e estresse, está perfeitamente posicionado para capitalizar sobre essas tendências:

1.  **Motivação por Resultados:** Usuárias do Leaf podem ser motivadas ao verem a quantificação direta da queima calórica associada aos seus passos, incentivando a manutenção ou aumento da atividade.
2.  **Incentivo em Dias de Baixa Atividade:** O Leaf pode enviar lembretes e sugestões de atividades leves em dias onde o engajamento tende a ser menor, ajudando as usuárias a manterem a consistência.
3.  **Otimização do Sono:** Ao monitorar o sono, o Leaf permite que as usuárias compreendam seus padrões e recebam dicas personalizadas para melhorar a qualidade do descanso, impactando positivamente sua energia diária.
4.  **Experiência Personalizada::** A segmentação de usuários permite que o aplicativo Bellabeat e o Leaf ofereçam recomendações e metas adaptadas ao perfil de atividade de cada usuária, tornando a experiência mais relevante e eficaz.

## 8. Recomendações para a Estratégia de Marketing da Bellabeat

1. **Campanhas Focadas em Benefícios Tangíveis:** Destacar como o Leaf quantifica o esforço (passos, calorias) e os benefícios diretos para a saúde e bem-estar. Criar desafios de "passos diários" com recompensas virtuais no aplicativo.
2. **Marketing Contextualizado por Dia da Semana:** Desenvolver campanhas específicas para fins de semana, promovendo atividades leves e relaxantes. Enviar lembretes personalizados para incentivar a atividade em dias de menor engajamento.
3. **Ênfase na Qualidade do Sono:** Campanhas que eduquem sobre a importância do sono e como o Leaf auxilia no monitoramento e melhoria dos hábitos de sono, oferecendo dicas de higiene do sono e meditações guiadas.
4. **Segmentação de Mensagens:** Adaptar a comunicação de marketing aos diferentes perfis de usuários. Para usuárias mais sedentárias, focar nos benefícios da atividade gradual; para as mais ativas, em otimização de desempenho e recuperação.

## 9. Conclusão

Este projeto demonstra o poder da análise de dados de dispositivos inteligentes para gerar insights acionáveis. As tendências identificadas fornecem uma base sólida para a Bellabeat refinar sua estratégia de marketing, personalizar a experiência do usuário do Leaf e, em última instância, fortalecer sua posição no mercado de tecnologia de bem-estar. A implementação dessas recomendações pode levar a um maior engajamento do usuário e a um crescimento sustentável para a empresa.



















