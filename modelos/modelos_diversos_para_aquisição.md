# 📘 Aquisições de Hardware & Software  
### Diretrizes, Modelos e Procedimentos para as Secretarias da Prefeitura de Hortolândia

---

## 📑 Sumário

- [1. Introdução](#1-introdução)  
- [2. Objetivos](#2-objetivos)  
- [3. Princípios Gerais](#3-princípios-gerais)  
- [4. Escopo das Aquisições](#4-escopo-das-aquisições)  
- [5. Fluxo Padronizado de Solicitação](#5-fluxo-padronizado-de-solicitação)  
- [6. Guia Prático – Como uma Secretaria Executa a Compra de Software](#6-guia-prático--como-uma-secretaria-executa-a-compra-de-software)  
- [7. Checklist Técnico – Hardware](#7-checklist-técnico--hardware)  
- [8. Checklist Técnico – Software](#8-checklist-técnico--software)  
- [9. Modelos Técnicos e Formulários](#9-modelos-técnicos-e-formulários)  
- [10. Critérios Técnicos de Avaliação](#10-critérios-técnicos-de-avaliação)  
- [11. Riscos e Mitigações](#11-riscos-e-mitigações)  
- [12. Responsabilidades](#12-responsabilidades)  
- [13. Estrutura de Diretórios no GitHub](#13-estrutura-de-diretórios-no-github)  
- [14. Referências Bibliográficas](#14-referências-bibliográficas)

---

## 1. Introdução
A aquisição de hardware e software na Administração Pública Municipal exige critérios rigorosos de padronização, segurança, rastreabilidade e conformidade, conforme a Lei nº 14.133/2021 e práticas consolidadas de governança (COBIT, ITIL, ISO 27001).  
Este documento orienta as Secretarias na formalização, análise, contratação e homologação de itens de TI, sempre com validação técnica obrigatória do DITI.

---

## 2. Objetivos
- Padronizar aquisições de TI.  
- Garantir conformidade legal e técnica.  
- Prevenir compras redundantes ou obsoletas.  
- Aumentar segurança da informação e interoperabilidade.  
- Estabelecer fluxo claro para Secretarias não técnicas.  

---

## 3. Princípios Gerais
1. Adequação técnica  
2. Segurança e LGPD  
3. Ciclo de Vida e TCO  
4. Eficiência  
5. Rastreabilidade  
6. Sustentabilidade  

---

## 4. Escopo das Aquisições
| Categoria | Exemplos |
|----------|----------|
| **Hardware** | notebooks, desktops, servidores, switches |
| **Software** | antivírus, ERP, BI, sistemas setoriais |
| **Serviços** | suporte, instalação, migração |
| **Infraestrutura** | monitores, nobreaks, cabos |

---

## 5. Fluxo Padronizado de Solicitação
1. Secretaria identifica necessidade e preenche o formulário.  
2. DITI avalia compatibilidade, segurança e necessidade.  
3. DITI emite parecer técnico.  
4. Secretaria monta dossiê e envia à CPL.  
5. CPL conduz licitação conforme Lei 14.133/2021.  
6. DITI avalia propostas.  
7. CPL adjudica e contrata.  
8. Fornecedor entrega → DITI homologa tecnicamente → Secretaria valida operacionalmente.  

---

## 6. Guia Prático – Como uma Secretaria Executa a Compra de Software

### 6.1 Início da Demanda (Secretaria)
A Secretaria deve:

- Preencher o formulário oficial:  
  `/aquisições/formularios/requerimento_aquisicao.md`
- Descrever necessidade, impacto, quantidade de usuários e urgência.
- Não solicitar marcas específicas.  
- Não iniciar compra sem parecer do DITI.

---

### 6.2 Encaminhamento ao DITI
DITI avalia:

- compatibilidade técnica,  
- LGPD e segurança,  
- duplicidade com sistemas existentes,  
- impacto na infraestrutura.

Resultado: **Parecer Técnico**  
Modelos em: `/aquisições/pareceres/parecer_padrao.md`

---

### 6.3 Validação da Especificação
DITI define requisitos mínimos, critérios técnicos e parâmetros de segurança.  
Esse documento é anexado ao processo de compra.

---

### 6.4 Preparação do Dossiê para Compras/CPL  
A Secretaria reúne:

- Formulário oficial  
- Parecer Técnico  
- Especificação técnica  
- Justificativa  
- Declaração LGPD (se houver dados pessoais)  

---

### 6.5 Processo Licitatório (CPL / Compras)
CPL:

- define modalidade,  
- publica atos,  
- analisa documentação,  
- julga propostas com apoio técnico do DITI.

---

### 6.6 Análise de Propostas (DITI)
DITI verifica:

- aderência técnica,  
- requisitos de segurança,  
- interoperabilidade,  
- viabilidade da solução.

---

### 6.7 Contratação e Assinatura
CPL formaliza adjudicação e homologação.  
DITI valida tecnicamente o contrato.  
Secretaria é a usuária da solução.

---

### 6.8 Entrega, Testes e Homologação
Fornecedor entrega o software e documentação.  
DITI realiza testes técnicos.  
Secretaria testa usabilidade.  
Somente após isso: **Homologação Final**.

---

### 6.9 Inventário de Software
DITI registra licenças, versões, prazos e responsáveis.  
Secretarias devem comunicar alterações de uso.

---

### 6.10 Restrições Importantes
É proibido:

- contratar software sem parecer do DITI,  
- usar software sem licença,  
- contratar sistemas que não registram logs,  
- adotar soluções sem conformidade LGPD,  
- contratar soluções críticas sem análise.

---

## 7. Checklist Técnico – Hardware
- Especificação compatível  
- Garantia mínima 12 meses (preferencial 36)  
- Eficiência energética  
- Peças disponíveis  
- Segurança e compatibilidade  

---

## 8. Checklist Técnico – Software
- Licenciamento adequado  
- Auditoria e logs  
- LGPD e ISO 27001  
- Compatibilidade com sistemas  
- Documentação técnica  
- SLA mínimo estabelecido  

---

## 9. Modelos Técnicos e Formulários

## 9. Modelos Técnicos e Formulários

### 9.1 Modelo de Notebook
Processador: i5 ou Ryzen 5
RAM: 16 GB
SSD: 512 GB
Tela: 15.6” FHD
Garantia: 36 meses

shell
Copiar código

### 9.2 Modelo de Antivírus (EDR)
Endpoints: 200+
Console centralizado
Sandbox e análise comportamental
LGPD e ISO 27001
SLA: 99,5%

shell
Copiar código

### 9.3 Formulário Oficial
Requerimento de Aquisição
Descrição da demanda
Justificativa
Sistemas afetados
Urgência

shell
Copiar código

### 9.4 Parecer Técnico
Compatibilidade
Justificativa técnica
Impacto na infraestrutura
Conclusão (aprovado / com ajustes / negado)

---

## 10. Critérios Técnicos de Avaliação
- Benchmarks e desempenho  
- Maturidade do fornecedor  
- SLA e suporte  
- Segurança e hardening  
- Roadmap de atualizações  
- Interoperabilidade e integração com data center  

---

## 11. Riscos e Mitigações

| Risco | Mitigação |
|-------|-----------|
| Obsolescência | Catálogo homologado |
| Incompatibilidade | Parecer técnico obrigatório |
| Vulnerabilidades | LGPD + ISO 27001 |
| Subdimensionamento | Plano de Capacidade |
| Licenciamento errado | Validação do DITI |

---

## 12. Responsabilidades

### Secretarias
- Preencher formulário  
- Justificar a demanda  
- Fornecer informações operacionais  
- Seguir o fluxo definido  

### DITI
- Emitir parecer técnico  
- Homologar entregas  
- Definir catálogo e padrões  
- Garantir segurança e conformidade  

### CPL
- Conduzir licitação  
- Validar documentação  
- Formalizar contratos  

---

## 13. Estrutura de Diretórios no GitHub


/aquisições/
/aquisições/modelos/
/aquisições/formularios/
/aquisições/pareceres/
/aquisições/bibliografia/


---

## 14. Referências Bibliográficas
- Lei nº 14.133/2021  
- Lei nº 13.709/2018 (LGPD)  
- COBIT 2019  
- ISO/IEC 27001:2022  
- ITIL v4  
- Guia de Contratações de TIC – Ministério da Economia  







