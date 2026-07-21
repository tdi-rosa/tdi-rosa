```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#ffffff","primaryTextColor":"#111111","primaryBorderColor":"#111111","lineColor":"#888888","fontFamily":"ui-monospace, SFMono-Regular, Menlo, monospace","fontSize":"14px"},"flowchart":{"curve":"basis"}}}%%
flowchart BT
    classDef event fill:#ffffff,stroke:#111111,stroke-width:1px,color:#111111
    classDef project fill:#111111,stroke:#111111,stroke-width:2px,color:#ffffff

    A(["APR 2026 — Started at 42 (Paris)"]):::event
    B["JUN 2026 — parlementclair<br/>AI legal chatbot for the French<br/>National Assembly hackathon"]:::project
    C["JUL 2026 — epub-translator-vllm<br/>Self-hosted EPUB translator<br/>running Qwen3.5 on vLLM"]:::project

    A --> B --> C
```

- **[parlementclair](https://github.com/tdi-rosa/parlementclair)** — AI legal chatbot (hackathon Assemblée nationale)
- **[epub-translator-vllm](https://github.com/tdi-rosa/epub-translator-vllm)** — traducteur EPUB self-hosted, Qwen3.5 sur vLLM
