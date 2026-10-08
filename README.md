# Burguer House — sistema digital

## Páginas oficiais

- **Cardápio:** https://danymalaguttimika-afk.github.io/card-pio-/burguer-house-cardapio-dados.html
- **PDV operacional:** https://danymalaguttimika-afk.github.io/card-pio-/burguer-house-pdv.html
- **Gestão/CRM:** https://danymalaguttimika-afk.github.io/card-pio-/burguer-house-gestao-crm.html
- **Precificação privada:** https://danymalaguttimika-afk.github.io/card-pio-/burguer-house-precificacao-privada.html
- **Landing pública:** https://danymalaguttimika-afk.github.io/burger-house/burguer-house-landing-v2.html

## Organização e manutenção

- As quatro páginas HTML deste repositório acima são os endereços operacionais atuais. A landing fica no repositório `burger-house`.
- `burguer-house-pdv-desktop.html` é uma versão de fallback; mantenha-a preservada até haver uma decisão explícita de substituição.
- Arquivos `*-anterior-*` são cópias de rollback, não páginas de uso diário. Preserve as cópias de rollback essenciais.
- Vários endereços antigos com nomes `*-profissional.html`, `*-visual-*.html`, `cardapio-realtime-v3.html` e `pdv-estavel-v4.html` são redirecionamentos de compatibilidade. Eles não são versões independentes; mantenha-os enquanto links ou favoritos antigos puderem existir.
- Os cartões do cardápio e do PDV devem usar a imagem própria do produto (`imageUrl`). Se ela ainda não estiver cadastrada, a interface mostra um aviso neutro; não substituir por foto genérica.
- O workspace de precificação é privado e separado. Sugestões de preço não atualizam produtos, `costPrice`, cardápio ou PDV automaticamente.
- Não adicionar credenciais, tokens, chaves de serviço ou dados de clientes a este repositório público.

## Protótipo temporário de comandas

- https://danymalaguttimika-afk.github.io/card-pio-/burguer-house-comandas-prototype.html
- Demonstração isolada: não acessa Firebase, não grava dados e não imprime. Serve apenas para revisar o fluxo de comandas antes de qualquer mudança no PDV oficial.

## Rotas retiradas

- `burguer-house-precificacao-preview.html` era um protótipo de precificação sem referências ativas. Foi removido após a publicação do painel privado oficial.
