# Lab02 - Data Flow & Mensagens <!-- omit in toc -->

- [Tarefa sobre catálogo de componentes](#tarefa-sobre-catálogo-de-componentes)
- [Tarefa Web Components 1](#tarefa-web-components-1)
- [Tarefa Web Components 2](#tarefa-web-components-2)

## Tarefa sobre catálogo de componentes

[Arquivo do notebook](notebook/components-01-catalog.ipynb)

## Tarefa Web Components 1

```html
<dcc-trigger label="Mundo"
             action="noticia/mundo/politica"
             value="política mundial">
</dcc-trigger>
<dcc-trigger label="Brasil P"
             action="noticia/brasil/politica"
             value="política do Brasil">
</dcc-trigger>
<dcc-trigger label="Brasil E"
             action="noticia/brasil/esporte"
             value="esporte do Brasil">
</dcc-trigger>
<dcc-trigger label="Bahia"
             action="noticia/bahia/esporte"
             value="esporte da Bahia">
</dcc-trigger>

<dcc-lively-talk id="doctor"
                 character="doctor"
                 speech="Notícias sobre ">
  <subscribe-dcc topic="noticia/+/politica"></subscribe-dcc>
</dcc-lively-talk>
<dcc-lively-talk id="nurse"
                 character="nurse"
                 speech="Notícias sobre ">
  <subscribe-dcc topic="noticia/brasil/#"></subscribe-dcc>
</dcc-lively-talk>
<dcc-lively-talk id="patient"
                 character="patient"
                 speech="Notícias sobre ">
  <subscribe-dcc topic="noticia/#"></subscribe-dcc>
</dcc-lively-talk>
```

## Tarefa Web Components 2

```html

```