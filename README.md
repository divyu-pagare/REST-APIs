## types of API
1. Open/Public - available for general use.
2. Partner - restricted to strategic business partners to communicate with each other.
3. Internal - available to the organization's internal developers.
4. Private - similar to internal API (the difference is in some cases they can be accessible outside of the organization).
5. Composite - set of requests in a single call. allow sending single request instead of multiple requests to sever.

## characteristics
1. stateful -
   - maintain client state between requests.
   - difficult to scale.
   - faster - because previous clients stored data.
   - careful handling of session data is necessary.
   - fault tolerance - loss of server can cause session data loss.
3. stateless -
   - treach each request as separate/independent.
   - more scalable.
   - faster for simple requests.
   - simple to develop and maintain.
   - Fault tolerance - loss of server does not impact user sessions.

