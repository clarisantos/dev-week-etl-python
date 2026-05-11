📊 Pipeline ETL: Personalização de Mensagens de Marketing Bancário
Este projeto foi desenvolvido como parte de um desafio prático de Ciência de Dados, com o objetivo de construir um pipeline ETL (Extract, Transform, Load) utilizando Python e Pandas. O projeto simula o fluxo de dados de um sistema bancário, onde clientes recebem recomendações personalizadas com base em sua saúde financeira.

🛠️ O Desafio
O objetivo principal foi replicar um fluxo de dados real, focando na resiliência do sistema. Caso a fonte de dados principal (API) esteja indisponível, o pipeline foi projetado para operar com arquivos locais (CSV), garantindo a continuidade do processo de negócio.

⚙️ Funcionalidades do Pipeline
1. Extração (Extract)
Realiza a leitura de uma base de dados de clientes em formato .csv.

Manipula dados estruturados contendo informações como Nome, Conta e Saldo.

2. Transformação (Transform)
Implementação de lógica de negócio em Python para segmentação de clientes.

Geração de mensagens personalizadas:

Saldo Negativo: Alerta sobre opções de crédito.

Saldo Baixo: Sugestão de reserva de emergência.

Saldo Alto: Recomendações de investimentos (CDB).

3. Carregamento (Load)
Consolidação dos dados transformados em um novo arquivo de saída (desafio_final_sdw.csv).

Preparação dos dados para serem consumidos por ferramentas de marketing ou dashboards.

🚀 Tecnologias Utilizadas
Linguagem: Python 3.x

Biblioteca Principal: Pandas (para manipulação e análise de dados)

Ambiente: Versátil para execução em terminais Linux e automação de scripts.

📂 Como executar o projeto
Clone o repositório:

Bash
git clone https://github.com/SEU_USUARIO/nome-do-repositorio.git
Certifique-se de ter o arquivo usuarios.csv na raiz do projeto.

Execute o script:

Bash
python desafio_etl.py
Por que esta descrição é boa?
Foco no Processo: Você não apenas "fez o código", você explicou o ETL.

Palavras-Chave: Usa termos como "Resiliência", "Lógica de Negócio" e "Segmentação", que são o que os gestores procuram.

Organização: O uso de ícones e blocos de código torna a leitura rápida e clara.

Você pretende adicionar alguma visualização de dados (gráficos) ou prefere manter o foco apenas no processo de backend/automação?
