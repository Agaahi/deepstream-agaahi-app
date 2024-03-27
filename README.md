# DeepStream Agaahi App

## Usage Instructions

1. Ensure you have NVIDIA Graph Composer 3.1 installed.
2. Confirm that the path to "deepstream-agaahi-app" is "/opt/nvidia/deepstream/deepstream-6.4/sources/apps/composer_apps/deepstream-agaahi-app" on your device.
3. Follow the [DeepStream quickstart guide](https://docs.nvidia.com/metropolis/deepstream/dev-guide/text/DS_Quickstart.html) to ensure you can run the reference applications.
4. Run `gxf_server`.
5. Run the application.

### On x86:

```bash
$ /opt/nvidia/graph-composer/execute_graph.sh deepstream-agaahi-app.yaml \
      deepstream-agaahi-app.parameters.yaml -d ./configs/target_x86_64.yaml

```

### On Jetson:

```bash
$ /opt/nvidia/graph-composer/execute_graph.sh deepstream-agaahi-app.yaml \
      deepstream-agaahi-app.parameters.yaml -d ./configs/target_aarch64.yaml
```
