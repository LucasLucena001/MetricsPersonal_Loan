# Modelo de Predição de Empréstimos Pessoais

Este repositório contém um script Python desenvolvido para prever a aceitação de empréstimos pessoais pelos clientes de um banco. O modelo utiliza dados históricos dos clientes, incluindo idade, experiência, renda, tamanho da família, entre outros, para fazer as previsões.

## Funcionalidades

- Carrega e prepara os dados a partir de um arquivo Excel.
- Aplica um modelo de regressão logística para prever a aceitação de empréstimos.
- Calcula métricas de desempenho do modelo, incluindo acurácia, precisão, recall, F1 Score e ROC-AUC.
- Exibe a matriz de confusão e a curva ROC.

## Como Usar

1. Clone o repositório para sua máquina local.
2. Instale as dependências necessárias usando `pip install -r requirements.txt` (você precisará criar este arquivo).
3. Execute o script com `python metricsperonal_loan.py`.

## Dependências

- pandas
- numpy
- scikit-learn
- matplotlib

## Dados

Os dados usados neste script são fornecidos em um arquivo Excel chamado `Bank_Personal_Loan_Modelling.xlsx`. Certifique-se de que este arquivo está no diretório correto ou atualize o caminho no script conforme necessário.

## Contribuições

Contribuições são bem-vindas! Se você tem melhorias ou correções, por favor, faça um fork do repositório e submeta um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE.md para detalhes.
