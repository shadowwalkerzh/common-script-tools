# common-script-tools
> A series of common scripts for developers, like tail logs for running docker containers, ssh advanced config.

# Features
## Tail logs for docker containers
> Install: ```curl -OfsSL https://raw.githubusercontent.com/shadowwalkerzh/common-script-tools/refs/heads/main/docker-log/taillog && sudo install -m 755 taillog /usr/local/bin/taillog && rm -f taillog```

## Advanced SSH config
> You can also use normal ssh login instead of call the tool, like `ssh work-github`

### Key Features:
- Multi-File Support: Reads both ~/.ssh/config and all *.config files under ~/.ssh/config.d/
- Smart Filtering: Automatically skips invalid entries (those without HostName)
- Flexible Description Parsing: Only recognizes #Desc

### Intuitive Interface:
- Numbered host list with IP and descriptions
- Input validation and error handling

