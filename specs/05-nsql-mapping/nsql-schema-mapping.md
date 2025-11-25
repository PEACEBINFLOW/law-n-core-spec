# N-SQL Schema Mapping (Draft)

This doc defines how Law-N concepts map into N-SQL tables and views.

Examples:

- `network.routes`
- `network.devices`
- `network.towers`
- `network.patterns`

The goal is to make it possible to write queries like:

```sql
SELECT *
FROM network.routes
WHERE device_id = '0xA4C1'
  AND latency_ms < 50
  AND g_layer = '5G';
