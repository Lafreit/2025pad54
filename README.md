# 🗂️ Estrutura para o projeto da defesa do PAD
## A ideia é criar um repositório com uma organização clara entre:
- Documentos oficiais do processo
- Minutas e versões da defesa
- Anexos e provas
- Pesquisa jurídica
- Scripts ou automações (se houver)
- Configurações do projeto (incluindo .gitignore)
## A estrutura típica delineada consiste em:
```
PAD-Defesa/
│
├── Documentos_Oficiais/
│   ├── Portaria_PAD.pdf
│   ├── Notificacao_PAD.pdf
│   ├── Regras_PAD.docx
│   └── Outros_Documentos/
│
│       └── Documento_Extra.pdf
│
├── Minutas_Defesa/
|   ├── Minuta_Inicial.docx
│   ├── Versao_1.docx
│   ├── Versao_2.docx
│   └── Versao_Final.docx
│
├── Anexos_Provas/
|   ├── Documentos-pessoais/
│   ├── Fatos_Evidencias/
│   │   ├── Fato_1.jpg
│   │   └── Fato_2.png
│   ├── Documentos_Provas/
│   │   ├── Prova_1.pdf
│   │   └── Prova_2.jpg
│   └── Outros_Anexos/
│
│       └── Anexo_Extra.pdf
│
├── Pesquisa_Juridica/
│   ├── Artigos/
│   │   ├── Artigo_1.pdf
│   │   └── Artigo_2.pdf
│   ├── Jurisprudencia/
│   │   ├── Caso_1.pdf
│   │   └── Caso_2.pdf
│   └── Legislacao/
│       ├── Lei_1.pdf
│       └── Lei_2.pdf
│
├── Scripts_Automatizacoes/
│   ├── script1.py
│   └── script2.sh
│
└── .gitignore
```
# 🧩 Estrutura Geral de um Processo Administrativo Disciplinar (PAD)
## 1️⃣ Fase Preliminar (Investigação / Sindicância)
- Levantamento inicial dos fatos
- Coleta de informações e documentos
- Oitiva informal de envolvidos
- Relatório preliminar
- Conclusão: arquivamento ou instauração do PAD

## 2️⃣ Instauração do PAD
- Publicação da Portaria de Instauração
- Definição da Comissão Processante
- Delimitação dos fatos e dispositivos legais supostamente violados
- Notificação do servidor

## 3️⃣ Instrução Processual
🔹 3.1. Citação / Notificação do Servidor
- Comunicação formal
- Prazo para apresentação de defesa prévia (quando aplicável)
🔹 3.2. Produção de Provas
- Oitiva de testemunhas
- Depoimento do acusado
- Juntada de documentos
- Diligências
- Perícias (se houver)
🔹 3.3. Relatório Parcial da Comissão
- Análise dos fatos
- Indicação de provas
- Eventual sugestão de penalidade ou absolvição

## 4️⃣ Defesa
- Abertura de prazo para defesa escrita
- Possibilidade de juntar documentos, provas e requerer diligências
- Entrega da defesa e protocolo

## 5️⃣ Relatório Final da Comissão
- Exame da defesa
- Conclusão fundamentada
- Proposta de penalidade ou arquivamento
- Encaminhamento à autoridade competente

## 6️⃣ Decisão da Autoridade Julgadora
- Análise do relatório final
- Julgamento
- Aplicação de penalidade ou arquivamento
- Notificação do servidor

## 7️⃣ Recursos / Revisão
- Pedido de reconsideração
- Recurso hierárquico
- Revisão do PAD (em caso de fatos novos ou vícios graves)
- Decisão final sobre recursos
- Encerramento do processo
- Notificação do servidor

# 📌 Esquema:

```PAD
├── Fase Preliminar
│   ├── Investigação
│   └── Levantamento de Fatos
├── Instauração
│   ├── Portaria de Instauração
│   ├── Comissão Processante
        └── Art. 21, LC nº 235/2023: 
              - Comissão previamente nomeada
              - Composta exclusivamente por Procuradores Municipais estáveis.
              - Não pode integrar a Comissão o advogado de alguma das autarquias municipais.
                - Lei  complementar nº 259/2024, art. 5°:
                    - "Os cargos de "Advogado" redistribuídos na forma do art. 1° serão extintos com a sua vacância."
              - Comissão composta por 3 membros, sendo um Presidente e dois Membros.
              - Comissão deve ser composta por Procuradores Municipais de carreira, estáveis, e não pode integrar a Comissão o advogado de alguma das autarquias municipais.
├── Instrução Processual
│   ├── Citação/Notificação
│   ├── Produção de Provas
│       ├── Oitiva de Testemunhas
│       ├── Depoimento do Acusado
│       ├── determinar Diligências
│       └── Perícias (se necessário)
├── Defesa Prévia
    ├── prazo de 10 dias (art. 203, caput, da Lei complementar nº 31/2013)
├── Relatório conclusivo da Comissão (art. 203, segnda parte e §1º, da Lei complementar nº 31/2013)
    ├── Se absolvição ou arquivamento → encaminhamento à autoridade competente
    ├── Se penalidade → encaminhamento à autoridade competente para decisão.
├── Decisão da Autoridade
└── Recursos/Revisão
```

