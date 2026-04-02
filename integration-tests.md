
**We have a multi-domain application with multiple repositories per domain.
For a given domain, generate a high-level integration/service-layer test plan. The output should identify:**

1. **Core business flows** in the domain.
2. **Internal dependencies** (APIs, services, queues, cache, shared libs) required for the flow.
3. **External integrations** (3rd-party APIs, payment, auth, storage) required.
4. **Data required** (sample payloads, fixtures, DB tables, migrations).
5. **Events or async interactions** (Kafka/SQS/pubs/subs, cron jobs, webhooks).
6. **Test strategy**

   * Integration tests
   * Service layer tests
   * Contract tests
   * Mocks vs actual services
7. **Test environment needs**

   * Env variables
   * Dockerized services
   * Secrets/config
   * Any stubs/localstack/wiremock requirements
8. **Edge cases** that must be covered.
9. **Risks & missing information** that must be clarified.

Provide the result in a structured format:

* **Business Flow Summary**
* **Internal Integration Map**
* **External Integration Map**
* **Data/Fixtures Needed**
* **Test Coverage Checklist**
* **Environment Needs**
* **Open Questions**

Ask follow-up questions if anything is missing.
