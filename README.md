Quantas vezes você ouviu as frases abaixo ao discutir a automatização de um processo
com um colega, amigo ou cliente?

"Ahh, é muito complicado."
"Ahh, eu tenho um script aqui que já faz tudo o que eu preciso."
"Ahh, essa tarefa aqui precisa de um input humano diferente toda vez, não tem como automatizar."

É complicado mudar, mas o mundo ideal não é alcançado de uma vez só. Além de apresentar
brevemente as caracterísiticas principais do ansible e alguns exemplos básicos, vamos mostrar
algumas formas de uso não ideais, mas que talvez sejam exatamente o que você ou seu colega
precisam para começar a automatizar seus processos.

Pois o ERRADO é não começar a usar infraestrutura como código.


- Básico (slides do cmpas)
  - Arquitetura
  - Push/agentless/etc
  - Exemplos

- O errado é não começar a fazer infraestrutura como código
  - configure/make/make install (bleergh)
  - módulo script
  - vars_prompt
  - vault


  (tentar passar um extra var file como param)
  (chamar ansible através de um script python que gera o inventário e tem parâmetros transformados em variáveis)
