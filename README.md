# Guia de People Analytics

Guia completo com fórmulas validadas para os principais KPIs de People Analytics, implementadas em **4 ambientes**: Excel, DAX (Power BI), SQL e Python.

## KPIs cobertos

| KPI | Benchmark |
|-----|-----------|
| Turnover Rate | 10–15% (SHRM) |
| Retention Rate | > 85% (AIHR) |
| eNPS | 20–40 (LinkedIn Trends) |
| Absenteísmo | ≤ 3,5% (AIHR) |
| Time to Fill | 30–45 dias (SHRM) |
| Time to Hire | 14–23 dias (LinkedIn) |
| Offer Acceptance Rate | > 85% (Michael Page) |
| Cost per Hire | R$ 3.000–8.000 (SHRM) |
| Quality of Hire | > 70/100 (AIHR) |
| Voluntary Turnover | < 10% (SHRM) |

## Como usar

Abra o arquivo `people-analytics-guide.html` em qualquer navegador. Nenhuma dependência externa necessária — tudo está inline.

## Modelo de dados (star schema)

```
dim_Colaboradores ──┐
dim_Vagas          ├── fato_Historico
dim_dCalendario ───┤
                   └── fato_Avaliacoes
```

## Referências

- SHRM Talent Acquisition Benchmarking Report
- AIHR People Analytics Guide
- LinkedIn Talent Trends
- Michael Page Guia Salarial