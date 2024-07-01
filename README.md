# Projeto-Exemplo de ETL com Python

## Descrição

Este é um projeto-exemplo de ETL (Extract, Transform, Load) para demonstrar algumas funcionalidades de automação com Python. O código consome uma base em Excel, realiza tratativas e envia a base tratada juntamente com um gráfico por e-mail.

## Funcionalidades

- **Extração**: Leitura de dados a partir de um arquivo Excel.
- **Transformação**: Tratamento dos dados conforme necessário.
- **Carregamento**: Envio dos dados tratados e de um gráfico por e-mail.

## Pré-requisitos

Para executar este projeto, você precisará ter instalado:

- Python 3.x
- Bibliotecas Python:
  - smtplib
  - email (MIMEMultipart, MIMEText, MIMEImage, MIMEApplication)
  - Informações_email (senha, remetente, lista_destinatariosMA, valores_a_excluirMA, lista_destinatariosMA_teste)
  - datetime
  - openpyxl
  - pandas
  - matplotlib
  - tabulate
  - Pillow (PIL)

Você pode instalar essas bibliotecas usando o comando:

```bash
pip install smtplib email openpyxl pandas matplotlib tabulate pillow
