## cscli scenarios remove

Remove given scenario(s)

### Synopsis

remove given scenario(s)

```
cscli scenarios remove [config] [flags]
```

### Examples

```
cscli scenarios remove crowdsec/xxx crowdsec/xyz
```

### Options

```
      --all     Delete all the files in selected scope
  -h, --help    help for remove
      --purge   Delete source file in ~/.cscli/hub/ too
```

### Options inherited from parent commands

```
  -b, --branch string   Use given branch from hub
  -c, --config string   path to crowdsec config file (default "/etc/crowdsec/config.yaml")
      --debug           Set logging to debug.
      --error           Set logging to error.
      --info            Set logging to info.
  -o, --output string   Output format : human, json, raw.
      --trace           Set logging to trace.
      --warning         Set logging to warning.
```

### SEE ALSO

* [cscli scenarios](cscli_scenarios.md)	 - Install/Remove/Upgrade/Inspect scenario(s) from hub

