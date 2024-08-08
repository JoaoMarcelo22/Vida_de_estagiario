# Vida de estagiário
Abaixo será apresentado os principais pontos que vamos abordar nessa jornada conjunta. *lembrando que esse grafico será modificado de acordo com o aprendizado fornecido no nosso canal.*

----
**Gráfico de aprendizado**

```
::: mermaid
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

:::

```

----
**Fontes:**

<a href="https://mermaid.js.org/syntax/flowchart.html">Mermaid - MD</a>
