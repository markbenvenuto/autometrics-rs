# Autometrics + Custom Metrics Example

This example demonstrates how you can collect custom metrics in addition to the ones generated by autometrics.

## Running the example

### Using the `opentelemetry` crate

```shell
cargo run -p example-custom-metrics --features=opentelemetry-0_20
```

### Using the `metrics` crate

```shell
cargo run -p example-custom-metrics --features=metrics-0_24
```

### Using the `prometheus` crate

```shell
cargo run -p example-custom-metrics --features=prometheus-0_13
```
