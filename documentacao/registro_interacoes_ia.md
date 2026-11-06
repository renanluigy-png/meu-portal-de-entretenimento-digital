# Registro de apoio da Inteligência Artificial
## Agenda 13 – Desenvolvimento de Sistemas I

**Projeto:** Meu Portal de Entretenimento Digital  
**Estudante:** Luigy Renan

Este registro organiza as três etapas de consulta indicadas no enunciado da atividade e descreve como as orientações foram aplicadas no projeto.

### Etapa 1 – Estrutura HTML

**Questão orientadora:** “IA, revise minha estrutura HTML. Estou usando corretamente as tags `<div>`, `<h1>` e `<img>`?”

**Síntese da orientação técnica:** usar `<div>` para agrupar elementos quando não há uma seção semântica mais específica; manter um único `<h1>` como título principal da página; usar `<h2>` para os títulos das três seções; e inserir imagens com `<img>`, incluindo descrições alternativas no atributo `alt`. Elementos como `<header>`, `<main>`, `<section>`, `<article>`, `<figure>` e `<footer>` ajudam a deixar o documento mais organizado.

**Aplicação no projeto:** o arquivo `portal.html` possui um título principal, três seções identificadas, cartões de conteúdo e nove imagens com textos alternativos.

### Etapa 2 – CSS interno e externo

**Questão orientadora:** “IA, como posso definir estilos diferentes para cada seção usando classes e IDs?”

**Síntese da orientação técnica:** classes são apropriadas para reutilizar padrões em vários elementos; IDs identificam elementos únicos e permitem aplicar ajustes específicos. O CSS interno pode ficar em uma tag `<style>` no `<head>`, enquanto a folha externa concentra a maior parte das regras visuais.

**Aplicação no projeto:** o arquivo `estilo.css` contém a identidade visual, cartões, tipografia e espaçamentos. As classes `.portal-section`, `.media-card` e `.section-title` padronizam elementos. IDs como `#titulo-portal`, `#titulo-filmes`, `#titulo-musica` e `#titulo-games` permitem ajustes individuais. O CSS interno estiliza o selo do cabeçalho. Um atributo `style` no HTML demonstra o CSS inline.

### Etapa 3 – Flexbox

**Questão orientadora:** “IA, me ajude a configurar o layout flexível com três colunas ajustáveis.”

**Síntese da orientação técnica:** aplicar `display: flex` ao contêiner das seções, usar `gap` para o espaçamento e permitir que os itens cresçam com `flex: 1 1 0`. Consultas de mídia podem alterar a direção ou a quebra de linha em telas menores.

**Aplicação no projeto:** a classe `.portal-grid` organiza as três seções lado a lado em telas maiores. Em tablets, o layout permite quebra de linha; em celulares, as seções ficam empilhadas para manter a leitura confortável.

### Conferência dos requisitos

- [x] Página HTML com o tema “Meu Portal de Entretenimento Digital”.
- [x] Três seções: Filmes e Séries, Música e Podcasts, Games e Tecnologia.
- [x] Duas a três imagens por seção (foram usadas três em cada seção).
- [x] Pequenos textos explicativos em cada cartão.
- [x] CSS inline, interno e externo.
- [x] Uso de classes e IDs.
- [x] Layout Flexbox responsivo.
- [x] Comentários explicativos nos arquivos CSS.
- [x] Reset CSS inspirado no modelo de Eric Meyer, carregado antes da folha principal.

**Observação:** este arquivo é um registro textual organizado das orientações aplicadas durante o desenvolvimento. Ele não substitui capturas de tela caso o mediador solicite evidências visuais das conversas.