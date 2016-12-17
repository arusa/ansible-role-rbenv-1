# rbenv

rbenv install to `/opt/rbenv`

## Requirements

- Ubuntu
- Debian

## Role Variables

- `rbenv_root`: rbenv install location
- `rbenv_ruby_version`: global default ruby version
- `rbenv_packages`: rbenv depends packages

## Dependencies

None.

## Example Playbook

    ---
    - hosts: all
      become: yes
      roles:
      - znzj.rbenv

## License

MIT License
