# Diagrams (Sanitized)

All diagrams use mock terminology. They are written in Mermaid so GitHub can render them directly.

## Files
1. **01_system_architecture.mmd** — High-level architecture of sources, pipeline, enrichment, and consumers.
2. **02_data_flow_sequence.mmd** — End-to-end sequence from alerts to analyst.
3. **03_common_schema.mmd** — Data model for Event, Cluster, Indicators, and Enriched fields.
4. **04_correlation_logic.mmd** — Flow of correlation with keys and time-window gating.
5. **05_mitre_coverage.mmd** — Example tactics/techniques covered in the demo.
6. **06_dashboard_tabs.mmd** — How the dashboard tabs interlink with stored data.

> Tip: To export PNG/SVG, use Mermaid CLI or VS Code Mermaid preview. Example:
> ```bash
> mmdc -i 01_system_architecture.mmd -o 01_system_architecture.png
> ```
