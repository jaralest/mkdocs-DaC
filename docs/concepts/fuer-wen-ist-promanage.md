# Für wen ist ProManage?

ProManage ist eine Softwarelösung für mittelständige Unternehmen mit mehreren Teams. Sie dient der Unterstützung von Projektmanagern und Marketingabteilungen bei ihrer täglichen Arbeit.

1. Das ist ein Test zwei

!!! danger "Warnung"
      Hier ist was schiefgelaufen.

Collapsible admonition:

??? tip "Warnung (ausklappbar)"
      Hier ist was schiefgelaufen. Aber wenigstens kann man es aufklappen.

## Sequence Diagrams

!!! info "Info"
      Mermaid-Diagramm benötigt eine Markdown-Extension.

```mermaid
sequenceDiagram
  autonumber
  Server->>Terminal: Send request
  loop Health
      Terminal->>Terminal: Check for health
  end
  Note right of Terminal: System online
  Terminal-->>Server: Everything is OK
  Terminal->>Database: Request customer data
  Database-->>Terminal: Customer data
```

