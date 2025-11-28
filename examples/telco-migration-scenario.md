# Telco Migration Scenario (Sketch)

How a telco could adopt Law-N without ripping out everything:

1. Deploy Law-N nodes in parallel with existing routers.
2. Start by mirroring traffic and learning patterns.
3. Use FBRP only for a small class of traffic (e.g. IoT devices).
4. Gradually promote Law-N routes to "authoritative" for more categories.
5. Expose N-SQL to internal teams for debug and analytics.
