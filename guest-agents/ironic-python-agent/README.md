# ironic-python-agent extension


## Installation

See [Installing Extensions](https://github.com/siderolabs/extensions#installing-extensions).

## Testing

Confirm extension service is running

```bash
$ talosctl service ext-ironic-python-agent
NODE     192.168.1.1
ID       ext-ironic-python-agent
STATE    Running
HEALTH   ?
EVENTS   [Running]: Started task ext-ironic-python-agent (PID 1941) for container ext-ironic-python-agent (4s ago)
         [Preparing]: Creating service runner (4s ago)
         [Preparing]: Running pre state (4s ago)
         [Waiting]: Waiting for service "cri" to be "up" (5s ago)
         [Waiting]: Waiting for service "containerd" to be "up", service "cri" to be registered, file "/dev/virtio-ports/org.qemu.guest_agent.0" to exist (6s ago)
         [Waiting]: Waiting for service "containerd" to be registered, service "cri" to be registered, file "/dev/virtio-ports/org.qemu.guest_agent.0" to exist (8s ago)
         [Waiting]: Waiting for service "containerd" to be "up", service "cri" to be "up", file "/dev/virtio-ports/org.qemu.guest_agent.0" to exist (9s ago)
```
