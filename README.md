# GasMind Knowledge Base

Knowledge base for the [Nextruments / GasMind agent platform](https://www.nextruments.com/), developed by Heng Zhang.

面向气体检测与工业仪器选型，包含本体、仪器实例、检测对象、检测原理、行业场景及关系数据。

## Data

| Directory | Contents |
| --- | --- |
| `data/ontology/` | Ontology nodes and relations |
| `data/instances/` | Instrument, gas, principle, industry and scenario instances, plus instance relations |

CSV files retain Neo4j bulk-import column headers (`:ID`, `:LABEL`, `:START_ID`, `:END_ID`, `:TYPE`). Contact information and credential-like strings have been redacted for this public release.
