
Acesse: https://github.com/jeanguerino/Trabalho-de-Computa-o-e-Algoritmos/wiki/Leia-me



O lado direito da regra em uma gramática livre de contexto na Forma Normal de Chomsky deve ter comprimento dois.

Portanto, existem 3 tipos de regras que precisam ser removidas / substituídas:

Regras longas (por exemplo, A-> BCD)
Regras vazias (por exemplo, A-> e)
Regras curtas (por exemplo, A-> a)
Entrada
A entrada do usuário inclui:

Número de regras
Estado inicial
Regras, cada uma em uma forma delimitada por espaço (A BC, para A-> BC)
Exemplo
Aqui está um exemplo que indica como usar o script:

Mensagem                Entrada do usuário
Dê o número de regras           3
Dê o estado inicial             S
Regra # 1                      S SS
Regra # 2                      S (S)
Regra # 3                      S e
