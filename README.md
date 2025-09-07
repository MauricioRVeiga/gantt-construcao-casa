## 📊 Gráfico de Gantt - Construção de Casa Unifamiliar

```mermaid
gantt
    title Cronograma do Projeto - Construção de Casa
    dateFormat  DD/MM/YYYY
    axisFormat  %d/%m

    section Planejamento
    Planejamento e Aprovações      :done, a1, 08/09/2025, 20d

    section Terreno
    Preparação do Terreno          :done, a2, after a1, 10d
    Fundação                       :active, a3, after a2, 15d

    section Estrutura
    Estrutura da Casa              :a4, after a3, 30d
    Instalações Elétricas/Hidráulicas :a5, after a4, 20d

    section Acabamento
    Acabamento Interno             :a6, after a5, 25d
    Acabamento Externo             :a7, after a6, 15d

    section Finalização
    Inspeção Final e Entrega       :a8, after a7, 5d
