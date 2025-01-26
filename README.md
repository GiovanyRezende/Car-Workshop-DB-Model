# Projeto Conceitual de Banco de Dados – Oficina

## Descrição
*O projeto se trata se uma modelagem conceitual para um contexto de oficina.* Contém as entidades:

- Cliente;
- Veículo;
- Mecânico;
- Especialidade;
- Equipe;
- Serivço;
- Ordem de Serviço (OS);
- Peça;
- Referência;
- Status;
- Endereço (tanto do cliente quanto do mecânico)

A narrativa do projeto é:

- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica;
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas;
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega;
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra;
- O valor de cada peça também irá compor a OS, e o cliente autoriza a execução dos serviços;
- A mesma equipe avalia e executa os serviços;
- Os mecânicos possuem código, nome, endereço e especialidade;
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

O modelo conceitual foi feito no aplicativo *brModelo*.

![image](https://github.com/user-attachments/assets/67059cec-281c-4063-ab74-b4f49d42dbe6)
