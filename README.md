# Ansible Role: Install system libraries

Install a set of system libraries required for CCDC C++ builds.

Applying this role will set up the system-level libraries required to compile CCDC applications.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ccdc.cpp_required_system_libraries

## License

MIT / BSD

## Author Information

This role was created in 2020 by Claudio Bantaloukas, based on existing roles at CCDC, by Jeff Geerling and google searches