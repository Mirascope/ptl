# Prompt Templating Language (PTL)

> A standardized interface for writing and defining prompt templates that render as messages.

To think of a prompt template as a string is incorrect. The template defines a model-agnostic method through which you produce all the information necessary to get a response from an LLM.

The output of rendering a prompt template is not a string -- it's a list of messages.

This language templating specification aims to fix this.

## Client Implementations

### Python

[Mirascope](https://github.com/Mirascope/mirascope) implements the early version that spawned this spec.

We plan to update Mirascope to implement this updated spec as part of the `v2.0` release. See our [roadmap](https://github.com/Mirascope/mirascope/issues/896).

### TypeScript (and other languages)

Coming soon...

## Versioning

This project uses [Semantic Versioning](https://semver.org/).

## License

This project is licensed under the terms of the [MIT License](LICENSE).
