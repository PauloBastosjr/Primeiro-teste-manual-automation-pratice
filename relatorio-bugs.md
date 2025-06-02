# 🐞 Relatório de Bugs - automationpratice.com.br

## 🐛 BUG01 - Login aceita senha incorreta
- **Descrição:** O sistema permite o login mesmo com senha incorreta.
- **Passos para Reproduzir:**
  1. Acessar o site  
  2. Clicar em "Login"  
  3. Inserir um e-mail válido e uma senha incorreta  
  4. Clicar em "Entrar"
- **Resultado Esperado:** Exibição de mensagem de erro: _"Senha inválida"_
- **Resultado Obtido:** Usuário é autenticado com senha incorreta. Mensagem de erro não é exibida.
- **Gravidade:** Alta  
- **Prioridade:** Alta  
- **Ambiente:** Chrome 136 / Windows 11  
- **Status:** Aberto  

## 🐛 BUG02 - Busca de produto específico retorna itens genéricos
- **Descrição:** Busca um produto específico mas traz todos os itens disponíveis.
- **Passos para Reproduzir:**
  1. Acessar o site  
  2. Clicar na lupa de busca  
  3. Digitar o nome exato de um produto (ex: "camiseta azul")  
  4. Pressionar Enter
- **Resultado Esperado:** Exibir o produto específico informado
- **Resultado Obtido:** Mostra a mensagem de "Sucesso", mas traz todos os produtos do catálogo, não apenas o buscado.
- **Gravidade:** Média  
- **Prioridade:** Média  
- **Ambiente:** Chrome 136 / Windows 11  
- **Status:** Aberto  
