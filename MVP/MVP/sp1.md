# 📌 MVP - AMPORT 

## 🎯 Objetivo do MVP
> Entregar a primeira versão funcional do dashboard, permitindo visualização inicial dos indicadores essenciais.  
- **Problema que resolve:** ausência de uma visão consolidada dos dados de portuários.
- **Hipótese:** dashboards simples já ajudam gestores a enxergarem padrões relevantes.  
- **Valor entregue:** visualização centralizada com dados limpos e estruturados.

---

## 📝 Descrição da Solução
> Construção da base inicial e criação dos primeiros elementos de interface.  
- **Funcionalidades incluídas:**  
  - Estrutura base do painel  
  - Visualização inicial dos dados  
  - Conexão preliminar com as bases utilizadas  
- **Limitações:** gráficos ainda não interativos, filtros limitados.  
- **Escopo reduzido:** foco apenas na criação da fundação do dashboard.

---

## 👥 Personas / Usuários-Alvo
- **Persona 1: Gestor Portuário**  
  - Dores: falta de dados organizados; relatórios demorados.  

- **Persona 2: Analista de Dados**  
  - Dores: necessidade de entender estrutura inicial para evoluir análises.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story | Prioridade | Estimativa |
|-----|------------|------------|------------|
| US1 | Como desenvolvedor, quero realizar a extração e limpeza dos dados da ANTAQ via Python para garantir a integridade da base. | Alta | 5 pontos |
| US2 | Como analista, quero visualizar o tempo médio de espera e operação por porto para identificar gargalos logísticos. | Alta | 8 pontos |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais | Status |
|--------|----------------------|--------|
| 01     | Estrutura inicial do painel | Concluído |
---

## 📊 Critérios de Aceitação
- Extração Robusta: O script Python (Google Colab) deve acessar o Portal da ANTAQ e tratar falhas de conexão ou mudanças na estrutura do site.
- Integridade Total: A base de dados não deve conter duplicatas de portos causadas por erros de digitação (normalização de strings).
- Visualização Funcional: O dashboard deve permitir distinguir claramente o "Tempo de Espera" (fora do porto) do "Tempo de Operação" (no berço).
- Identificação de Gargalos: Deve ser possível identificar qual porto tem o maior desvio em relação à média de tempo de processamento da região.

---

## 📈 Métricas de Validação

- Qualidade da Base: Percentual de dados inconsistentes ou nulos após a limpeza (Meta: < 2%).
- Performance de Processamento: Tempo que o script leva para atualizar o dashboard após a extração.
- Clareza Visual: Avaliação do analista sobre a facilidade de identificar um gargalo em menos de 10 segundos ao olhar o mapa/gráfico.
---

## 🚀 Próximos Passos
- Adicionar novos indicadores  
- Desenvolver interatividade  
- Criar filtros dinâmicos

---

## 📂 Anexos / Evidências
[Assista ao vídeo no YouTube](x)

