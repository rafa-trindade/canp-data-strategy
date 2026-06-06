# CANP - Inteligência de Mercado & Análise de Dados

Case acadêmico/profissional de diagnóstico estratégico para a **Cooperativa CANP**, produtora de Café Especial e Mel Gourmet no Norte do Paraná. O projeto propõe a transformação da gestão da cooperativa de reativa para orientada por dados, estruturado em cinco dimensões analíticas.

🔗 **[Acesse o case publicado](https://rafa-trindade.github.io/cases/canp/)**

---

## Contexto

A CANP registrou aumento expressivo de comentários negativos em redes sociais e marketplaces, concentrados em dois temas: **atrasos nas entregas** e **inconsistências no sabor entre lotes**. A ausência de um sistema integrado de coleta e análise de dados impedia a identificação das causas-raiz e a tomada de decisões proativas.

O diagnóstico desenvolvido integra dados dispersos, mapeia causas-raiz e propõe uma arquitetura de inteligência de mercado adaptada à realidade de uma pequena cooperativa agroindustrial.

---

## Estrutura do Projeto

### 01 · Web Analytics
Plano de coleta e análise de dados digitais, cobrindo:
- Social Listening via Meta Graph API e ferramentas como Mention e Brand24
- Web Scraping de marketplaces (Mercado Livre, Amazon, Elo7) com BeautifulSoup e Scrapy
- Coleta via APIs oficiais (Google Places, Google Analytics 4, INMET/CPTEC)
- Pesquisa de mercado online estruturada em cinco blocos temáticos (perfil, produto, entrega, experiência digital e NPS)
- Análises recomendadas: sentimento, funil de conversão, coorte, cluster e correlação multivariada

### 02 · Data Storytelling
Narrativa analítica seguindo o modelo de cinco atos - **Contexto → Conflito → Evidências → Insights → Recomendação** -, com:
- Inventário de dados por categoria (produção, clima, logística, avaliações, vendas)
- Cadeia de causalidade: clima × qualidade, logística × reclamações, sazonalidade × demanda
- Storyboard com sete visualizações propostas (mapas de calor, dispersão, NPS, sentimento, sazonalidade)
- Recomendações ao conselho gestor: IoT, ETL, rastreabilidade por lote e planejamento de demanda

### 03 · LGPD & Privacidade
Mapeamento de dados, riscos e controles de conformidade:
- Data Mapping de cinco datasets críticos (cooperados, rastreabilidade de mel e café, clientes, clima)
- Análise de riscos por fase do ciclo de vida do dado (coleta, transmissão, armazenamento, uso, descarte)
- Controles técnicos: criptografia TLS/AES-256, RBAC, backup automatizado, substituição de comunicações informais
- Controles administrativos: DPO, Política de Privacidade, DPAs com fornecedores, política de retenção
- Aplicação dos princípios da LGPD: finalidade, necessidade, adequação, prevenção e responsabilização

### 04 · Governança de Dados
Plano de Qualidade de Dados (PQD) com base no framework DAMA-DMBOK:
- Sete dimensões de qualidade aplicadas ao dataset de Colheita de Café: completude, consistência, acurácia, atualidade, unicidade, validade e rastreabilidade
- Checklist de implementação em quatro fases: diagnóstico, limpeza/padronização, validação e monitoramento contínuo
- Definição de Data Owners para os quatro datasets críticos (clima, produção, logística, clientes/reputação)

### 05 · Dashboards - DIOM
Dashboard de Inteligência Operacional e de Mercado com três KPIs estratégicos e semáforos de ação proativa:

| KPI | Fórmula | Verde | Amarelo | Vermelho |
|---|---|---|---|---|
| TCL - Taxa de Conformidade de Lote | (Lotes Conformes / Total) × 100 | ≥ 90% | 75–89% | < 75% |
| OTDR - On-Time Delivery Rate | (Entregas no Prazo / Total Despachados) × 100 | ≥ 95% | 85–94% | < 85% |
| ISD - Índice de Sentimento Digital | (Positivos − Negativos) / Total × 100 | ≥ +40 | +10 a +39 | < +10 |

O DIOM prevê três visões diferenciadas: **Executiva** (diretoria), **Operacional** (produção e logística) e **Mercado** (marketing e atendimento).

---

## Stack & Ferramentas Referenciadas

| Categoria | Tecnologias / Ferramentas |
|---|---|
| Social Listening | Mention, Brand24, Meta Business Suite |
| Web Scraping | Python, BeautifulSoup, Scrapy |
| APIs de Dados | Meta Graph API, Google Places API, GA4, INMET/CPTEC |
| IoT & Conectividade Rural | Sensores LoRaWAN, LPWAN |
| ETL & Automação | n8n, Power Automate |
| BI & Dashboards | Power BI, Google Looker Studio |
| Segurança | TLS/SSL, AES-256, RBAC, 2FA |
| Framework de Dados | DAMA-DMBOK |
| Legislação | LGPD (Lei n.º 13.709/2018) |

---

## Destaques do Case

- Diagnóstico estruturado em cinco dimensões analíticas interdependentes
- Proposta de arquitetura de dados adaptada à realidade rural e de baixa conectividade
- Abordagem de conformidade LGPD aplicada ao contexto de cooperativas agroindustriais
- KPIs com protocolos de ação proativa e limites de decisão definidos
- Roadmap de implementação sem dependência de grandes investimentos em tecnologia

---

## Autor

**Rafael Trindade**
[Portfólio →](https://rafa-trindade.github.io/)

---

*© 2026 Rafael Trindade. Todos os direitos reservados.*
