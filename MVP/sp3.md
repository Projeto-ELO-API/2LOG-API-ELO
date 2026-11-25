# 📌 MVP - Projeto ELO

## 🎯 Objetivo do MVP
- Avaliar o cenário da segurança viária e identificar possíveis regiões com maior riscos de sinistros.
- Criar gráfico para análise mais detalhada permitindo a visualização de sinistros por tipo de veículo e ampliar os filtros. 
- Investigação de incidentes e identificação de fatores críticos (pivôs) em sinistros com motoristas de frota pesada. 
---

## 📝 Descrição da Solução
Ampliação dos filtros no gráfico, permitindo análise mais detalhada em relação aos fatores que pode ser causadores iniciais de sinistros, análise e investigação de pequenas causas que estão diretamente ligadas a atividades de motoristas de veículos pesados que também podem  ser provocadoras de sinistros, com base nos dados  das pesquisas realizadas e extração de dados.

---

## 👥 Personas / Usuários-Alvo
- Analistas de segurança viária, que buscam entender causas/fatores associados a sinistros com veículos pesados no trânsito  
- Analistas de saúde pública que, buscam entender as principais causas de óbitos no país
- Analista de dados,  interessados em visualização de dados logísticos
- Gestores públicos, que buscam dados para melhoria contínua dos setores
- Especialistas do Observatório Nacional, que buscam entender os dados e desenvolver soluções e melhorias no trânsito.
---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US11 |Como Gestor público, quero identificar os estados com maior taxa de letalidade envolvendo veículos pesados, para identificar os locais com maior gravidade nos sinistros.  | Média      | 2 pontos   |
| US12 | Como Analista de segurança viária, quero realizar um cruzamento entre os dados de saúde do DATASUS e os dados de transporte da PRF, para analisar a relação entre sinistros  e a mortalidade.        | Média      | 5 pontos   |
| US13 | Como Analista de segurança viária, quero analisar a variação dos sinistros envolvendo veículos pesados entre as regiões do Brasil, para identificar diferenças regionais na segurança viária.    | Baixa      | 2 pontos   |
| US14 | Como Inspetor do Observatório, quero utilizar filtros no Power BI por tipo de veículo, região, ano e gravidade do sinistro, para realizar análises específicas dos dados. | Média      | 3 pontos   |
| US15 | Como Pesquisador do Observatório, quero que o dashboard desenvolvido no Power BI possua navegação intuitiva e acesso às informações com poucos cliques, para facilitar sua utilização pelos usuários.        | Média      | 2 pontos   |
| US16 | Como Diretor do Observatório, quero que os artefatos do projeto sejam visionados utilizando o GitHub, para manter o histórico e o controle das versões dos arquivos, códigos e os demais materiais desenvolvidos.    | Média      | 3 pontos   |
| US17 | Como Inspetor do Observatório, quero analisar a relação entre o crescimento da frota de veículos pesados e o aumento dos sinistros fatais, para verificar se existe associação entre esses indicadores.     | Média      | 3 pontos   |
| US18 |Como cliente, quero analisar a evolução dos indicadores de segurança viária entre 2015 e 2025, para identificar tendências e mudanças ao longo do período.        | Média      | 3 pontos   |
| US19 | Como Analista de segurança viária, quero visualizar no Power BI os pontos de parada de descanso e a distância entre esses pontos e os locais dos sinistros, para analisar possíveis relações entre infraestrutura de descanso e segurança viária.         | Média      | 3 pontos   |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Integrar dados da PRF e DATASUS                      | Concluído |
| 02     | Criar um banco de dados                           | Concluído |
| 03     | Tratamento de dados                           | Concluído |
| 04     | Criar Dashboard no Power BI            | Concluído |
| 05     | Criar gráficos por tipo                    | Concluído |
| 06     | Listar totais de sinistros, óbitos e veículos       | Concluído |
| 07     | Elaboração de imagem de fundo simples                       | Concluído |
| 08     | Inclusão e modificação de filtros no gráfico                       | Concluído |
| 09     | Realizar pesquisa em transportadoras                       | Concluído |
| 10     | Ampliar os filtros no dashboard Power BI                       | Concluído |
| 11     | Análise de causas-raiz e fatores determinantes de sinistros envolvendo veículos pesados                 | Concluído |
| 12     | Disponibilizar no dashboard a visualização dos pontos de parada de descanso e a distância entre esses pontos e os locais dos sinistros                 | Concluído |
| 13     | Filtrar os dados permitindo a análise de evolução dos indicadores de segurança viária entre 2015 e 2025            | Concluído 

