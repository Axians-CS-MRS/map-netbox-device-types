# Netbox Device Types

A repository to store all device types to install.

## How to feed this repo?

You can contribute to the development of the list of the devices by feeding it.
To add a new device you need to:  
- create a new yaml file in the respective vendor directory with the `model` as `name`:
    example: Cisco/c9300-24t.yaml
- List the device components as follow:

```
manufacturer: Cisco
model: C9300-24T
part_number: C9300-24T
slug: c9300-24t
u_height: 1
is_full_depth: true
console_ports:
  - name: con 0
power_ports:
  - name: PS-1
interfaces:
  - name: GigabitEthernet1/0/1
```