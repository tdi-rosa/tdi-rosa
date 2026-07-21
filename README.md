```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#ffffff","primaryTextColor":"#111111","primaryBorderColor":"#111111","lineColor":"#888888","fontFamily":"ui-monospace, SFMono-Regular, Menlo, monospace","fontSize":"14px"},"flowchart":{"curve":"basis"}}}%%
flowchart TB
    classDef event fill:#ffffff,stroke:#111111,stroke-width:1.5px,color:#111111
    classDef project fill:#111111,stroke:#111111,stroke-width:2px,color:#ffffff

    A(("APR 2026<br/>STARTED AT 42")):::event
    B["JUN 2026<br/><b>parlementclair</b><br/>AI legal chatbot for the French<br/>National Assembly hackathon"]:::project
    C["JUL 2026<br/><b>epub-translator-vllm</b><br/>Self-hosted EPUB translator<br/>running Qwen3.5 on vLLM"]:::project

    A --> B --> C

    click B "https://github.com/tdi-rosa/parlementclair" _blank
    click C "https://github.com/tdi-rosa/epub-translator-vllm" _blank
