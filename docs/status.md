---
title: Project Status | KubeDB
description: KubeDB Project Status
menu:
  docs_{{ .version }}:
    identifier: roadmap-cli
    name: Status
    parent: welcome
    weight: 15
menu_name: docs_{{ .version }}
section_menu_id: welcome
url: /docs/{{ .version }}/welcome/status/
aliases:
  - /docs/{{ .version }}/status/
---

# Project Status

## Versioning Policy

There are 2 parts to versioning policy:

 - Operator & cli version: KubeDB follows semver versioning policy. Until 1.0 release is done, there might be breaking changes between point releases of the operator. Please always check the release notes for upgrade instructions.
 - CRD version: `kubedb.com/v1alpha1` is considered in alpha. This means breaking changes to the YAML format might happen among different releases of the operator.
