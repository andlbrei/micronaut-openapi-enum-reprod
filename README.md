## Micronaut 4.6.2

Micronaut OpenAPI Generator generates an empty shell of an enum class when `if/then` is present to conditionally require a field when validating.
Removing `if/then` results in a correct enum representation.

Run `./gradlew :generateServerOpenApiModels`
