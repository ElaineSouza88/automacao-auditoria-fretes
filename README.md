# Estudo de Caso: Automação Inteligente de Auditoria de Fretes 🚀

## 📋 Cenário e Dor de Negócio
No cenário logístico tradicional, a conferência de Conhecimentos de Transporte Eletrônicos (CT-es) costuma ser um grande gargalo operacional. O processo analítico manual gera lentidão, erros de digitação humana e atrasos na liberação de faturas para pagamento. 

O objetivo deste projeto foi desenhar uma solução inteligente que automatize a aprovação de documentos fiscais com base em regras de tolerância parametrizáveis, otimizando o fluxo logístico e garantindo a acurácia financeira.

---

## 🏗️ Engenharia de Requisitos & Entregáveis
Como Analista de Requisitos, estruturei a solução focando na clareza lógica para o time de desenvolvimento e aderência às regras de negócio. Os principais entregáveis documentados incluem:

* **Documento de Requisitos de Negócio (BRD):** Mapeamento detalhado das regras de aceitação automática de fretes.
* **Margens de Tolerância:** Definição de critérios de aprovação via faixas percentuais e valores fixos de desvio aceitável.
* **Fluxos de Exceção:** Tratamento de divergências e regras de contestação junto ao transportador em caso de rejeição automática.

---

## 🗺️ Modelagem de Processos (BPMN)
Para garantir que a tecnologia sirva fielmente à eficiência operacional, fiz a modelagem da árvore de decisão do motor de auditoria utilizando a notação BPMN. O fluxo abrange:
1. Recepção do documento fiscal.
2. Batimento automatizado com a tabela contratada.
3. Validação de margem de tolerância.
4. Direcionamento para workflow de aprovação (ou reprovação) automática ou tratativa manual de ocorrências.

---

## 📈 Backlog de Melhorias Futuras (Visão de Produto)
Durante o ciclo de validação e refinamento do projeto, identifiquei oportunidades estratégicas para elevar a segurança e governança da aplicação:

- [ ] **Implementação de Trava de Valor Fixo (Cap):** Aplicação de um limite monetário máximo sobre as margens percentuais para blindar a operação contra exposições financeiras indesejadas em fretes de alto valor unitário.
- [ ] **Workflows Automatizados de Contestação:** Regras de interação direta com portais de transportadores para agilizar o aceite de divergências de valores.
- [ ] **Painel de Desempenho de Acurácia (KPIs):** Indicadores analíticos para monitorar o índice de erros por parceiro logístico.

---

## 🛠️ Competências Aplicadas
* Engenharia de Requisitos (BRD / User Stories)
* Modelagem de Processos de Negócio (BPMN)
* Visão de Produto e Gestão de Backlog (PO)
* Domínio de Regras de Negócio de Transportes (TMS)

  [🔙 Voltar ao Perfil](https://github.com/ElaineSouza88)
