# Análise de Conformidade, Risco e Eficiência em EPS de Cobrança (Bradesco)

Projeto de análise de dados aplicado a Speech Analytics, com foco em conformidade regulatória, eficiência operacional e mitigação de riscos financeiros e jurídicos em operações de cobrança.

---

## Contexto
Projeto baseado em experiência prática no acompanhamento do fluxo de dados das EPS de cobrança do Bradesco, envolvendo grandes volumes de ligações, metadados e transcrições de áudio em um ambiente altamente regulado.

---

## Problema
As EPS de cobrança precisam manter aderência mínima de 99,9% entre dados e metadados para evitar penalizações contratuais. Além disso, falhas no atendimento — como direcionamento indevido de clientes para agências e menções a órgãos reguladores — geram alto custo operacional e risco de ajuizamento.

---

## Solução
- Monitoramento do fluxo de dados das EPS (acionamentos, tempos e carteira).  
- Criação de relatórios de aderência entre dados e metadados (áudio, identificadores, data e duração).  
- Análise massiva de transcrições de áudio utilizando Regex para identificação de padrões críticos.  
- Construção de padrões analíticos para classificação de situações sensíveis no atendimento.

---

## Resultados

**Direcionamento Indevido para Agência**  
Identificação de mais de 77.000 ocorrências em três meses. A análise revelou que, em média, seis a cada dez ligações estavam associadas à não localização do contrato pelo operador, gerando alto custo operacional e ineficiência no atendimento.

**Risco Regulatório e Ajuizamento**  
Identificação de mais de 80.000 ocorrências relacionadas a menções ao Banco Central e intenção de processo em quatro meses, permitindo análise comparativa entre EPS com maior exposição a risco regulatório.

---

## Ferramentas Utilizadas
Python, Regex, Excel, Speech Analytics

---

## Impacto
- Mitigação de riscos financeiros, jurídicos e regulatórios.  
- Redução de falhas operacionais no atendimento.  
- Geração de insights estratégicos a partir de dados não estruturados.  
- Suporte à tomada de decisão baseada em dados em ambiente crítico de negócio.
  
## Aprendizados

Durante o desenvolvimento deste projeto e da minha experiência inicial, adquiri aprendizados que vão além do código:

- Qualidade de atendimento e análise de interações, entendendo como pequenas decisões impactam diretamente a experiência do cliente  
- Manipulação e análise de dados em massa, com foco em organização, padronização e extração de informações relevantes  
- Visão de negócio aplicada à tecnologia, compreendendo como processos técnicos influenciam resultados, custos e riscos  
- Entendimento de processos legais e regulatórios, incluindo causas de processos judiciais contra empresas e a importância da conformidade  
- Desenvolvimento de pensamento analítico, atenção a detalhes e responsabilidade na tomada de decisões  
- Evolução na comunicação técnica e na documentação de processos

Esses aprendizados reforçaram minha base profissional e minha capacidade de evoluir tecnicamente com consciência de negócio.

