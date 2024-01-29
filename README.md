Node Exporter
=========

Ansible role to install Node Exporter on

Requirements
------------

This role only works on ARM64 processors

Tested So
---------
- Amazon Linux 2023
- Ubuntu Server 22.04

Role Variables
--------------

| Name               | Default       | Description                                  |
|--------------------|---------------|----------------------------------------------|
| node_exporter_user | node_exporter | User to be used to run node exporter service |
