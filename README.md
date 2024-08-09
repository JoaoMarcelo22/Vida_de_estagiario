# Vida de estagiário
Abaixo será apresentado os principais pontos que vamos abordar nessa jornada conjunta. *lembrando que esse grafico será modificado de acordo com o aprendizado fornecido no nosso canal.*

----
**Gráfico de aprendizado**

```mermaid
flowchart TD

    id1((Ponto Inicial)) --> id2{Logica de programação} & id3[SQL] & id4[Git]
    id2 --> Dev & Dados
    subgraph Versionamento
        id4
    end
    subgraph Dev
        C# & JavaScript
        C# --> BackEnd
        JavaScript --> Front/Back
    end
    subgraph Dados

    Python{Python} --> id11[Automatização] & id12[ML/IA]
    id3 & Python --> id8{{Ciencia de dados}} 
    id3 --> BI
    style id8 fill:green
    end
```

----
**Fontes:**

<a href="https://mermaid.js.org/syntax/flowchart.html" target="_blank">Mermaid - MD</a> <br/>
<a href="https://www.youtube.com/watch?v=_yBXhKfqDRI" target="_blank">Mermaid Embedd in GitHub</a> <br/>
<a href="https://www.w3schools.com/git/default.asp?remote=github" target="_blank">W3C - Git</a> <br/>
<a href="https://www.w3schools.com/js/default.asp" target="_blank">W3C - JavaScript</a> <br/>
<a href="https://www.w3schools.com/python/default.asp" target="_blank">W3c - Python</a> <br/>
