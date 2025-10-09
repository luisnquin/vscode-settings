
# My VSCode settings

## Setup

```shell
# Install extensions
$ for id in $(curl https://raw.githubusercontent.com/luisnquin/vscode-settings/main/extensions.jsonc -s | jq -r '.[].identifier'); do code --install-extension "$id"; done
# Install settings
$ curl https://raw.githubusercontent.com/luisnquin/vscode-settings/main/settings.jsonc > ~/.config/Code/User/settings.json
```

## License

Soon, I guess.
