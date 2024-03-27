Projeto de Automação de Processos - README

Objetivo:
O objetivo deste projeto é automatizar a análise de dados de vendas de várias lojas a partir de uma planilha do Excel. O projeto separa uma planilha para cada loja, calcula métricas como vendas, faturamento, entre outros, e identifica o dia de maior venda para cada loja. Em seguida, gera um ranking das lojas com base nesse indicador e envia um relatório por e-mail, simulando um relatório para uma empresa.

Frameworks Utilizados:

Pandas: Para manipulação e análise de dados.
pathlib: Para interação com arquivos.
win32com.client: Para envio de e-mails em formato HTML.
Requisitos:

Python 3.x instalado no sistema.
Bibliotecas necessárias instaladas:
Pandas
pathlib
win32com.client (para interação com o Excel e envio de e-mails)
Configuração:

Certifique-se de ter todas as bibliotecas mencionadas instaladas. Você pode instalá-las executando pip install nome_da_biblioteca.
Edite o arquivo config.py para ajustar os parâmetros como o caminho do arquivo Excel, as métricas desejadas e informações de e-mail.
Execução:

Execute o script main.py.
O script irá processar a planilha do Excel, separar os dados por loja e calcular as métricas desejadas, como vendas, faturamento, etc.
Em seguida, identifica o dia de maior venda para cada loja e gera um ranking das lojas com base nesse indicador.
Por fim, o relatório é enviado por e-mail em formato HTML, simulando um relatório para uma empresa.
Observações:

Certifique-se de que a estrutura da planilha do Excel esteja de acordo com o esperado pelo script.
Mantenha as configurações de e-mail seguras para evitar o acesso não autorizado à sua conta.
Contribuições:
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues relatando problemas encontrados ou propor melhorias através de pull request
