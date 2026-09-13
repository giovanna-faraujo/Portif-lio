# Portfólio — Giovanna Ferreira Araujo
 
Site pessoal em HTML puro, com tema claro e escuro. Feito para GitHub Pages.
 
## Estrutura de arquivos
 
```
index.html                          → o site (imagens dos projetos já embutidas no arquivo)
Giovanna_Ferreira_Araujo_CV_TI.pdf  → currículo em PDF, baixado pelo botão do site
README.md                            → este arquivo
```

## Tradução automática do navegador
 
A página está só em português, mas preparada para funcionar bem com a tradução automática do navegador (o "Traduzir esta página?" do Chrome, Edge, etc.):
 
- O idioma da página está declarado corretamente (`lang="pt-BR"`), que é o que faz o navegador oferecer a tradução automaticamente para quem visita em outro idioma.
- Não há nenhum bloqueio de tradução no código.
- Os textos estão em blocos completos (frases inteiras), não fragmentados em pedaços soltos, o que deixa a tradução automática mais natural.
Nomes de ferramentas e tecnologias (Power BI, Active Directory, ServiceNow etc.) tendem a não ser traduzidos pelo navegador, o que é o comportamento esperado, já que são nomes próprios.

## Cores e tema
 
As cores ficam centralizadas no início do arquivo, dentro de `:root` (tema claro) e `[data-theme="dark"]` (tema escuro):
 
```css
--accent   → cor de destaque principal (roxo)
--signal   → verde, usado no WhatsApp e nos indicadores de status
--warn     → dourado, usado no e-mail e nas tags "em formação"
```
 
O botão no cabeçalho alterna entre os temas e lembra a última escolha do visitante (quando o navegador permite salvar essa preferência).
