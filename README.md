Node Exporter
=========

Ansible role to install Node Exporter on Amazon Linux 2023

Requirements
------------

This role only works on Amazon Linux 2023 with ARM64 processors

Role Variables
--------------

| Name               | Default       | Description                                  |
|--------------------|---------------|----------------------------------------------|
| version            | 1.7.0         | Software version to install                  |
| node_exporter_user | node_exporter | User to be used to run node exporter service |
