## Aplicação de Gerenciamento de RH Escolar em Python

Este projeto Python oferece uma solução simples para gerenciar informações básicas do corpo docente de uma escola, incluindo cálculo de custos com salários.

### Funcionalidades

- **Cadastro de Professores:** Permite inserir dados como nome, endereço, data de admissão, área de atuação, carga horária diária, valor da hora e dias trabalhados por semana e por mês.
- **Cálculo Automático de Custos:** Calcula automaticamente a carga horária semanal, o custo semanal e o custo mensal de cada professor, com base nos dados fornecidos.
- **Exibição Organizada dos Dados:** Apresenta os dados de todos os professores cadastrados de forma clara e estruturada.

### Como Usar

1. **Requisitos:** Certifique-se de ter o Python instalado em seu computador.
2. **Execução:** Execute o script Python (`nome_do_arquivo.py`) em seu terminal.
3. **Interação:** Siga as instruções na tela para inserir os dados de cada professor. Digite "sair" quando terminar.
4. **Resultados:** Os dados dos professores e os custos calculados serão exibidos no terminal.

### Estrutura do Código

- **`calcular_custos(professor)`:** Função que realiza os cálculos de custos.
- **`professores = []`:** Lista para armazenar os dados dos professores.
- **Loop `while True`:** Permite a inserção contínua de dados até que o usuário digite "sair".

### Próximos Passos (Sugestões)

- **Validação de Dados:** Implementar validação para garantir que os dados inseridos sejam válidos (formato de data, valores numéricos, etc.).
- **Armazenamento Persistente:** Salvar os dados em um arquivo (CSV, JSON) ou banco de dados para que persistam após o término da execução do script.
- **Interface Gráfica:** Criar uma interface gráfica (GUI) para facilitar a interação com o usuário.
- **Relatórios:** Gerar relatórios com informações mais detalhadas sobre os custos, como total de gastos por área de atuação.
- **Integração:** Integrar com outros sistemas da escola, como o sistema de gestão acadêmica.

### Observações

- Este projeto é um ponto de partida e pode ser expandido para incluir funcionalidades mais avançadas.
- Sinta-se à vontade para contribuir, reportar problemas e sugerir melhorias!
