Leitor de Comprovantes em PDF
Visão Geral
O "Leitor de Comprovantes em PDF" é uma ferramenta que facilita a extração automatizada de dados de comprovantes de pagamento em formato PDF. Utilizando a API da OpenAI para interpretar e organizar os dados, o programa permite que os usuários convertam rapidamente as informações presentes nos PDFs em uma planilha Excel estruturada. Essa ferramenta é ideal para profissionais que lidam com grandes volumes de comprovantes e precisam organizar as informações de forma clara e acessível.

Funcionalidades
Interface Gráfica Simples: O programa fornece uma interface gráfica intuitiva onde o usuário pode selecionar o arquivo PDF e escolher o diretório onde o relatório em Excel será salvo.
Extração de Dados Automatizada: A ferramenta extrai informações importantes como o nome do fornecedor, data de pagamento, valor original, encargos, descontos e valor pago.
Atualização em Tempo Real: Durante a extração, o nome do fornecedor sendo processado é exibido em tempo real na interface gráfica, permitindo que o usuário acompanhe o progresso.
Relatório Excel: Os dados extraídos são organizados em um arquivo Excel com colunas claramente definidas, facilitando a análise e o gerenciamento das informações.
Como Usar
Iniciar o Programa: Ao executar o script Python, a interface gráfica será carregada.

Selecionar o PDF: Clique no botão "Procurar" ao lado do campo "Selecione o PDF" para escolher o arquivo PDF de comprovantes que deseja processar.

Selecionar o Diretório de Salvamento: Clique no botão "Procurar" ao lado do campo "Diretório para salvar o Excel" para escolher o diretório onde o relatório Excel será salvo. O nome do arquivo será automaticamente definido como planilha_de_pagamentos_efetuados.xlsx.

Iniciar Extração: Após selecionar o PDF e o diretório de salvamento, clique em "Extrair Dados e Salvar". O programa começará a processar o PDF e exibirá o nome do fornecedor em tempo real conforme cada página do PDF é processada.

Concluir o Processo: Ao final do processo, o programa exibirá uma mensagem de confirmação indicando que os dados foram extraídos com sucesso e salvos no local especificado.

Requisitos

Python 3.x

Bibliotecas Python:

openai ( use: pip install openai==0.27.6)
pdfplumber
pandas
tkinter


Configuração

Clone este repositório para o seu ambiente local.

Instale as dependências necessárias utilizando pip:

bash/dos

pip install openai pdfplumber pandas
Adicione sua chave de API da OpenAI no script para permitir a comunicação com a API.

Execute o script para iniciar a interface gráfica.

Contribuição
Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões para melhorar a ferramenta, sinta-se à vontade para abrir um problema ou enviar um pull request.

