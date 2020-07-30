# Home Assistant Add-on: SNMP server

## How to use

1. Set the `domain` option, e.g., `mynetwork.local`.
2. Save the add-on configuration by clicking the "SAVE" button.
3. Start the add-on.

## Configuration

The SNMP server add-on can be changed to your likings. This section
describes each of the add-on configuration options.

Example add-on configuration:

```yaml
community: public
```

### Option: `community`

The community your SNMP monitor is looking for, eg `public`

## Support

In case you've found a bug, please [open an issue on my GitHub][issue].

[issue]: https://github.com/darthsebulba04/hassio-snmpd/issues
[repository]: https://github.com/darthsebulba04/hassio-snmpd/
