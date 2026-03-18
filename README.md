# ReDoc

ReDoc is an open-source API documentation renderer for OpenAPI specifications, originally created by Rebilly and now maintained by Redocly. It generates a responsive three-panel documentation layout from OpenAPI 3.1, 3.0, and Swagger 2.0 definitions. The left panel provides a search bar and navigation menu, the central panel displays the documentation content, and the right panel shows request and response examples.

ReDoc is available as a CLI tool, HTML tag, React component, and Docker image. It supports rich vendor extensions such as `x-tagGroups`, `x-logo`, `x-codeSamples`, `x-badges`, and `x-traitTag` for advanced customization of the rendered documentation.

- **Website:** https://redocly.com/redoc
- **Documentation:** https://redocly.com/docs/redoc
- **GitHub:** https://github.com/Redocly/redoc
- **Live Demo:** https://redocly.github.io/redoc/
- **npm:** https://www.npmjs.com/package/redoc

## API Artifacts

| Artifact | Type | Description |
|---|---|---|
| [redoc-configuration-schema.json](json-schema/redoc-configuration-schema.json) | JSON Schema | Full schema for all ReDoc configuration options including functional settings and theme options |
| [redoc-context.jsonld](json-ld/redoc-context.jsonld) | JSON-LD | Linked data context mapping ReDoc entities to standard vocabularies |
