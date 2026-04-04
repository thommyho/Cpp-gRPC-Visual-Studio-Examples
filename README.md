# gRPC C++ Examples for Windows (v1.80.0)

This directory contains Visual Studio–friendly variants of the official gRPC C++ examples.

## Available examples

| Example | Upstream path | Commit | Author | Date |
|--------|---------------|--------|--------|------|
| [auth](./auth/README.md) | `examples\cpp` | `339906443b` | Craig Tiller | Wednesday, October 15, 2025 |
| [cancellation](./cancellation/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [compression](./compression/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [deadline](./deadline/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [debugging](./debugging/README.md) | `examples\cpp` | `423d678b01` | Adam Heller | Wednesday, April 30, 2025 |
| [error_details](./error_details/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [error_handling](./error_handling/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [flow_control](./flow_control/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [generic_api](./generic_api/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [health](./health/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [helloworld](./helloworld/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [interceptors](./interceptors/README.md) | `examples\cpp` | `339906443b` | Craig Tiller | Wednesday, October 15, 2025 |
| [keepalive](./keepalive/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [load_balancing](./load_balancing/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [metadata](./metadata/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [retry](./retry/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |
| [route_guide](./route_guide/README.md) | `examples\cpp` | `339906443b` | Craig Tiller | Wednesday, October 15, 2025 |
| [wait_for_ready](./wait_for_ready/README.md) | `examples\cpp` | `95a1de4935` | Yash Tibrewal | Thursday, March 27, 2025 |

Here is your content prepared and structured for Markdown:

---

## ⚠️ gci.commands.test.commands.examples – Warning Summary

**Generated:** 19
**Skipped:** 24

Skipped examples:

```
csm_client
csm_server
debugging_server
client_flow_control_server
server_flow_control_client
gcp_observability_client
gcp_observability_server
xds_greeter_server
orca_server
codelab_callback_client
codelab_callback_server
greeter_callback_solution_client
greeter_callback_solution_server
ostream_greeter_callback_client
ostream_greeter_callback_server
otel_greeter_callback_client
otel_greeter_callback_server
reflection_server
systemd_socket_activation_client
systemd_socket_activation_server
unix_abstract_sockets_client
unix_abstract_sockets_server
xds_greeter_client
xds_greeter_server
```

> ⚠️ The skipped examples will **not** be included in the generated Visual Studio solution,
> but they are still available in the destination directory.

---

## ❌ Detailed Skip Reasons

### Missing `grpcpp/ext/csm_observability.h`

* `csm_client`
* `csm_server`

### Missing `grpcpp/ext/admin_services.h`

* `debugging_server`
* `xds_greeter_server`

### Missing `grpcpp/ext/gcp_observability.h`

* `gcp_observability_client`
* `gcp_observability_server`

### Missing `grpcpp/ext/orca_service.h`

* `orca_server`

### Missing `grpcpp/ext/otel_plugin.h`

*(OpenTelemetry plugin not available)*

* `codelab_callback_client`
* `codelab_callback_server`
* `greeter_callback_solution_client`
* `greeter_callback_solution_server`
* `ostream_greeter_callback_client`
* `ostream_greeter_callback_server`
* `otel_greeter_callback_client`
* `otel_greeter_callback_server`

### Missing `examples/protos/helloworld.grpc.pb.h`

*(PR required for gRPC / Unix-only features)*

* `reflection_server`
* `systemd_socket_activation_client` *(Unix-only feature)*
* `systemd_socket_activation_server` *(Unix-only feature)*
* `unix_abstract_sockets_client` *(Unix-only feature)*
* `unix_abstract_sockets_server` *(Unix-only feature)*
* `xds_greeter_client`
* `xds_greeter_server`

### Compilation Errors

**`client_flow_control_server`**

```
client_flow_control_server.cc(60,5): error C3861: 'sleep': identifier not found
```

**`server_flow_control_client`**

```
server_flow_control_client.cc(64,5): error C3861: 'sleep': identifier not found
```
