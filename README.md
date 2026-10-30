# Crie Orçamento

Gerador de orçamentos profissionais para qualquer tipo de serviço ou produto.

**Site:** https://crieorcamento.com.br

## O que faz

- Monta o orçamento com logo, cor da empresa, itens, descontos, frete e impostos
- Calcula entrada, parcelas e juros
- Gera QR Code Pix com o valor já preenchido
- Baixa o PDF em A4 ou imprime direto
- Copia o orçamento formatado para o WhatsApp
- Conta de usuário com orçamentos salvos na nuvem
- Link de aprovação: o cliente abre no celular, confere e aprova com nome e CPF, sem precisar de conta
- Orçamento aprovado fica travado; para mudar, é preciso duplicar

## Como funciona por dentro

Página única em HTML, sem servidor próprio. O PDF é gerado no navegador (jsPDF) e os dados ficam no Supabase (login, banco e regras de acesso por usuário). A hospedagem é o GitHub Pages.

## Autor

Feito por Jefferson Buiar, JDB Sites.
