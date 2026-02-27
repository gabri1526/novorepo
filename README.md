# novorepo
Este é un exemplo para o exercicio de crear repo en github
# 🚀 Dominando o Fluxo Markdown

Benvidos ao meu repositorio de prácticas. Aquí documento como configurar un contorno de traballo profesional para escribir documentación técnica.

## 🛠️ Ferramentas Configuradas
* **Editor:** VS Code & Nano (para edición rápida en terminal).
* **Linter:** Regras de estilo para evitar saltos de cabeceiras e espazos extra.
* **Render:** Markdown Preview Enhanced para soporte de Jupyter e Mermaid.
* **Exportación:** Markdown PDF sen cabeceiras nin pés de páxina automáticos.

## 📊 O meu Fluxo de Traballo
```mermaid
graph LR
    A[Escrita en Nano/VSCode] --> B{Pasar Linter}
    B -- Erros --> C[Corrixir Formato]
    C --> B
    B -- OK --> D[Previsualizar MPE]
    D --> E[Exportar PDF Limpo]