---

## 📊 Critérios de Aceitação
- Dashboard funcional com dados carregados corretamente 
- Visualizações claras (gráficos e tabelas)  
- Presença de filtros (ex: município, ano, tipo - acidente)
- Análise dos dados com base em pesquisas realizadas
- Pesquisa para entender a real situação de estradas da região
- Inclusão e modificação de filtros no gráfico
- Elaboração de novos filtros no gráfico
---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP: 2  
- Clareza na interpretação dos dados (feedback qualitativo) 
- Funcionamento correto dos filtros e interações
---

## 🚀 Próximos Passos
- Pequenas correções
- Publicação do vídeo 
- Apresentação na feira de soluções  

---

## 📂 Anexos / Evidências

<a href="https://www.youtube.com/watch?v=HzqmKhDbvdI" target="_blank">

## Tratamento de dados (Python)
Fase inicial 
<img width="1600" height="673" alt="image" src="https://github.com/user-attachments/assets/9cebab27-f0ca-4769-87b6-4d7a0ad023d5" />

## Concatenação dos dados de 2020 - 2025
<img width="1600" height="422" alt="image" src="https://github.com/user-attachments/assets/91290948-e952-4523-bb8e-dd61683db0d5" /> 

## Visualização da tabela final
<img width="1600" height="694" alt="image" src="https://github.com/user-attachments/assets/68d9b38c-0ac2-4179-8a5f-ce57cff60659" />

## Dashboard-visão geral
[Dashboard-Visão-Geral](https://centropaulasouza-my.sharepoint.com/:u:/r/personal/thiago_miranda01_aluno_cps_sp_gov_br/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fthiago%5Fmiranda01%5Faluno%5Fcps%5Fsp%5Fgov%5Fbr%2FDocuments%2FApi%2FBi%2E2semestre%2Epbix&parent=%2Fpersonal%2Fthiago%5Fmiranda01%5Faluno%5Fcps%5Fsp%5Fgov%5Fbr%2FDocuments%2FApi&share=cQqe8cDmVpQXQ5XyBhWnW22vEgUC6TdrdnVcJThlSoXsTr396g)

<img width="1448" height="813" alt="image" src="https://github.com/user-attachments/assets/c498727f-779e-482c-9b83-eb7b29d2edc1" />

## Análises estatísticas
<img width="1439" height="799" alt="image" src="https://github.com/user-attachments/assets/674a1f28-3ae8-4774-9159-51c11903b3a1" />

## Perfil dos sinistros
<img width="1452" height="810" alt="image" src="https://github.com/user-attachments/assets/51072f72-7c86-433b-bfea-8ef3dbebbfbc" />


## Dashboard-Segurança-viária
[Dashboard-Segurança-Viária](https://centropaulasouza-my.sharepoint.com/:u:/r/personal/caio_souza16_aluno_cps_sp_gov_br/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fcaio%5Fsouza16%5Faluno%5Fcps%5Fsp%5Fgov%5Fbr%2FDocuments%2FAnexos%2FDASHBOARD%20API%20SEGURAN%C3%87A%20AVIARIA%20NACIONAL%2Epbix&parent=%2Fpersonal%2Fcaio%5Fsouza16%5Faluno%5Fcps%5Fsp%5Fgov%5Fbr%2FDocuments%2FAnexos&share=cQpFE%2DRvm8r0SaRt%5FqbRWIQDEgUCE4qlegek03vV5h1p8oU1Ag)

<img width="890" height="500" alt="image" src="https://github.com/user-attachments/assets/28f17efe-bf60-46a8-962e-eceb90f4d56b" />

## PACER
<img width="995" height="580" alt="image" src="https://github.com/user-attachments/assets/0f6e1a2f-f776-4e8c-ac93-c28036a0bd16" />

