# replitcli

[![NPM](https://nodei.co/npm/replit.png)](https://nodei.co/npm/replit/)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FScoder12%2Freplitcli.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FScoder12%2Freplitcli?ref=badge_shield)

A command line interface for repl.it

## Current Commands

Usage:

```
Usage: replit [options] [command]

Options:
  -V, --version            output the version number
  -d, --debug              Enable debug logging
  -c, --config <filename>  Location of configuration file (default:
                           "~/.config/.replitcli.json")
  -h, --help               display help for command

Commands:
  auth [options]
  bash [repl]
  local <repl>
  run [repl]
  cp <src> <dest> [repl]   Copies a file from a repl to your computer or vice
                           versa. Prepend a path with repl: to
                           indicate it is on the repl.
```

## Future Plans

- exec command
- Recursive copy from remote
- Repl info command

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FScoder12%2Freplitcli.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FScoder12%2Freplitcli?ref=badge_large)
