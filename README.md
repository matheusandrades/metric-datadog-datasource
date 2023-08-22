# Plugin de Fonte de Dados Grafana para Datadog

Este é um **plugin não oficial** da Datadog que utiliza a API da Datadog para consultas de métricas. Também existe um [plugin oficial da Datadog](https://grafana.com/grafana/plugins/grafana-datadog-datasource/) disponível para assinaturas Enterprise do Grafana.

- Suporte apenas para metricas.
- Oferece suporte para:
   - Exploração
   - Variáveis de painel
   - A maioria das visualizações, pelo menos as padrões
   - Nomes/rótulos personalizados para séries de gráficos (incluindo variáveis).
- **Requisitos**:
   - Nome do site, por exemplo, `datadoghq.com`
   - Chave da API
   - Chave de aplicativo

## Instalação

1. Adicione este plugin à lista de "confiáveis" usando, por exemplo, uma variável de ambiente:
   ```
   GF_PLUGINS_ALLOW_LOADING_UNSIGNED_PLUGINS=metric-datadog-datasource
```
2. Instale descompactando para o diretório do plug-in ou usando a variável env, ou seja:
   ```
   GF_INSTALL_PLUGINS=https://github.com/matheusandrades/metric-datadog-datasource/releases/download/latest/metric-datadog-datasource-latest.zip;Datadog
   ```
2. Configurando o Datasource

# Screenshots

## Datasource

![Datasource](https://github.com/matheusandrades/metric-datadog-datasource/raw/main/src/img/datasource.jpg)

## Query

![Query](https://github.com/matheusandrades/metric-datadog-datasource/raw/main/src/img/query_full.jpg)
```
