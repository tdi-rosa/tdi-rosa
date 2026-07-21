```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#ffffff","primaryTextColor":"#111111","primaryBorderColor":"#ffffff","lineColor":"#111111","fontFamily":"ui-monospace, SFMono-Regular, Menlo, monospace","fontSize":"13px"},"flowchart":{"curve":"basis"}}}%%
flowchart TB
    classDef eventdot fill:#ffffff,stroke:#111111,stroke-width:1.5px
    classDef projectdot fill:#111111,stroke:#111111,stroke-width:1.5px
    classDef label fill:none,stroke:none,color:#111111,text-align:left
    classDef sub fill:none,stroke:none

    subgraph n1[ ]
    direction LR
    Ad(( )):::eventdot
    At["APR 2026<br/>STARTED AT 42 (PARIS)"]:::label
    Ad --- At
    end

    subgraph n2[ ]
    direction LR
    Bd["  "]:::projectdot
    Bt["JUN 2026<br/><b>parlementclair</b><br/>AI legal chatbot for the French<br/>National Assembly hackathon"]:::label
    Bd --- Bt
    end

    subgraph n3[ ]
    direction LR
    Cd["  "]:::projectdot
    Ct["JUL 2026<br/><b>epub-translator-vllm</b><br/>Self-hosted EPUB translator<br/>running Qwen3.5 on vLLM"]:::label
    Cd --- Ct
    end

    n1 --> n2 --> n3
    class n1,n2,n3 sub

    click Bt "https://github.com/tdi-rosa/parlementclair" _blank
    click Ct "https://github.com/tdi-rosa/epub-translator-vllm" _blank