# 🔶 FLUXOGRAMA DETALHADO DO PROCESSO ADMINISTRATIVO DISCIPLINAR (PAD)

```plaintext
Início do PAD
   │
   ├── Fase Preliminar
   │     ├── Investigação Inicial
   │     ├── Coleta de Informações
   │     ├── Oitiva Informal
   │     └── Relatório Preliminar
   │           │
   │           ├── Arquivamento do Caso
   │           └── Instauração do PAD
   │
   ├── Instauração do PAD
   │     ├── Publicação da Portaria
   │     ├── Definição da Comissão
   │     ├── Delimitação dos Fatos
   │     └── Notificação do Servidor
   │
   ├── Instrução Processual
   │     ├── Citação/Notificação Formal
   │     │     └── Prazo para Defesa Prévia
   │     ├── Produção de Provas
   │     │     ├── Oitiva de Testemunhas
   │     │     ├── Depoimento do Acusado
   │     │     ├── Juntada de Documentos
   │     │     ├── Diligências
   │     │     └── Perícias (se necessário)
   │     └── Relatório Parcial da Comissão
   │           ├── Análise dos Fatos
   │           ├── Indicação de Provas
   │           └── Sugestão de Penalidade/Absolvição
   │
   ├── Defesa do Servidor
   │     ├── Prazo para Defesa Escrita
   │     ├── Juntada de Documentos/Provas
   │     └── Protocolo da Defesa
   │
   ├── Relatório Final da Comissão
   │     ├── Exame da Defesa
   │     ├── Conclusão Fundamentada
   │     ├── Proposta de Penalidade/Arquivamento
   │     └── Encaminhamento à Autoridade Competente
   │
   ├── Decisão da Autoridade Julgadora
   │     ├── Análise do Relatório Final
   │     ├── Julgamento do Caso
   │     ├── Aplicação de Penalidade/Arquivamento
   │     └── Notificação do Servidor
   │
   └── Recursos/Revisão
         ├── Pedido de Reconsideração
         ├── Recurso Hierárquico
         └── Revisão do PAD (se necessário)
```

# 📘 - Projeto de Defesa do PAD

# 🛡️ Projeto de Defesa – Processo Administrativo Disciplinar (PAD)

Este repositório organiza toda a documentação, versões, anexos e pesquisas relacionadas à defesa apresentada no Processo Administrativo Disciplinar (PAD).  
A estrutura foi planejada para garantir clareza, rastreabilidade e controle de versões.

---

## 📂 Estrutura do Repositório

```
|-- Atospad1818
|   |-- 2025pad54-Citacao.pdf
|   |-- DefesaPreviaPad_54-2025 (1).pdf
|   `-- DefesaPreviaPad_54-2025.docx
|-- DIpad1818
|   |-- 0955.560.0015670-2025.pdf
|   |-- 0955.560.0016327-2025.pdf
|   `-- 0955.560.0016563-2025.pdf
|-- DOEpad1818
|   |-- 20250829Ed2706CSata20250807AutPAD.pdf
|   |-- 20250829eD2706CSata20250814AtuPAD&SuspPrev.pdf
|   `-- 20260109.Ed2797port1818.pdf
|-- OutrasSindicancias
|   |-- 0000247-2026-PAD.pdf
|   |-- 0955.560.0015670-2025_Perda_PZ_Multirao-PAD.pdf
|   `-- 0955.5600003285-2025_DrMagrini_PendenciasSAJ_de_LAF.pdf
|-- Pipfile
|-- Provas
|   `-- AvisoFerias2025.docx
|-- README.md
|-- template
|   |-- MinutaDefesa.md
|   |-- MinutaDefesaPrevia.md
|   `-- resumo.md
`-- venv
    |-- Include
    |-- Lib
    |   `-- site-packages
    |-- Scripts
    |   |-- Activate.ps1
    |   |-- activate
    |   |-- activate.bat
    |   |-- activate.fish
    |   |-- deactivate.bat
    |   |-- pip.exe
    |   |-- pip3.14.exe
    |   |-- pip3.exe
    |   |-- python.exe
    |   `-- pythonw.exe
    `-- pyvenv.cfg

```

---

## 🧭 Fluxograma Detalhado do Processo Administrativo Disciplinar


