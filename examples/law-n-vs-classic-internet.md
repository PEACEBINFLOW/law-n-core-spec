# Law-N vs Classic Internet — Request Flow

## Classic CLFI Flow

1. App builds HTTP request.
2. Request goes through:
   - HTTP
   - TLS
   - TCP
   - IP
3. Routed via:
   - local router
   - ISP
   - backbone
   - data center
4. No one at the app layer knows:
   - which tower was used
   - what the signal looked like
   - how many retries happened.

## Law-N Flow (Conceptual)

1. App states an **intent**:
   - latency target
   - reliability
   - cost/energy preferences
2. Law-N:
   - picks a pattern
   - picks towers / satellites
   - uses FBRP to construct the route
3. CLSI places the workload based on:
   - current tower load
   - route patterns
4. App can query the path using N-SQL.
