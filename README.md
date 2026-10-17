# simulador-carteira-dio
Projeto desenvolvido durante o Bootcamp Santander - Excel com IA e Claude da DIO (Digital Innovation One). O objetivo é criar uma ferramenta interativa no Microsoft Excel que simula investimentos, aplicando conceitos de planejamento financeiro, projeção de patrimônio e estimativa de dividendos.

*Este projeto possui finalidade exclusivamente educacional. Os valores apresentados são resultados de uma simulação matemática e não representam recomendação de investimento.*

🎯 Objetivo da Ferramenta
A planilha responde a cinco perguntas de negócio fundamentais para o planejamento financeiro:

* Quanto investir por mês?
* Por quantos anos?
* Qual a taxa de rendimento mensal?
* Quanto de patrimônio vai acumular?
* Quanto vai receber de dividendos por mês?

💻 Tecnologias e Recursos Utilizados

* Microsoft Excel: Construção da interface e modelagem dos dados.
* Validação de Dados: Criação de listas suspensas interativas para a escolha do perfil de investidor.
* Gerenciador de Nomes: Criação de variáveis (como aporte e taxa_mensal) para deixar as fórmulas mais limpas e escaláveis.
* Funções Lógicas e Financeiras: Uso avançado de fórmulas para simulação de cenários.

🛠️ Lógica e Fórmulas Aplicadas

* Para o funcionamento dinâmico da planilha, a lógica foi estruturada nas seguintes funções:
* Função VF (Valor Futuro): Utilizada para calcular o patrimônio acumulado ao longo das projeções (de 2 a 30 anos) com base no aporte mensal e na taxa de rendimento.
* Função PROCV com Chave Composta: Aplicada para buscar e distribuir automaticamente o percentual do aporte entre os diferentes tipos de fundos  de acordo com o perfil de investidor selecionado. A chave composta atua como um indexador preciso para cruzar os dados.

📊 Percentuais e Perfis de Investimento

A divisão dos aportes foi estruturada em uma base de dados auxiliar, fundamentada em três perfis fictícios para fins de simulação:

* Conservador: 50% Tijolo, 30% Papel, 10% Híbridos, 10% FOFs.
* Moderado: 35% Tijolo, 32% Papel, 10% Desenvolvimento, 10% Hotelarias, 8% Híbridos, 5% FOFs.
* Agressivo: 50% Papel, 20% Desenvolvimento, 10% Tijolo, 10% Hotelarias, 5% Híbridos, 5% FOFs.

🎨 O Que Mudou em Relação à Ferramenta do Expert
A lógica e o passo a passo ensinados pelo Expert Felipe Aguiar foram mantidos para garantir a integridade dos cálculos. A principal alteração realizada nesta versão foi a personalização das cores e da identidade visual, adaptando o design da interface para uma experiência de usuário mais alinhada com as minhas preferências de UI.

🚀 Como Utilizar

Faça o download do arquivo .xlsx disponível neste repositório.
Abra o arquivo no Microsoft Excel.
Na tela principal, altere os valores nas células permitidas (Aporte Mensal, Prazo, etc.).
Selecione o seu perfil de investidor na lista suspensa para ver a divisão do portfólio e a projeção de dividendos se ajustarem automaticamente.

📸 Demonstração
Abaixo estão as evidências da planilha funcionando com simulações em dois perfis diferentes:

Simulação Perfil Conservador<img width="830" height="884" alt="image" src="https://github.com/user-attachments/assets/b1f28df2-c9c8-4818-b623-36c04555dbc2" />

Simulação Perfil Agressivo <img width="834" height="885" alt="image (1)" src="https://github.com/user-attachments/assets/753c248f-41fe-43a2-8aab-710db308b5d0" />

📚 O que foi aprendido
Durante o desenvolvimento, foram praticados conceitos vitais para a estruturação de dados:   
- Lógica de Dados: Uso de tabelas auxiliares e chaves compostas para simular o comportamento de bancos de dados relacionais dentro do Excel.   
- Matemática Financeira: Aplicação de juros compostos e projeção de valores no tempo.   
- Boas Práticas: Uso de variáveis (intervalos nomeados) no lugar de referências soltas de células, facilitando a manutenção e a escalabilidade das fórmulas.

👩‍💻 Autor
Ana Clara Fernandes Lima Moreira

Estudante de Análise e Desenvolvimento de Sistemas em transição para a área de Tecnologia.

*Este repositório reúne a planilha elaborada para o desafio e sua respectiva documentação técnica*

