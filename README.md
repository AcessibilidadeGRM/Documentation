# Documentação de idealização do projeto
### grupo 1
### Lucas Guerriero - Lucas Candido - Mateus Carlos - Pedro Macedo - Artur Silva
| Papel | Integrante |
|---|---|
| UX | Lucas Guerriero |
| Front End | Lamarck, Pedro Macedo |
| Back End | Artur Silva |
| Banco de Dados | Lucas Candido |
--- 
## Introdução
A acessibilidade digital não se restringe a adaptações voltadas exclusivamente a pessoas com deficiências sensoriais — como visuais ou auditivas — mas abrange qualquer tipo de limitação que possa impedir ou dificultar o acesso ao sistema. Isso inclui barreiras linguísticas, limitações de hardware (dispositivos móveis ou desktops, equipamentos novos ou obsoletos, resoluções variadas), faixas etárias distintas, níveis de conhecimento lexical e deficiências em geral.
Em termos práticos, acessibilidade consiste em tornar o sistema utilizável pelo maior número possível de pessoas, sem impor restrições desnecessárias a qualquer público.
Visual
Suporte a configurações para usuários com daltonismo; opção de ampliação tipográfica para facilitar o acesso por idosos; uso criterioso de saturação de cores; e textos com densidade reduzida para maior legibilidade.
Áudio (quando o áudio for um elemento central do sistema)
Integração de interpretação em Libras em tempo real.
Imagens
Inclusão de atributos de texto alternativo nas imagens, garantindo compatibilidade com leitores de tela.
Linguístico
Suporte à tradução para múltiplos idiomas; adoção de linguagem simples e acessível para usuários com menor repertório lexical.
Hardware e Performance
Otimização do código para redução de peso e aderência às práticas de green code, possibilitando a execução em dispositivos de baixa capacidade; desenvolvimento de versões com portabilidade para ambientes online (para aplicativos e sistemas baseados em download); disponibilização de versões offline com funcionalidades reduzidas; e minimização de dependências externas.
Faixa Etária
Tipografia ampliada e contraste adequado para idosos; textos com menor densidade para idosos e crianças; elementos visuais com apelo suave e não agressivo para o público infantil.
## fontes 

```https://www.virtualvision.com.br/blog/ferramentas-acessibilidade-digital/```
```https://www.dominos.com.br/tabs/home?```
```https://www.magazineluiza.com.br``` 

---
### justificativa da falta de acessibilidade da Domino's
A empresa se tornou um dos casos mais famosos do mundo sobre falta de acessibilidade.
Um usuário cego abriu um processo porque:

O site não funcionava com leitores de tela
Elementos não tinham descrição
Navegação por teclado era impossível

O caso virou referência mundial sobre importância do WCAG.
---
## Requisitos do Sistema — Loja de Figurines Online
 
### Requisitos Funcionais
 
#### RF01 — Catálogo de Produtos
 
- O sistema deve exibir os figurines com nome, preço, imagem e disponibilidade em estoque.
- Cada imagem deve obrigatoriamente conter texto alternativo (`alt`) descritivo.
- O catálogo deve permitir filtro por categoria, faixa de preço e disponibilidade.
- O sistema deve oferecer busca textual com sugestões automáticas.
#### RF02 — Página de Produto
 
- A página de cada figurine deve exibir descrição detalhada, galeria de imagens com `alt`, dimensões, materiais e avaliações de outros usuários.
- Deve haver opção de zoom nas imagens, acessível via teclado.
#### RF03 — Carrinho e Checkout
 
- O usuário deve conseguir adicionar, remover e alterar quantidades de itens no carrinho sem depender de arrastar e soltar (*drag-and-drop*).
- O fluxo de checkout deve ser navegável inteiramente por teclado.
- Campos de formulário devem ter rótulos (`<label>`) explicitamente associados.
- Mensagens de erro devem ser descritivas e anunciadas por leitores de tela (`aria-live`).
#### RF04 — Autenticação e Conta
 
- O sistema deve permitir cadastro, login e recuperação de senha.
- O formulário de login deve ser compatível com gerenciadores de senha e preenchimento automático do navegador.
- O usuário deve poder gerenciar endereços e histórico de pedidos na área da conta.
#### RF05 — Acessibilidade Visual
 
- O sistema deve oferecer modo de alto contraste alternável pelo usuário.
- Deve haver opção de aumento de tamanho de fonte (pelo menos três níveis: normal, médio e grande).
- O sistema deve fornecer paletas alternativas compatíveis com os três tipos mais comuns de daltonismo (deuteranopia, protanopia, tritanopia).
#### RF06 — Acessibilidade Linguística
 
- O sistema deve estar disponível em pelo menos dois idiomas: Português (BR) e Inglês.
- O conteúdo deve ser escrito em linguagem simples, com frases curtas e vocabulário cotidiano.
- Termos técnicos devem ser acompanhados de tooltip ou glossário explicativo.
#### RF07 — Suporte a Áudio e Libras
 
- Vídeos promocionais ou instrucionais devem ter legendas e, quando possível, interpretação em Libras.
- Todo conteúdo em áudio deve ter transcrição textual disponível.
#### RF08 — Notificações e Comunicação
 
- O sistema deve enviar confirmação de pedido, atualização de status e nota fiscal por e-mail.
- Notificações em tela devem permanecer visíveis por tempo suficiente e poder ser dispensadas pelo teclado.
---
 
