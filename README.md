# multi-cluster-app-dispatcher
Holistic job manager on Kubernetes capable of (i) provides an abstraction for wrapping all resources of the job/application and treating them holistically, (ii) queuing job/application creation requests and applying different queuing policies, e.g., FIFO, Priority, (iii) dispatching the job to one of multiple clusters, where a queuing agent runs, using configurable dispatch policies, and (iv) auto-scaling pod sets balancing job demands and cluster availability (future work).

## Multi-Cluster-App-Dispatcher Build Information

Follow the build instructions [here](./doc/build/build.md) to build the Multi-Cluster-App-Dispatcher controller.
