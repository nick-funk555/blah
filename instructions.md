# Configuring the Qemu-guest-agent
## Installing tools
on Debian/Ubuntu based systems (with apt-get) run:

```apt-get install qemu-guest-agent```


on Redhat based systems (with yum):

```yum install qemu-guest-agent```


on SUSE Linux (with zypper):

```zypper install qemu-guest-agent```


## Enabling the guest tools

The guest agent might not start automatically after the installation.

Start the service

```systemctl start qemu-guest-agent```

Enable the service to autostart permanently

```systemctl enable qemu-guest-agent```
