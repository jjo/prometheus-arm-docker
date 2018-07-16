[![Build
Status](https://travis-ci.org/jjo/prometheus-arm-docker.svg?branch=master)](https://travis-ci.org/jjo/prometheus-arm-docker)
# Prometheus ARM Docker Images

Forked from the original great work by
<https://github.com/jjo/prometheus-arm-docker>

ARM [Docker][docker] images for [Prometheus][prometheus] for
deployment on Raspberry Pi and similar boards.

All images use the official release binaries, downloaded from the
[Prometheus download page][prom-downloads], and default/sample
configurations. The images are also designed to match the [official
x86 Docker images][prom-docker].

No hardcorded version (only major release(s) per directory), see
`Makefile.common` and e.g. `prometheus-v1/Makefile`.

## Docker images built:

| Binary     | ARM 32  | ARM 64 |
| ---------- | ------- | ------ |
| prometheus | [xjjo/armv7-prometheus](https://hub.docker.com/r/xjjo/armv7-prometheus) | [xjjo/armv7-prometheus](https://hub.docker.com/r/xjjo/arm64-prometheus) |
| alertmanager | [xjjo/armv7-alertmanager](https://hub.docker.com/r/xjjo/armv7-alertmanager) | [xjjo/armv7-alertmanager](https://hub.docker.com/r/xjjo/arm64-alertmanager) |
| pushgateway | [xjjo/armv7-pushgateway](https://hub.docker.com/r/xjjo/armv7-pushgateway) | [xjjo/armv7-pushgateway](https://hub.docker.com/r/xjjo/arm64-pushgateway) |
| node_exporter | [xjjo/armv7-node_exporter](https://hub.docker.com/r/xjjo/armv7-node_exporter) | [xjjo/armv7-node_exporter](https://hub.docker.com/r/xjjo/arm64-node_exporter) |
| blackbox_exporter | [xjjo/armv7-blackbox_exporter](https://hub.docker.com/r/xjjo/armv7-blackbox_exporter) | [xjjo/armv7-blackbox_exporter](https://hub.docker.com/r/xjjo/arm64-blackbox_exporter) |

[docker]: https://www.docker.com
[prometheus]: https://prometheus.io/
[prom-downloads]: https://prometheus.io/download/
[prom-docker]: https://hub.docker.com/r/prom/
