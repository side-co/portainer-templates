# App Templates

This repository hosts unofficials templates (**'Apps Templates'**) definitions for portainer.

Documentation is available [ReadTheDocs](http://portainer.readthedocs.io/en/latest/templates.html) for more information about the template definition format and how to deploy your own templates.

## Portainer templates

### Tracing Services

This will run these services:

- `jaegertracing/all-in-one:latest`
- `omnition/opencensus-collector:latest`
- `omnition/opencensus-agent:latest`

```sh
cd stacks/tracing ; docker stack deploy -c docker-stack.yml tracing
```
