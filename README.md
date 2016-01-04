# Ansible Role: Beetbox CakePHP

An Ansible role that creates a CakePHP project on beetbox.

## Requirements

This role is specifically developed as an extension to beetbox -- https://github.com/drupalmel/beetbox

## Role Variables

Available variables are listed below, along with default values:

Create new CakePHP project.

    cake_create_project: no
    
CakePHP version. Composer compatible version, leave blank to use the latest version.

    cake_version: "*"

## Dependencies

- Beetbox -- https://github.com/drupalmel/beetbox

## License

MIT