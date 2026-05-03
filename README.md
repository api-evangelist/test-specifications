# Test Specifications

Documentation that defines the requirements, procedures, and expected outcomes for testing software systems and APIs. Test specifications establish the criteria that implementations must satisfy, bridging the gap between product requirements and executable test cases. They include test plans, test case definitions, acceptance criteria, and conformance requirements. Effective use of this practice reduces bugs in production, supports contract testing, and enables a culture of quality-driven development aligned with OpenAPI, AsyncAPI, and JSON Schema standards.

**URL:** [https://en.wikipedia.org/wiki/Test_specification](https://en.wikipedia.org/wiki/Test_specification)

## Tags

- Acceptance Testing
- Contract Testing
- Documentation
- OpenAPI
- Quality Assurance
- Testing

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

| Name | Description |
|---|---|
| [OpenAPI Initiative](https://www.openapis.org/) | The de-facto standard for describing RESTful APIs; OpenAPI documents serve as machine-readable test specifications. |
| [AsyncAPI Initiative](https://www.asyncapi.com/) | Open specification standard for event-driven APIs used as test specification baseline for async contract testing. |
| [JSON Schema](https://json-schema.org/) | Vocabulary for annotating and validating JSON documents, used as payload specification in test cases. |
| [Gherkin / Cucumber BDD](https://cucumber.io/docs/gherkin/) | Plain-text Given-When-Then language for writing executable test specifications consumed by BDD frameworks. |
| [Pact Contract Testing](https://pact.io/) | Consumer-driven contract testing tool where consumers author pact specifications that providers verify against. |
| [Swagger Editor](https://editor.swagger.io/) | Web-based editor for designing OpenAPI specifications with real-time validation and mock server generation. |
| [Optic API](https://www.useoptic.com/) | Developer tool that tracks specification changes and validates live traffic against OpenAPI specs to detect contract drift. |
| [Spectral](https://stoplight.io/open-source/spectral) | JSON/YAML linter and specification validator enforcing OpenAPI and AsyncAPI ruleset compliance in CI/CD pipelines. |

## Artifacts

| Type | URL |
|---|---|
| JSON Schema | [test-specifications-schema.json](json-schema/test-specifications-schema.json) |
| JSON Structure | [test-specifications-structure.json](json-structure/test-specifications-structure.json) |
| JSON-LD Context | [test-specifications-context.jsonld](json-ld/test-specifications-context.jsonld) |
| Vocabulary | [test-specifications-vocabulary.yml](vocabulary/test-specifications-vocabulary.yml) |

## Examples

| Name | Description |
|---|---|
| [OpenAPI Test Specification Example](examples/test-specification-openapi-example.json) | Example test specification for an Orders API with contract test cases and conformance levels. |
