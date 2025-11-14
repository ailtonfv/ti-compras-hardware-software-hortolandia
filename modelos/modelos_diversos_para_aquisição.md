# 📘 Aquisições de Hardware e Software  
**Diretrizes, Modelos e Procedimentos para as Secretarias da Prefeitura de Hortolândia**

---

## 📑 Sumário
1. Introdução  
2. Objetivos  
3. Princípios Gerais  
4. Escopo das Aquisições  
5. Competências e Limites da TI (DITI e DSTI)  
6. Fluxo Padronizado de Solicitação  
7. Guia Prático – Como uma Secretaria Executa a Compra de Software  
8. Checklist Técnico – Hardware  
9. Checklist Técnico – Software  
10. Modelos Técnicos e Formulários  
11. Critérios Técnicos de Avaliação  
12. Riscos e Mitigações  
13. Responsabilidades  
14. Estrutura de Diretórios no GitHub  
15. Siglas (aprox. 100 itens)  
16. Referências Bibliográficas  

---

# 1. Introdução
A aquisição de hardware e software na Administração Pública Municipal exige critérios rigorosos de padronização, segurança, rastreabilidade e conformidade, conforme a Lei nº 14.133/2021 e práticas consolidadas de governança (COBIT, ITIL, ISO 27001).  

Este documento orienta todas as Secretarias — inclusive não técnicas — na formalização, instrução, contratação e homologação de itens de Tecnologia da Informação, sempre com **validação técnica prévia** pelo DITI e pelo DSTI, conforme suas competências.

---

# 2. Objetivos
- Padronizar aquisições de TI.  
- Garantir conformidade legal e técnica.  
- Prevenir compras redundantes ou incompatíveis.  
- Aumentar segurança da informação e interoperabilidade.  
- Estabelecer fluxo claro e objetivo para Secretarias não técnicas.  
- Evitar decisões que comprometam continuidade operacional.  

---

# 3. Princípios Gerais
1. **Adequação técnica**  
2. **Segurança da informação e LGPD**  
3. **Ciclo de vida e TCO (Custo Total de Propriedade)**  
4. **Eficiência e economicidade**  
5. **Rastreabilidade e auditoria**  
6. **Sustentabilidade e padronização**  

---

# 4. Escopo das Aquisições

| Categoria | Exemplos |
|----------|----------|
| **Hardware** | notebooks, desktops, servidores, switches, nobreaks |
| **Software** | antivírus, ERP, BI, sistemas setoriais, licenças |
| **Serviços** | instalação, migração, suporte, treinamento |
| **Infraestrutura** | monitores, racks, cabeamento, pontos de rede |

---

# 5. Competências e Limites da TI (DITI e DSTI)

A estrutura de TI da Prefeitura é composta por dois departamentos distintos, cada um com competências específicas:

### **DITI – Departamento de Infraestrutura em Tecnologia da Informação**
Responsável por:
- rede lógica, conectividade, servidores, nuvem;  
- segurança da informação e LGPD técnica;  
- inventário de hardware;  
- suporte técnico e manutenção;  
- infraestrutura física e lógica.  

### **DSTI – Departamento de Sistemas em Tecnologia da Informação**
Responsável por:
- desenvolvimento e manutenção de sistemas;  
- banco de dados;  
- APIs, integrações e interoperabilidade;  
- ciência da computação aplicada;  
- geoprocessamento;  
- inovação e qualidade de software.  

### ⚠️ **Limites institucionais**
Para evitar interpretações equivocadas:

**DITI e DSTI NÃO possuem competência legal para aprovar compras públicas.**  
A aprovação compete à:
- Secretaria demandante,  
- Comissão Permanente de Licitação (CPL),  
- Secretaria de Finanças (orçamento),  
- Autoridade competente designada.

O papel da TI é **estritamente técnico**, nos seguintes termos:
- emissão de parecer técnico;  
- definição de requisitos mínimos;  
- avaliação de riscos;  
- validação de compatibilidade e segurança;  
- homologação técnica da entrega.

---

# 6. Fluxo Padronizado de Solicitação
1. Secretaria identifica necessidade e preenche formulário oficial.  
2. Secretaria envia ao DITI/DSTI para análise técnica.  
3. TI emite parecer técnico e valida requisitos.  
4. Secretaria monta dossiê e envia à CPL.  
5. CPL conduz licitação conforme Lei 14.133/2021.  
6. DITI/DSTI avaliam as propostas tecnicamente.  
7. CPL adjudica e contrata.  
8. Fornecedor entrega → DITI/DSTI homologam tecnicamente → Secretaria valida operacionalmente.  

---

# 7. Guia Prático – Como uma Secretaria Executa a Compra de Software

