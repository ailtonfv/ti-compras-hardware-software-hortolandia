# 📘 Aquisições de Hardware & Software
### Diretrizes, Modelos e Procedimentos para as Secretarias da Prefeitura de Hortolândia  
*(README.md oficial do diretório `aquisições/`)*

---

## 📑 Sumário
- [1. Introdução](#1-introdução)  
- [2. Objetivos](#2-objetivos)  
- [3. Princípios Gerais](#3-princípios-gerais)  
- [4. Escopo das Aquisições](#4-escopo-das-aquisições)  
- [5. Fluxo Padronizado de Solicitação](#5-fluxo-padronizado-de-solicitação)  
- [6. Checklist Técnico – Hardware](#6-checklist-técnico--hardware)  
- [7. Checklist Técnico – Software](#7-checklist-técnico--software)  
- [8. Modelos de Especificações Técnicas](#8-modelos-de-especificações-técnicas)  
- [9. Critérios Técnicos de Avaliação](#9-critérios-técnicos-de-avaliação)  
- [10. Riscos e Mitigações](#10-riscos-e-mitigações)  
- [11. Responsabilidades](#11-responsabilidades)  
- [12. Estrutura de Diretórios no GitHub](#12-estrutura-de-diretórios-no-github)  
- [13. Referências Bibliográficas](#13-referências-bibliográficas)

---

## 1. Introdução
A aquisição de hardware e software na Administração Pública Municipal exige critérios rigorosos de padronização, transparência e segurança, em conformidade com a Lei nº 14.133/2021 e com estruturas consolidadas de governança (COBIT, ITIL, ISO/IEC 27001).  
Este README orienta todas as Secretarias na abertura, justificativa, análise e homologação de demandas de TI, reforçando o papel estratégico do Departamento de Infraestrutura de TI (DITI).

---

## 2. Objetivos
- Assegurar padronização e conformidade legal.  
- Alinhar aquisições ao PDTI e ao parque tecnológico.  
- Reduzir redundâncias e custos desnecessários.  
- Garantir segurança da informação e interoperabilidade.  
- Fortalecer a governança de TI como área estratégica.

---

## 3. Princípios Gerais
1. Adequação técnica e compatibilidade.  
2. Segurança da informação e conformidade com LGPD.  
3. Avaliação de ciclo de vida e custo total de propriedade (TCO).  
4. Eficiência e economicidade.  
5. Documentação e rastreabilidade.  
6. Sustentabilidade e descarte correto.

---

## 4. Escopo das Aquisições
| Categoria | Exemplos |
|----------|----------|
| **Hardware** | desktops, notebooks, servidores, storage, switches, impressoras |
| **Software** | sistemas operacionais, antivírus, produtividade, sistemas setoriais |
| **Serviços** | suporte técnico, instalação, migração, garantia estendida |
| **Infraestrutura** | monitores, nobreaks, cabos, componentes de rede |

---

## 5. Fluxo Padronizado de Solicitação
1. **Abertura da demanda pela Secretaria**  
   - Preenchimento do formulário padrão.  
   - Justificativa do impacto no serviço público.

2. **Análise técnica do DITI**  
   - Estudo de compatibilidade e requisitos.  
   - Avaliação de conformidade com segurança.

3. **Parecer Técnico**  
   - Aprovado, ajustado ou negado.  
   - Indicação de modelos homologados.

4. **Envio à CPL / Compras**  
   - Adequação à Lei nº 14.133/2021.

5. **Entrega e Homologação**  
   - Testes e aceite técnico.  
   - Registro no inventário oficial.

---

## 6. Checklist Técnico – Hardware
- Compatibilidade com sistemas existentes.  
- Configurações alinhadas ao catálogo DITI.  
- Garantia mínima de 12 meses (preferencial 36 meses).  
- Disponibilidade de peças e manutenção.  
- Eficiência energética e certificações.  
- Possibilidade de expansão futura.

---

## 7. Checklist Técnico – Software
- Licenciamento adequado (OEM, volume ou SaaS).  
- Logs e trilhas de auditoria.  
- Conformidade com LGPD.  
- Compatibilidade operacional.  
- Documentação técnica.  
- SLA do fornecedor.

---

## 8. Modelos de Especificações Técnicas

### 8.1 Notebook padrão administrativo
```md
**Equipamento:** Notebook corporativo  
**Processador:** Intel i5 ou Ryzen 5  
**Memória RAM:** 16 GB DDR4  
**Armazenamento:** SSD NVMe 512 GB  
**Tela:** 15.6" FHD  
**Sistema Operacional:** Windows 11 Pro ou Linux Debian  
**Garantia:** 36 meses (on-site)
8.2 Antivírus corporativo
md
Copiar código
**Tipo:** Antivírus corporativo com EDR  
**Licenciamento:** 200+ endpoints  
**Console:** Centralizado  
**Relatórios:** Logs exportáveis  
**Conformidade:** LGPD obrigatória  
**SLA:** 99,5%

## 9. Critérios Técnicos de Avaliação

- Métricas de desempenho relevantes (benchmarks, capacidade de processamento, latência, IOPS).  
- Maturidade do fornecedor (certificações, histórico de estabilidade, presença em Quadrantes do Gartner).  
- SLA formal de atendimento, suporte e atualização.  
- Roadmap de evolução tecnológica disponibilizado pelo fornecedor.  
- Aderência às políticas de segurança da informação (ISO/IEC 27001, NIST, boas práticas de hardening).  
- Integração total com o data center municipal e sistemas já existentes.  
- Garantia de interoperabilidade com sistemas críticos (Educação, Saúde, Inclusão Social, Planejamento etc.).

---

## 10. Riscos e Mitigações

| Risco | Consequência | Mitigação |
|-------|--------------|-----------|
| Obsolescência técnica | Perda de desempenho e aumento de custo | Utilizar catálogo homologado do DITI |
| Incompatibilidade com sistemas | Interrupções e retrabalho | Parecer técnico obrigatório antes da compra |
| Falhas de segurança | Vazamento de dados, indisponibilidade | Checklist LGPD, ISO 27001 e hardening |
| Subdimensionamento | Lentidão, sobrecarga, gargalos | Plano de Capacidade do DITI |
| Licenciamento inadequado | Irregularidade legal | Validação prévia do DITI e Jurídico |
| Falta de documentação | Impossibilidade de auditoria | Registro documental padronizado |

---

## 11. Responsabilidades

### Secretarias Demandantes
- Preencher corretamente o formulário oficial de solicitação.  
- Justificar a necessidade do item e o impacto na política pública.  
- Indicar urgência, prazo e contexto operacional.  
- Encaminhar informações complementares quando solicitadas pelo DITI.

### DITI – Departamento de Infraestrutura de TI
- Realizar análise técnica completa de cada demanda.  
- Emitir parecer técnico formal (aprovado, ajustado ou negado).  
- Homologar especificações técnicas e validar entregas.  
- Atualizar periodicamente o catálogo de hardware e software.  
- Assegurar aderência às normas de segurança da informação e LGPD.

### Compras / CPL
- Conduzir o processo de contratação conforme Lei nº 14.133/2021.  
- Validar documentos enviados para licitação.  
- Registrar atas, contratos e termos de referência.  
- Articular com o DITI eventuais dúvidas técnicas durante o processo.

---

## 12. Estrutura de Diretórios no GitHub

```md
| Diretório / Arquivo | Descrição | Link |
|----------------------|-----------|------|
| `/` | Raiz do repositório | [Abrir](../) |
| `/aquisições/` | Diretório principal deste tema | [Abrir](./) |
| `/aquisições/README.md` | Documento oficial com as diretrizes | [Abrir](./README.md) |
| `/aquisições/modelos/` | Modelos técnicos prontos | [Abrir](./modelos/) |
| `/aquisições/modelos/notebook.md` | Modelo técnico de notebook | [Abrir](./modelos/notebook.md) |
| `/aquisições/modelos/antivirus.md` | Modelo técnico de antivírus | [Abrir](./modelos/antivirus.md) |
| `/aquisições/formularios/` | Formulários padronizados | [Abrir](./formularios/) |
| `/aquisições/formularios/requerimento_aquisicao.md` | Formulário de abertura de demanda | [Abrir](./formularios/requerimento_aquisicao.md) |
| `/aquisições/pareceres/` | Pareceres técnicos emitidos pelo DITI | [Abrir](./pareceres/) |
| `/aquisições/bibliografia/` | Referências e normas utilizadas | [Abrir](./bibliografia/) |
13. Referências Bibliográficas
BRASIL. Lei nº 14.133/2021 – Nova Lei de Licitações.

ISACA. COBIT 2019 – Framework de governança de TI.

ISO/IEC. ISO 27001:2022 – Sistema de Gestão de Segurança da Informação.

OFFICE OF GOVERNMENT COMMERCE. ITIL v3 e ITIL 4.

Gartner. Magic Quadrant for Endpoint Protection Platforms.

Gartner. Magic Quadrant for Network Firewalls
