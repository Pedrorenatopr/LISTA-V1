Hortifruti Fácil - Gestão de Compras 🛒📝

Um aplicativo web Mobile-First desenvolvido especificamente para facilitar a rotina de compras e gestão financeira de profissionais de Hortifruti durante suas idas ao CEASA ou atacadistas.

📌 O Problema Resolvido

Muitos comerciantes ainda utilizam papel e caneta para planejar as compras, anotar os preços pagos no calor do momento (no CEASA) e, ao final do dia, repassar essas informações de forma manual e trabalhosa para o setor financeiro.

O Hortifruti Fácil digitaliza todo esse processo em um único ambiente, sem complicação. Ele foi desenhado com foco absoluto na usabilidade para o público sênior (letras grandes, sem necessidade de navegar entre muitas telas e ações automatizadas).

🚀 Principais Funcionalidades

1. Sistema Unificado de Planejamento e Execução

Aba Única de Compras: O planejamento do que comprar e a anotação do valor pago acontecem na mesma tela. Ao adicionar um produto, os campos de "Quantidade" e "Valor" já ficam disponíveis imediatamente.

Salvamento Automático (Fantasma): Não há botões de "Salvar". Tudo que o usuário digita (seja a quantidade, o valor ou um novo item) é salvo em tempo real na memória do celular (Local Storage). Se o navegador fechar acidentalmente, nenhum dado é perdido.

2. Autocomplete de Produtos Inteligente

Catálogo Embutido: O sistema possui um banco de dados interno com mais de 70 frutas, verduras, legumes e temperos comuns em hortifruti.

Pesquisa Dinâmica e Tolerante: Conforme o usuário digita, o app sugere opções em uma lista com letras grandes. A pesquisa ignora acentos (ex: "mamao" encontra "Mamão").

Adição Livre: Se o produto desejado não estiver no catálogo, o usuário pode digitar livremente e adicioná-lo apertando o botão "+".

3. Usabilidade Focada no Público Mais Velho (Mobile-First)

Interface Limpa e Robusta: Textos grandes, botões coloridos de alto contraste e distâncias adequadas para o toque (Touch Targets grandes) para evitar toques acidentais.

Teclados Otimizados: O campo de valor financeiro (R$) abre automaticamente o teclado numérico do celular (inputmode="decimal" e step="0.01"), evitando que o usuário precise trocar o teclado manualmente.

Mensagens Suaves (Toasts): Substituição dos alertas nativos do navegador (alert()), que costumam causar confusão, por mensagens que aparecem no rodapé e somem sozinhas.

4. Relatório e Fechamento Financeiro

Resumo Automático: A segunda aba ("Resumo") compila em tempo real todos os itens que tiveram algum valor ou quantidade preenchidos.

Totalizador Visível: O valor total gasto no dia fica destacado no topo da tela de resumo.

Integração Nativa com WhatsApp: Com um único clique, o sistema formata a lista de compras (Itens, Quantidades, Valores Individuais e Total) e abre diretamente o aplicativo do WhatsApp no celular, pronto para ser enviado ao setor financeiro.

Encerramento de Dia Seguro: Botão para limpar a lista e começar um novo dia, com modal de confirmação para evitar perdas acidentais de dados.

🛠️ Tecnologias Utilizadas

Este projeto foi construído focando em ser extremamente leve, rápido e não depender de servidores complexos ou banco de dados externo. Ele roda inteiramente no navegador do cliente (Client-Side).

HTML5: Estrutura semântica e suporte a Mobile-First.

CSS3 & Tailwind CSS (via CDN): Estilização rápida, responsiva e moderna, sem a necessidade de gerar arquivos CSS pesados.

JavaScript (Vanilla - ES6): Toda a lógica de estado, cálculo em tempo real e persistência de dados.

Lucide Icons (via CDN): Biblioteca de ícones leves e consistentes para melhorar o entendimento visual das ações.

Local Storage API: Para guardar os dados no navegador do próprio celular do usuário.

📦 Como Instalar / Executar

Como é um aplicativo "Single-File" (Tudo em um arquivo só), a execução é muito simples:

Baixe ou copie o código fonte do arquivo principal (ex: index.html).

Abra o arquivo diretamente em qualquer navegador moderno (Chrome, Safari, Firefox, Edge).

Dica: Para a melhor experiência, abra o arquivo no navegador do seu smartphone.

Para usar como "App" no celular: No Android (Chrome) ou iOS (Safari), abra o arquivo/link, vá nas opções do navegador e clique em "Adicionar à Tela Inicial". Ele criará um ícone igual a de um aplicativo comum.

👤 Como Usar (Guia Rápido)

Na aba 1. Compras, toque no campo "Pesquise ou digite...".

Comece a digitar o nome do produto (ex: "Tomate"). Toque na sugestão que aparecer abaixo.

Com o produto na lista, digite quantas caixas/quilos vai comprar no campo "Qtd".

No campo "Valor (R$)", digite quanto pagou no total por aquele item.

Repita o processo para os demais itens.

Ao final das compras, toque na aba 2. Resumo (abaixo).

Verifique o total e clique no botão verde "Enviar p/ WhatsApp" para repassar os valores ao financeiro.

No final do dia, clique em "Finalizar Dia e Limpar Tudo" para deixar a prancheta pronta para amanhã.
