# Ice – Análise de Vendas de Videogames

Este projeto analisa dados de jogos vendidos pela loja online **Ice**, utilizando informações de avaliações, gêneros, plataformas e vendas históricas para identificar padrões de sucesso e planejar estratégias de marketing.

---

## 🧪 Objetivo

Avaliar fatores que influenciam o sucesso comercial de jogos, incluindo:

- Plataformas mais lucrativas
- Gêneros de maior venda
- Relação entre avaliações de usuários e críticos e vendas
- Diferenças regionais nas vendas

O objetivo é fornecer insights para **planejamento de campanhas publicitárias e previsão de vendas futuras**.

---

## 🔍 Descrição do Projeto

O projeto está dividido em seis etapas principais:

1. **Etapa 1 – Exploração de Dados:**  
   Abrir e inspecionar o arquivo CSV `games.csv` para entender estrutura, colunas e qualidade dos dados.

2. **Etapa 2 – Preparação dos Dados:**  
   - Normalização de nomes de colunas (minúsculas)  
   - Conversão de tipos de dados  
   - Tratamento de valores ausentes e casos “TBD”  
   - Cálculo de vendas globais por jogo (soma de todas as regiões)

3. **Etapa 3 – Análise Exploratória:**  
   - Número de jogos lançados por ano  
   - Distribuição de vendas por plataforma  
   - Identificação de plataformas emergentes e decadentes  
   - Diagramas de caixa de vendas globais por plataforma  
   - Análise da relação entre pontuações de usuários/críticos e vendas  
   - Distribuição de vendas por gênero

4. **Etapa 4 – Perfil de Usuário por Região:**  
   Para cada região (NA, EU, JP):  
   - Cinco plataformas principais e suas quotas de mercado  
   - Cinco gêneros mais populares e lucrativos  
   - Efeito das classificações ESRB nas vendas

5. **Etapa 5 – Teste de Hipóteses:**  
   - Comparar classificações médias de usuários entre Xbox One e PC  
   - Comparar classificações médias de usuários entre gêneros Action e Sports  
   - Definição de hipóteses nula e alternativa  
   - Escolha do nível de significância (*alfa*) e justificativa

6. **Etapa 6 – Conclusão Geral:**  
   Síntese de resultados, insights de plataformas e gêneros lucrativos, recomendações de marketing e planejamento para 2017.

---

## 🚀 Tecnologias Utilizadas

- Python 3.11  
- Pandas, NumPy, Matplotlib, Seaborn  
- Jupyter Notebook  

> Bibliotecas adicionais estão listadas no `requirements.txt`.

---

## 📂 Dataset

Arquivo CSV utilizado:

| Arquivo | Conteúdo |
|---------|----------|
| `games.csv` | Dados de jogos: nome, plataforma, ano de lançamento, gênero, vendas regionais (NA, EU, JP, Other), pontuações de críticos e usuários, classificação ESRB |

---

## 📦 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/rodriguesbrian/tt6_games_project
cd tt6_games_project