┌──────────────────────────────────────────────────────────────┐ │                     1. FASE PRELIMINAR                       │ │                (Sindicância / Investigação)                  │ └───────────────┬──────────────────────────────────────────────┘ │ ▼ ┌──────────────────────────────────────────────┐ │ Há indícios suficientes para instaurar PAD?  │ └───────────────┬──────────────────────────────┘ │SIM │ ▼ ┌──────────────────────────────────────────────┐ │              2. INSTAURAÇÃO DO PAD           │ │ - Portaria                                   │ │ - Nomeação da Comissão                       │ │ - Delimitação dos fatos                      │ └───────────────┬──────────────────────────────┘ │ ▼ ┌──────────────────────────────────────────────┐ │              3. INSTRUÇÃO PROCESSUAL         │ └───────────────┬──────────────────────────────┘ │ ▼ ┌──────────────────────────────────────────────┐ │ 3.1. CITAÇÃO / NOTIFICAÇÃO DO SERVIDOR        │ │ - Ciência formal                              │ │ - Prazo para defesa prévia (quando cabível)   │ └───────────────┬──────────────────────────────┘ │ ▼ ┌──────────────────────────────────────────────┐ │            3.2. PRODUÇÃO DE PROVAS           │ │ - Oitiva de testemunhas                      │ │ - Depoimento do acusado                      │ │ - Juntada de documentos                      │ │ - Diligências / perícias                     │ └───────────────┬──────────────────────────────┘ │ ▼ ┌──────────────────────────────────────────────┐ │        3.3. RELATÓRIO PARCIAL DA COMISSÃO    │ │ - Análise dos fatos                          │ │ - Indicação de provas                        │ │ - Eventual sugestão preliminar               │ └───────────────┬──────────────────────────────┘ │ ▼ ┌──────────────────────────────────────────────┐ │                    4. DEFESA                 │ │ - Defesa escrita                             │ │ - Juntada de documentos                      │ │ - Requerimento de diligências                │ └───────────────┬──────────────────────────────┘ │ ▼ ┌──────────────────────────────────────────────┐ │        5. RELATÓRIO FINAL DA COMISSÃO        │ │ - Exame da defesa                            │ │ - Conclusão fundamentada                     │ │ - Proposta de penalidade ou arquivamento     │ └───────────────┬──────────────────────────────┘ │ ▼ ┌──────────────────────────────────────────────┐ │       6. DECISÃO DA AUTORIDADE JULGADORA     │ │ - Julgamento                                 │ │ - Penalidade ou arquivamento                 │ └───────────────┬──────────────────────────────┘ │ ▼ ┌──────────────────────────────────────────────┐ │                7. RECURSOS / REVISÃO         │ │ - Pedido de reconsideração                   │ │ - Recurso hierárquico                        │ │ - Revisão do PAD                             │ └──────────────────────────────────────────────┘

---

## 📋 Checklist Operacional do PAD

### **Fase Preliminar**
- [ ] Verificar documentos iniciais  
- [ ] Identificar fatos imputados  
- [ ] Avaliar indícios mínimos  
- [ ] Confirmar existência de sindicância  

### **Instauração**
- [ ] Conferir Portaria  
- [ ] Verificar composição da comissão  
- [ ] Checar descrição dos fatos  
- [ ] Confirmar notificação  

### **Instrução**
- [ ] Defesa prévia (se cabível)  
- [ ] Oitiva de testemunhas  
- [ ] Depoimento do acusado  
- [ ] Juntada de documentos  
- [ ] Solicitar diligências  
- [ ] Registrar nulidades  

### **Defesa**
- [ ] Elaborar defesa escrita  
- [ ] Anexar documentos  
- [ ] Formular pedidos  
- [ ] Protocolar no prazo  
- [ ] Guardar comprovante  

### **Relatório Final**
- [ ] Conferir análise da defesa  
- [ ] Verificar coerência da conclusão  
- [ ] Identificar vícios  

### **Decisão**
- [ ] Checar fundamentação  
- [ ] Verificar divergências  
- [ ] Confirmar notificação  

### **Recursos**
- [ ] Avaliar reconsideração  
- [ ] Preparar recurso hierárquico  
- [ ] Verificar cabimento de revisão  

---

## 🧱 Convenção de Nomeação

- `defesa-vX.md` → rascunhos  
- `defesa-vX.Y.pdf` → versões exportadas  
- `defesa-final.pdf` → peça definitiva  
- `YYYY-MM-DD-descricao.ext` → comprovantes e anexos  

---

## 📌 Objetivo do Repositório

Este repositório serve como base organizada para:

- elaboração da defesa,  
- controle de versões,  
- armazenamento de documentos,  
- registro de prazos e diligências,  
- acompanhamento completo do PAD.  

---

## 📜 Licença

Uso pessoal e restrito ao processo administrativo.
Proibida reprodução ou distribuição sem autorização.