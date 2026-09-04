# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

An Ansible Galaxy role (`dragonde.lubuntu`) to configure Lubuntu, created Nov/2014. Standard Ansible role layout.

## Layout

Standard Ansible role structure: `tasks/`, `handlers/`, `defaults/`, `vars/`, `files/`, `meta/`.

## Usage

```yaml
- hosts: lubuntu
  roles:
    - { role: dragonde.lubuntu }
```
