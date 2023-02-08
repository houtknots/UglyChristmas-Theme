# Ugly Christmas Theme
> Ugly Christmas Theme based on Clear Theme Dark https://community.home-assistant.io/t/clear-theme-dark/100960

## Screenshots
### Overview
![Theme - Overview](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-overview.png)
### Logbook
![Theme - Overview](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-logbook.png)
### Developer Tools
![Theme - Overview](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-developer-tools.png)
### Configuration
![Theme - Configuration](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-configuration.png)
### Profile
![Theme - Configuration](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-profile.png)
### Map
![Theme - Overview](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-map.png)

## Installation

### Preparation
1. Make sure that under the **configuration.yaml** file you have the following:

```yaml
frontend:
  themes: !include_dir_merge_named themes/
```

2. Within the Home Assistant **Config** folder, create a new folder named **themes**
3. **Restart** Home assistant to apply the changes.

### HACS installation
1. Within the Community Store (HACS) search for "Ugly Christmas Theme"
2. Open the Theme
3. Press the "Install" button
4. Restart Home-Assistant or reload your themes
5. Apply the theme from within your profile settings or set it as backend-selected theme.

### Manual installation
1. Within the Home assistant **themes** folder, create a file named `uglychristmas.yaml`
2. In this GitHub repo, go into the **themes** folder, open the `uglychristmas.yaml` file and copy the contents
3. Paste the contents in the `uglychristmas.yaml` file created under your Home Assistant themes folder
4. Restart Home-Assistant or reload your themes
5. Apply the theme from within your profile settings or set it as backend-selected theme.
