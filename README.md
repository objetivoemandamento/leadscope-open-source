# LeadScope — Inteligência Comercial

MVP open source para organizar potenciais clientes, qualificar oportunidades manualmente e preparar rascunhos de abordagem comercial. Projeto independente de VÉRTICE e NFC.

## Funcionalidades do MVP
- Painel responsivo em português (pt-BR).
- Cadastro manual de leads com setor, localização, site, prioridade, status e notas.
- Busca e filtro por texto, localização e prioridade.
- Favoritos, exclusão de registros e indicadores.
- Geração de rascunhos de abordagem para revisão humana.
- Exportação da base para CSV.
- Persistência local no navegador via `localStorage`.

## Publicar na Vercel
Este projeto é um site estático e não precisa de etapa de build.

1. Importe este repositório na Vercel.
2. Framework Preset: **Other**.
3. Build Command: deixe vazio.
4. Output Directory: `.` (raiz do projeto), se solicitado.
5. Faça o deploy.

O arquivo `index.html` está na raiz do repositório.

## Limitações importantes
Esta versão **não** faz pesquisa automática real na internet, não usa modelos de IA, não tem backend, banco de dados remoto, login/multiusuário, sincronização entre dispositivos nem envio automático de mensagens. Os registros de exemplo são fictícios. Os dados cadastrados ficam no navegador utilizado e podem ser apagados se o armazenamento local for limpo. Não insira dados sensíveis.

Os rascunhos são sugestões genéricas e devem ser revisados antes de qualquer contato. Verifique os fatos, respeite preferências de contato e cumpra as leis de privacidade e proteção de dados aplicáveis.

## Licença
MIT. Consulte o arquivo [LICENSE](./LICENSE).
