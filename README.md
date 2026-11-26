# BPMN TO-BE — Setor 6: Monitoramento da Execução

Entregáveis da fase TO-BE da disciplina de Gestão de Processos de Negócio

## Estrutura do repositório

```
BPMN_Setor_6_TO_BE/
├── BPM TO-BE/                         # Processo redesenhado (versão final)
│   ├── Processo Principal TO-BE.drawio.png
│   └── Subprocessos/
│       ├── Subprocessos-1. Acompanhar a execução da OS.drawio.png
│       ├── Subprocessos-2. Processar reporte do fornecedor (evento).drawio.png
│       ├── Subprocessos-3. Fiscalizar prazos e conformidade.drawio.png
│       ├── Subprocessos-4. Tratar ocorrência ou alerta.drawio.png
│       ├── Subprocessos-5. Encerrar OS cancelada (evento).drawio.png
│       └── Subprocessos-6. Consolidar indicadores da OS (evento).drawio.png
│
├── BPM TO-BE x AS-IS/                 # Comparativo: o que mudou em relação ao AS-IS
│   ├── TO BE ALTERADO.drawio.png
│   └── Subprocessos_alterados/
│       └── Subprocessos_alterados-1 … 6 (mesmos subprocessos acima, com as alterações destacadas)
│
└── Indicadores/                       # Indicadores de desempenho do processo TO-BE
    ├── Equipe 6 - Planilha de Especificação de Indicadores de Processo (3).xlsx
    └── PDF/
        ├── … - Classificação.pdf
        └── … - Detalhamento.pdf
```

### `BPM TO-BE/`
Diagramas BPMN do processo redesenhado, exportados do draw.io em PNG.

- **Processo Principal TO-BE**: visão geral do fluxo do Setor 6, que chama os subprocessos.
- **Subprocessos/**: um diagrama para cada subprocesso, numerados na ordem em que aparecem no processo principal. Os que têm **(evento)** no nome começam por um evento: chegada de um reporte do fornecedor, cancelamento da OS ou consolidação de indicadores.

| # | Subprocesso |
|---|-------------|
| 1 | Acompanhar a execução da OS |
| 2 | Processar reporte do fornecedor (evento) |
| 3 | Fiscalizar prazos e conformidade |
| 4 | Tratar ocorrência ou alerta |
| 5 | Encerrar OS cancelada (evento) |
| 6 | Consolidar indicadores da OS (evento) |

### `BPM TO-BE x AS-IS/`
Os mesmos diagramas da pasta anterior, com destaque para **o que foi alterado em relação ao processo AS-IS**. Use esta pasta para entender as melhorias propostas; use `BPM TO-BE/` para ver o processo final limpo.

- **TO BE ALTERADO**: processo principal com as alterações destacadas.
- **Subprocessos_alterados/**: subprocessos 1 a 6, com a mesma numeração de `BPM TO-BE/Subprocessos/`.

### `Indicadores/`
Especificação dos indicadores que medem o desempenho do processo TO-BE.

- **Planilha (.xlsx)**: arquivo-fonte, com duas abas:
  - *Classificação*: posiciona cada indicador por desempenho (economicidade, eficiência, eficácia, efetividade) e por fluxo de implementação (insumo, processo, produto, resultado, impacto).
  - *Detalhamento*: ficha de cada indicador, com finalidade, fórmula, variáveis, unidade, polaridade, periodicidade, fase do processo, método e responsável pela coleta.
- **PDF/**: as mesmas duas abas exportadas em PDF, para leitura rápida.

| ID | Indicador | Fase do processo |
|----|-----------|------------------|
| IND01 | Percentual de OS com status atualizado ao cidadão em até 24h | Acompanhar a execução |
| IND02 | Defasagem média da informação de andamento da OS | Acompanhar a execução |
| IND03 | Taxa de conformidade de prazos das OS | Fiscalizar prazos e conformidade |

## Convenções

- **Diagramas:** exportados do draw.io (`.drawio.png`). O nome de cada arquivo segue o padrão `<pasta>-<nº>. <nome do subprocesso>`.
- **Numeração:** os números 1 a 6 identificam o mesmo subprocesso nas duas pastas de BPMN, o que facilita comparar a versão final com a versão anotada.


Obs: Esse readme foi criado com ajuda do claude para orientar sobre a ordenação