# Componentization Perf Test Results

| Component         | Configuration         | Throughput (EPS/core) | Memory Usage |
|-------------------|-----------------------|--------------------|-----------------------|
| In-Process Plugin    |   tools/pipeline_perf_test/system_under_test/otel-collector/collector-out-of-process.yaml  | 232.33k/sec             | 257MB      | 
| Out-of-Process Plugin    | tools/pipeline_perf_test/system_under_test/otel-collector/collector-manifest.yaml       | 58.50k/sec         | 519MB (combined memory for parent & child)             | 

