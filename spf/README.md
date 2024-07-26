# registrar-nfs
- Fluxo para realizar a leitura de notas fiscais da MGS e PRODEMGE e posterior leitura de documento de Dados para Conformidade no SEI.
- O fluxo realiza integração com o SEI e usa JavaScript para realizar a extração dos dados para conformidade.
- No momento está paralisado o desenvolvimento por conta de alterações na padronização do documento de Dados para Conformidade pela equipe do SEI.

# registrar-liquidacao
- Fluxo para realizar o lançamento de informações no Siafi referentes ao processo de execução de liquidação.
- Usa planilha auxiliar para leitura e registro dos dados. 
- Dividido em duas etapas, uma referente ao Siafi terminal e outra referente ao Siafi Web. 
- Na etapa do Siafi Web é utilizado linguagem Javascript para preenchimento de formulários e também é realizada integração com o SEI.

# registrar-pagamento
- Mesma linha do fluxo anterior, porém referente à etapa de pagamento da execução de despesas.

# jogo-da-memória
- Jogo criado para realização de dinâmica em grupo da equipe da SPF.
- Utiliza o Excel e Automate para a criação e execução do jogo.

## Observação
Os arquivos config.xlsx possuem as variáveis de entrada utilizadas para o funcionamento dos respectivos fluxos.
