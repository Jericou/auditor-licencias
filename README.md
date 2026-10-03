# Auditor de Facturación — licencias

Lista **pública y firmada** de licencias o copias suspendidas por el proveedor del programa.

- `bloqueos.json` solo contiene **identificadores** (sin nombres, sin datos de pacientes, sin motivos).
- Está firmada con una clave que solo tiene el proveedor: los programas comprueban la firma antes de creerle a la lista.
- El programa solo **lee** este archivo al abrir; no envía nada.