## 7.1 Início da Demanda (Secretaria)
A Secretaria deve:

- Preencher o formulário oficial:  
  `/aquisições/formularios/requerimento_aquisicao.md`
- Descrever necessidade, impacto, quantidade de usuários, urgência.
- Não solicitar marcas específicas.  
- Não iniciar processo sem parecer do DITI/DSTI.

---

## 7.2 Encaminhamento ao DITI/DSTI
A área técnica avalia:

- compatibilidade com sistemas existentes;  
- requisitos de LGPD e segurança;  
- necessidade de logs e auditoria;  
- impacto em infraestrutura;  
- duplicidade com soluções já contratadas.  

Modelo de parecer técnico:  
`/aquisições/pareceres/parecer_padrao.md`

---

## 7.3 Validação da Especificação
DITI/DSTI definem:
- requisitos mínimos obrigatórios;  
- critérios técnicos de julgamento;  
- parâmetros de desempenho;  
- requisitos de segurança.

---

## 7.4 Dossiê para Compras/CPL
A Secretaria reúne:

- Formulário oficial  
- Parecer técnico  
- Especificação técnica validada  
- Justificativa  
- Declaração LGPD (se aplicável)  

---

## 7.5 Processo Licitatório (CPL)
CPL:

- define modalidade;  
- analisa documentação;  
- consulta TI quando necessário;  
- publica atos;  
- conduz julgamento técnico/objetivo.  

---

## 7.6 Análise de Propostas (DITI/DSTI)
TI verifica:

- aderência aos requisitos;  
- segurança da informação;  
- escalabilidade;  
- capacidade de integração;  
- riscos técnicos.  

---

## 7.7 Contratação e Assinatura
- CPL adjudica e homologa.  
- TI valida tecnicamente o contrato.  
- Secretaria demandante assina como usuária.  

---

## 7.8 Entrega, Testes e Homologação
Fornecedor entrega software, licenças e documentação.  
DITI/DSTI realizam testes técnicos.  
Secretaria realiza testes de operação.  
Somente após isso: **Homologação Final**.

---

## 7.9 Inventário de Software
DITI registra licenças, versões e prazos.  
Secretarias comunicam alterações.  

---

## 7.10 Restrições Importantes
É proibido:

- contratar software sem parecer técnico;  
- usar software sem licença;  
- contratar sistemas sem logs ou auditoria;  
- adotar software fora da LGPD;  
- contratar soluções críticas sem TI.  

---

# 8. Checklist Técnico – Hardware
- Especificação compatível  
- Garantia mínima 12 meses (preferencial 36)  
- Eficiência energética  
- Peças disponíveis  
- Segurança e compatibilidade  
- Atendimento a catálogo de TI  

---

# 9. Checklist Técnico – Software
- Licenciamento regular  
- Auditoria e logs  
- Aderência à LGPD  
- Compatibilidade com sistemas internos  
- Documentação técnica  
- SLA mínimo de suporte  

---

# 10. Modelos Técnicos e Formulários

## 10.1 Modelo de Notebook
Processador: Intel i5 / Ryzen 5
RAM: 16 GB
SSD: 512 GB
Tela: 15.6’’ Full HD
Garantia: 36 meses

shell
Copiar código

## 10.2 Modelo de Antivírus (EDR)
Console centralizado
Sandbox
Resposta automatizada
LGPD e ISO 27001
Cobertura mínima: 200 endpoints

shell
Copiar código

## 10.3 Formulário Oficial
Requerimento de Aquisição
Descrição da Demanda
Justificativa
Sistemas Afetados
Urgência e Impacto

shell
Copiar código

## 10.4 Parecer Técnico
Compatibilidade
Justificativa Técnica
Impacto na Infraestrutura
Conclusão (Aprovado / Ajustes / Não Aprovado)

yaml
Copiar código

---

# 11. Critérios Técnicos de Avaliação
- Benchmarks  
- Maturidade do fornecedor  
- Segurança da informação  
- SLA e suporte  
- Roadmap de atualizações  
- Interoperabilidade  

---

# 12. Riscos e Mitigações

| Risco | Mitigação |
|-------|-----------|
| Obsolescência | Catálogo homologado |
| Incompatibilidade | Parecer técnico obrigatório |
| Vulnerabilidades | LGPD + ISO 27001 |
| Subdimensionamento | Plano de capacidade |
| Licenciamento incorreto | Validação do DITI |

---

# 13. Responsabilidades

### Secretarias
- Preencher formulário  
- Justificar demanda  
- Prover informações  
- Seguir o fluxo  

### DITI
- Emite parecer técnico  
- Homologa entregas  
- Mantém padrões e catálogo  
- Garante segurança  

