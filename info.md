# Ugly Christmas Theme
Ugly Christmas Theme that over time has evolved into a more beautifulish christmassy theme.

## Installation

### Preparation
1. Make sure that under the **configuration.yaml** file you have the following:

```yaml
frontend:
  themes: !include_dir_merge_named themes/
```

2. Under the Home Assistant **Config** folder, create a new folder named **themes**
3. **Restart** Home assistant to apply the changes.

### HACS installation
1. Within the Community Store (HACS) search for "Ugly Christmas Theme"
2. Open the Theme
3. Press the "Install" button
4. Restart Home-Assistant or reload your themes
5. Apply the theme from within your profile settings or set it as backend-selected theme.

## Screenshots
### Dark Mode
#### Overview
![Theme - Overview](./docs/dark/theme-overview.png)
#### More info popup
![Theme - Overview](./docs/dark/theme-overview-ac.png)
#### Automation Editor
![Theme - Overview](./docs/dark/theme-automation-editor.png)
#### Map
![Theme - Configuration](./docs/dark/theme-map.png)
### Light Mode
#### Overview
![Theme - Overview](./docs/light/theme-overview.png)
#### More info popup
![Theme - Overview](./docs/light/theme-overview-ac.png)
#### Automation Editor
![Theme - Overview](./docs/light/theme-automation-editor.png)
#### Map
![Theme - Configuration](./docs/light/theme-map.png)
