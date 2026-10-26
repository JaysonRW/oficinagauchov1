# Auto Mecânica Gaúcho — MecFluxo V1.2.2

Protótipo mobile-first para a oficina Auto Mecânica Gaúcho, incluindo site institucional e painel operacional demonstrativo.

## Abrir a demonstração

Abra o arquivo [index.html](./index.html) diretamente em um navegador, ou sirva o diretório em um servidor estático (por exemplo, GitHub Pages).

O `index.html` é uma demonstração autocontida com os estilos, scripts e banner otimizados.

## Funcionalidades da demonstração

- Página institucional responsiva com identidade visual azul e laranja
- Painel de gestão com clientes, veículos e ordens de serviço
- Orçamentos, acompanhamento de etapas e aprovação simulada
- Solicitações de peças e compras vinculadas às ordens de serviço
- Controle de pesquisa, fornecedor, retirada e recebimento de peças
- Exportação de registros de teste em JSON

## Importante

**Este é um protótipo, não um sistema pronto para uso com dados reais.**

O painel utiliza armazenamento local no navegador. **Não há autenticação, banco remoto, sincronização, autorização digital ou backup em servidor. Não utilize dados reais de clientes.**

Dados de contato, localização, serviços e horários exibidos na página pública devem ser confirmados junto à oficina antes de publicação comercial.

## Projeto completo

A base de desenvolvimento React + TypeScript/Vite e as propostas de migração Supabase fazem parte do pacote de projeto V1.2.2 gerado separadamente. O repositório, neste primeiro commit, contém a demonstração HTML autocontida.

## Próximos passos

Integrar autenticação e banco de dados, implantar políticas de segurança e testes com a equipe antes de colocar o painel em produção.
