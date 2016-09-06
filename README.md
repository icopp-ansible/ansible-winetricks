# ansible-winetricks

Install the latest stable Winetricks via Homebrew.

## Dependencies

* [icopp.homebrew](https://github.com/icopp/ansible-homebrew)
* [icopp.wine](https://github.com/icopp/ansible-wine)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.winetricks
```

## License

MIT
