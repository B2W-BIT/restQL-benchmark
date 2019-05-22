The tests for the benchmark below are done using the getting started of the tools involved. No tuning or configuration changes were applied. The goal was to test the out of the box performance of the compared tools.

The environment used was one C5.large AWS instance which has the simplest configuration of the compute optimized line (2 vCPU and 4GB RAM). To create a consistent environment all services called by restQL or the tool were stubed using https://github.com/MachadoLhes/tanker-go. Tanker go allows to specify the response time of the request in the query string so that it mimics a real service.

We’ve used open source [vegeta](https://github.com/tsenart/vegeta) for the load test.

Response time

Average response time by load

Success percent

Average success by load