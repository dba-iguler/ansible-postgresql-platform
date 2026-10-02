# Ansible PostgreSQL Platform

Hands-on Ansible lab for PostgreSQL platform setup and automation.

## What I'm working on

- Linux base configuration
- PostgreSQL installation
- PostgreSQL configuration
- Patroni setup
- etcd setup
- HAProxy setup
- PgBouncer setup
- users and directories
- systemd services
- configuration templates
- repeatable server setup

## Planned structure

roles/
  common/
  postgres/
  patroni/
  etcd/
  haproxy/
  pgbouncer/

## Current goal

Use Ansible to turn fresh Linux servers into a working PostgreSQL HA platform with repeatable configuration.

This repo will grow as I move more manual setup steps into Ansible.
