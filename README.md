# Student Dropout Prediction

Projeto de análise e previsão de evasão estudantil utilizando técnicas de Machine Learning no KNIME Analytics Platform.

## Sobre o Projeto

Este projeto visa identificar estudantes com maior risco de evasão através da análise de variáveis acadêmicas, socioeconômicas e comportamentais. Utilizamos pipelines de aprendizado de máquina para comparar diferentes abordagens de classificação.

## Dataset

O dataset contém **10.000 registros** de estudantes com as seguintes variáveis:

| Variável | Descrição |
|----------|-----------|
| `Student_ID` | Identificador único do estudante |
| `Age` | Idade do estudante |
| `Gender` | Gênero (Male/Female) |
| `Family_Income` | Renda familiar |
| `Internet_Access` | Acesso à internet (Yes/No) |
| `Study_Hours_per_Day` | Horas de estudo por dia |
| `Attendance_Rate` | Taxa de presença (%) |
| `Assignment_Delay_Days` | Dias de atraso em trabalhos |
| `Travel_Time_Minutes` | Tempo de deslocamento (minutos) |
| `Part_Time_Job` | Trabalho parcial (Yes/No) |
| `Scholarship` | Bolsa de estudos (Yes/No) |
| `Stress_Index` | Índice de estresse |
| `GPA` | Média geral de notas |
| `Semester_GPA` | Média do semestre |
| `CGPA` | Coeficiente de rendimento acumulado |
| `Semester` | Ano/Semestre atual |
| `Department` | Departamento (Arts, Engineering, CS, etc.) |
| `Parental_Education` | Escolaridade dos pais |
| `Dropout` | Evasão (0 = Não, 1 = Sim) - **Variável alvo** |

## Estrutura do Projeto

```
student-dropout-prediction/
├── README.md
├── student_dropout_dataset_v3.csv      # Dataset principal
├── Pipeline_Student_Dropout.knwf       # Pipeline KNIME
├── apresentacao_pipelines_ml.html      # Apresentação (HTML)
├── apresentacao_pipelines_ml.pdf       # Apresentação (PDF)
├── assets/                             # Imagens e gráficos
│   ├── grafico-barras.png
│   ├── pipeline-a.png
│   ├── pipeline-b.png
│   ├── scatter-plot.png
│   └── img-002.png
└── docs/                               # Documentação
    ├── 01_dataset_info.pdf
    ├── 02_pipeline_tratamento.pdf
    └── 03_comparacao_pipelines.pdf
```

## Pipelines de Machine Learning

Foram desenvolvidos e comparados diferentes pipelines de classificação no KNIME:

- **Pipeline A**: Abordagem com pré-processamento tradicional
- **Pipeline B**: Abordagem alternativa com técnicas avançadas

Os detalhes da comparação estão documentados em `docs/03_comparacao_pipelines.pdf`.

## Como Usar

### Requisitos

- [KNIME Analytics Platform](https://www.knime.com/downloads) (versão 4.x ou superior)

### Execução

1. Clone este repositório
2. Abra o KNIME Analytics Platform
3. Importe o workflow `Pipeline_Student_Dropout.knwf`
4. Execute o pipeline

## Documentação

| Documento | Descrição |
|-----------|-----------|
| `01_dataset_info.pdf` | Informações detalhadas sobre o dataset |
| `02_pipeline_tratamento.pdf` | Pipeline de tratamento de dados |
| `03_comparacao_pipelines.pdf` | Comparação entre pipelines de ML |

## Licença

Este projeto é de uso acadêmico.

---

*Desenvolvido para fins de estudo e pesquisa em Machine Learning aplicado à educação.*

