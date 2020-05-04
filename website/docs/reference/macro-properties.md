---
title: Macro properties
---

Macros may be described in the `source-paths` or `macro-paths` directories configured in your `dbt_project.yml` file.

```yml
version: 2

macros:
  - name: <macro name>
    [description](description): <markdown_string>
    arguments:
      - name: <arg name>
        type: <arg type>
        [description](description): <markdown_string>
      - ...
  - ...

```