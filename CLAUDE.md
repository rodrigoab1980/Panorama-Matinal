# Panorama Matinal — regras do projeto

O Panorama existe em dois lugares, que precisam ficar iguais no conteúdo:

1. **Página no Claude (artifact):** https://claude.ai/artifact/8K4cvx5os7zLaRs5mE3rhq
   - Tem o mapa do S&P desenhado por ação (dados do Finviz) e o botão "Gerar resumo" do Laatus.
   - Ao republicar, não passe `capabilities` nem `icon`, para manter o botão funcionando.
2. **Site público (este repositório):** https://rodrigoab1980.github.io/Panorama-Matinal/
   - As partes ao vivo são widgets do TradingView e não devem ser editadas à mão.
   - O conteúdo editorial fica entre os marcadores `<!-- EDITORIAL:... -->` e `<!-- /EDITORIAL:... -->`.

**Regra:** toda alteração pedida pelo usuário (visual, conteúdo, seções, textos) deve ser feita nos dois: republicar o artifact E fazer commit/push aqui. Ao terminar, dizer ao usuário que os dois foram atualizados.

Tarefas agendadas (dias úteis, horário de Brasília), que atualizam os dois:
- 07:28 "Panorama Matinal": edição completa
- 10:05 "Resumo Laatus": resumo da live (usa o navegador do computador do usuário)
- 10:55 "Panorama - notícias 11h": só entra se houver notícia relevante

Se uma mudança alterar a estrutura da página, atualize também as instruções dessas tarefas.

Idioma: português do Brasil.
