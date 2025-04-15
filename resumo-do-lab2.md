# 📘 Resumo de Lições Aprendidas - Lab DIO: Computação em Nuvem

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do laboratório da DIO, com foco em conceitos essenciais da computação em nuvem. Um dos principais tópicos abordados foi o SLA (Service Level Agreement), ou Acordo de Nível de Serviço.

---

## 🔐 O que é SLA?

O **SLA (Service Level Agreement)** é um contrato formal que define os níveis de serviço acordados entre um **provedor de serviços** (como um provedor de nuvem) e o **cliente**. Um dos aspectos mais críticos em um SLA é a **garantia de disponibilidade**, normalmente expressa em porcentagens.

Essa disponibilidade determina quanto tempo o serviço pode ficar **fora do ar** por ano, conforme demonstrado abaixo:

---

## 📊 Níveis de SLA e Tempo Máximo de Inatividade

| SLA (%)     | Tempo de Inatividade por Ano | Uso Típico |
|-------------|-------------------------------|------------|
| **99%**     | ~87,6 horas (3,65 dias)       | Serviços menos críticos com maior tolerância à interrupção |
| **99.9%**   | ~8,76 horas                   | Aplicações importantes com certa tolerância a falhas |
| **99.99%**  | ~52,56 minutos                | Sistemas críticos, como e-commerces |
| **99.999%** | ~5,26 minutos                 | Ambientes extremamente críticos (financeiro, saúde) |

---

## ⚙️ Considerações Importantes sobre SLAs

- **💸 Custo**: Quanto maior a disponibilidade garantida, maior o custo. Isso ocorre devido à necessidade de infraestrutura redundante e monitoramento avançado.
  
- **🏗️ Arquitetura de Resiliência**:
  - Redundância de servidores e recursos
  - Failover automático
  - Replicação geográfica de dados

- **⚠️ Penalidades e Compensações**:
  - Muitos contratos SLA preveem **créditos** ou **reembolsos** caso o provedor não atinja o nível acordado.

---

## ✅ Conclusão

Ao escolher um SLA, é fundamental **balancear custo e necessidade de disponibilidade**. Aplicações críticas exigem níveis elevados de SLA, enquanto serviços internos ou não essenciais podem operar com níveis mais baixos e menos custos.

---

📎 *Este documento é parte do conteúdo aprendido no Lab de Computação em Nuvem da DIO.*

