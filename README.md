# Midnight theme for Home Assistant

The midnight theme for [Home Assistant]. For background on this project please
see the Home Assistant Community [forum thread](https://community.home-assistant.io/t/midnight-theme/)
forums.

![midnight theme](example.png)

# Usage

Add themes in the Home Assistant configuration for the frontend. See the
documentation for [configuring themes](https://www.home-assistant.io/integrations/frontend/#themes)
for more information.

You can include the `midnight.yaml` file from this project in your Home
Assistant `/config` directory. Then edit your `configuration.yaml` according to
the example below.

```yaml
# configuration.yaml

frontend:
  themes:
    midnight: !include themes/midnight.yaml
```

[Home Assistant]: https://www.home-assistant.io/

# Credits

Thank you to [Marcel Hoffs](https://community.home-assistant.io/u/marcelhoffs)
for creating the original theme.
