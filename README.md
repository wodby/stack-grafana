# Grafana application stack for Kubernetes on Wodby

Deploy Grafana applications on Kubernetes with Wodby.

This repository defines the Wodby stack manifests and default service
composition for Grafana.

<!-- wodby:generated:start -->

## Stack contract

- [Grafana stack on Wodby](https://wodby.com/stacks/grafana)
- [Browse Wodby application stacks](https://wodby.com/stacks)
- [Wodby stack documentation](https://wodby.com/docs/2.0/stacks/)
- [Stack manifest reference](https://wodby.com/docs/2.0/stacks/template/)

## Service definitions

- [Grafana service](https://github.com/wodby/service-grafana)

## What's included

| Component / service | Default configuration |
| --- | --- |
| Grafana<br>`grafana` | required; enabled by default; volumes: `data` 10 GB |

Enabled optional services are selected by default but can be excluded when an
app is created. Disabled optional services are available but not selected by
default. Required services cannot be excluded.

## Validate the stack manifest

```bash
wodby stack validate-manifest stack.yml --org <org-id>
```

<!-- wodby:generated:end -->
