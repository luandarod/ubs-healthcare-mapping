# UBS Healthcare Mapping

Atlas territorial de acesso à Atenção Primária à Saúde (APS) e oportunidade para telemedicina no Brasil.

O projeto combina dados de UBS, IBGE, DATASUS, Farmácia Popular, OpenStreetMap e conectividade para avaliar barreiras territoriais e oportunidades de acesso. Os indicadores são exploratórios e não comprovam acesso individual ou demanda clínica.

- [Dashboard interativo](https://luandarodrigues-portfolio.vercel.app/dashboards/ubs-healthcare-mapping/)
- [Documentação completa, metodologia e instruções de reprodução](projects/ubs-healthcare-mapping/README.md)
- [Dicionário de dados](projects/ubs-healthcare-mapping/TELEMEDICINE_DATA_DICTIONARY.md)
- [Protocolo pré-paper](projects/ubs-healthcare-mapping/PREPAPER_TELEMEDICINE_PROTOCOL.md)
- [Matriz de decisão](projects/ubs-healthcare-mapping/TELEMEDICINE_DECISION_MATRIX.md)

## Estrutura

- `projects/ubs-healthcare-mapping/`: scripts Python, dados, testes, gráficos e documentação.
- `docs/dashboards/ubs-healthcare-mapping/`: dashboard HTML, JavaScript e dados publicados.

Os caminhos originais foram mantidos para preservar a reprodução do pipeline.

## Instalação e testes

```bash
pip install -r projects/ubs-healthcare-mapping/requirements.txt
python -m pytest projects/ubs-healthcare-mapping/tests
```

Consulte a documentação completa para executar todas as etapas de aquisição, enriquecimento, roteamento e auditoria.
