Previsão de Dividendos com Redes Neurais em Python
Este projeto visa prever os dividendos por ação de uma lista de ativos da bolsa de valores usando redes neurais recorrentes (LSTM). O programa constrói, treina, valida e testa um modelo baseado no histórico de dividendos para gerar previsões, sendo útil para investidores que desejam otimizar suas carteiras de ativos com foco em rendimentos.

Estrutura do Projeto
O projeto é composto pelas seguintes etapas:

Coleta de Dados: Obtém o histórico de dividendos por ação de uma lista de ativos da bolsa.
Pré-processamento: Organiza e normaliza os dados para alimentar o modelo de previsão.
Construção do Modelo: Utiliza uma rede neural LSTM para capturar padrões nos dividendos ao longo do tempo.

Treinamento e Validação: O modelo é treinado com 65% dos dados e validado com 17,5% do histórico.
Teste: Os 17,5% restantes são usados para testar o modelo e calcular o erro médio quadrático (MSE).
Previsões: Gera previsões futuras e compara com os dividendos reais de 2023.
Tecnologias Utilizadas
Python 3.x
Bibliotecas:
pandas: para manipulação de dados
numpy: para cálculos numéricos
tensorflow e keras: para construção e treinamento de redes neurais

Como Usar
Clonar o Repositório:
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Instalar Dependências: Execute o seguinte comando no ambiente virtual:
pip install -r requirements.txt
Rodar o Programa: Após instalar as dependências, execute:
python previsao_dividendos.py

Entrada e Saída
Entrada: Lista de ativos com o histórico de dividendos (2008 a 2024).
Saída: Previsões de dividendos para 2023 e 2024, com comparação entre valores previstos e reais.
Contribuições
Contribuições são bem-vindas. Sinta-se à vontade para abrir um issue ou enviar um pull request.

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais informações.