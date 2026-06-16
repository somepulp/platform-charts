# platform-charts

Shared Helm chart library for all application workloads running on the platform. 

Provides reusable, parameterized charts that enforce consistent standards across services — covering deployment patterns, resource configuration, ingress, health checks, and observability instrumentation.

Responsible for: Helm chart definitions for all application types, chart versioning and releases, and enforcing platform-wide standards for how workloads are packaged and configured.

Does not manage: environment-specific values or deployment targets (see `platform-deploy`), platform service charts (see `platform-components`), or application source code (see individual app repos).