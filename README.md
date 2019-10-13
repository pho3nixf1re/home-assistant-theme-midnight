# DEPRECATED REPO

There is a new home assistant community [themes
organization](https://github.com/home-assistant-community-themes). This theme is
now [maintained
there](https://github.com/home-assistant-community-themes/midnight). This repo
is now deprecated but left here for posterity.

## Midnight theme for Home Assistant

The midnight theme for [Home Assistant]. For background on this theme please
see the Home Assistant Community [forum thread](https://community.home-assistant.io/t/midnight-theme/).

![midnight theme](example.png)

## Usage

### HACS

See new [community maintained repo](https://github.com/home-assistant-community-themes/midnight).

### Manual

Add this theme to your Home Assistant configuration for the frontend. See the
[documentation about custom
themes](https://www.home-assistant.io/integrations/frontend/#themes) for more
information.

1. Copy the `midnight.yaml` file from this project in your Home Assistant
   `/config/themes` directory.
2. Edit your `configuration.yaml` to include custom themes.

```yaml
# configuration.yaml

frontend:
  themes: !include_dir_merge_named themes
```

## Credits

Thank you to [Marcel Hoffs](https://community.home-assistant.io/u/marcelhoffs)
for creating the original theme.

[Home Assistant]: https://www.home-assistant.io/