### DSTI
- Valida sistemas, API, banco de dados  
- Testa integrações  
- Garante aderência técnica  

### CPL
- Conduz licitação  
- Valida documentação  
- Formaliza contratação  

---

# 14. Estrutura de Diretórios no GitHub
/aquisições/
/aquisições/modelos/
/aquisições/formularios/
/aquisições/pareceres/
/aquisições/bibliografia/

yaml
Copiar código

---

# 15. Siglas (aproximadamente 100 itens)

ABNT – Associação Brasileira de Normas Técnicas
AC – Autoridade Competente
AD – Active Directory
API – Application Programming Interface
ARP – Address Resolution Protocol
AWS – Amazon Web Services
BD – Banco de Dados
BI – Business Intelligence
BID – Banco Interamericano de Desenvolvimento
BIOS – Basic Input/Output System
BYOD – Bring Your Own Device
CA – Certificado de Autenticidade
CAPEX – Capital Expenditure
CFTV – Circuito Fechado de TV
CIO – Chief Information Officer
CLOUD – Computação em Nuvem
CMDB – Configuration Management Database
COBIT – Control Objectives for Information and Related Technologies
CPU – Central Processing Unit
CPL – Comissão Permanente de Licitação
CSV – Comma-Separated Values
DBA – Database Administrator
DDR – Double Data Rate (memória RAM)
DevOps – Development and Operations
DITI – Departamento de Infraestrutura em Tecnologia da Informação
DNS – Domain Name System
DRP – Disaster Recovery Plan
DSP – Divisão de Suporte e Manutenção
DSTI – Departamento de Sistemas em Tecnologia da Informação
EDR – Endpoint Detection and Response
ERP – Enterprise Resource Planning
FAQ – Frequently Asked Questions
FQDN – Fully Qualified Domain Name
FTP – File Transfer Protocol
GD – Gestão de Demandas
GDPR – General Data Protection Regulation
GIS – Geographic Information System
GPU – Graphics Processing Unit
HDMI – High-Definition Multimedia Interface
HTTP – Hypertext Transfer Protocol
HTTPS – Hypertext Transfer Protocol Secure
IAM – Identity and Access Management
IA – Inteligência Artificial
ICMP – Internet Control Message Protocol
IDS – Intrusion Detection System
IP – Internet Protocol
IPS – Intrusion Prevention System
ISO – International Organization for Standardization
ITAM – IT Asset Management
ITIL – Information Technology Infrastructure Library
KPI – Key Performance Indicator
LAN – Local Area Network
LDAP – Lightweight Directory Access Protocol
LGPD – Lei Geral de Proteção de Dados
MDM – Mobile Device Management
MFA – Multi-Factor Authentication
NAT – Network Address Translation
NDA – Non-Disclosure Agreement
NTP – Network Time Protocol
OS – Operating System
PaaS – Platform as a Service
PCI – Peripheral Component Interconnect
PDF – Portable Document Format
PDTI – Plano Diretor de Tecnologia da Informação
PMBOK – Project Management Body of Knowledge
POC – Proof of Concept
QoS – Quality of Service
RAID – Redundant Array of Independent Disks
RAM – Random Access Memory
RDP – Remote Desktop Protocol
REST – Representational State Transfer
RFQ – Request for Quotation
RFP – Request for Proposal
RGPD – Regulamento Geral de Proteção de Dados
SaaS – Software as a Service
SAN – Storage Area Network
SAP – Systems, Applications and Products
SCP – Secure Copy Protocol
SDK – Software Development Kit
SEGINFO – Segurança da Informação
SIEM – Security Information and Event Management
SLA – Service Level Agreement
SMPUGE – Secretaria Municipal de Planejamento Urbano e Gestão Estratégica
SQL – Structured Query Language
SSH – Secure Shell
SSL – Secure Sockets Layer
SUAS – Sistema Único de Assistência Social
TCP/IP – Transmission Control Protocol / Internet Protocol
TI – Tecnologia da Informação
TIC – Tecnologia da Informação e Comunicação
TCO – Total Cost of Ownership
UDP – User Datagram Protocol
UPS – Uninterruptible Power Supply
URL – Uniform Resource Locator
VPN – Virtual Private Network
VS Code – Visual Studio Code
WAN – Wide Area Network
XML – Extensible Markup Language
YAML – YAML Ain't Markup Language

yaml
Copiar código

---

# 16. Referências Bibliográficas
- Lei nº 14.133/2021  
- Lei nº 13.709/2018 (LGPD)  
- COBIT 2019  
- ISO/IEC 27001:2022  
- ITIL v4  
- Guia de Contratações de TIC – Ministério da Economia  



