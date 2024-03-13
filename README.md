# aulas-front-end
 Atividades de estudo html e css

# HTML

1. Estruturaçao
2. Semantica
3. Padroes Web

# CSS

Linguagem de estilizaçao que "casa" com HTML

Em geral, CSS  serve para:

1. Estilos
2. Alinhamento
3. Design Responsivo
4. Animacoes e efeitos especiais de interação

### Formas de implementação

### Inline
O CSS é criado diretamente em cada tag HTML

### Interna/OnPage
O CSS é criado usando regras (com seletores, propriedades, valores) dentro da propria pagina que queremos fomatar.

As regras vão valer para todos os elementos\tags desta pagina

### Como fazer uma regra CSS?
seletor (propriedade: valor;)

seletor(
    propriedades:valor;
    propriedades:valor;
    propriedades:valor;
)


### Externa
É criado um arquivo de estensão CSS indicado as regras de formatação. Este arquivo é então conectado as paginas HTML.

---

### Tipos de seletor
-Tag:seletor mais abrangente/generalista, casa com elementos HTML de acordo com a teg especificada

-Descendente: seletor mais especifico, casa com elementos que são filhos (descendentes) de outro elemtento. Use se espaço para separar o filho/pai

-Classe: seletor versatil que permite a  aplicaçao de estilos em diversos elementos, possibilitando tambem a conbinação de diferentes classes. No CSS usa-se, nome-da-classe para criar a classe, e no HTML usa-se o atributo class="nome-da-classe" para aplicar a classe

-Identificado: seletor bastante restrito  ( o mesmo id so pode ser usado em um elemento por pagina), permitindo cirar uma eslilização altamente especifica. No CSS usa-se #nome-do-id para criar, e no HTML usa-se o atributo id="nome-do-id"para aplicar

-Pseudo-Classe: Classe "pré-prontas/nataivas" da linguagem que podem ser aplicadas em diversas situaçoes, Exemplos: passsar mouse, reconhecer foco, selecionar determinados elementos etc. TODAS pseudo-classe começam com dois-pontos

-Agrupado: grupo de seletores que compartilhm a mesma uma mesma formatação. Usa-se a virgula para separar os seletores 