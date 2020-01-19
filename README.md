# Ugly Christmas Theme
> Ugly Christmas Theme based on Clear Theme Dark https://community.home-assistant.io/t/clear-theme-dark/100960

## Screenshots
### Overview
![Theme - Overview](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-overview.png)
### Map
![Theme - Overview](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-map.png)
### Logbook
![Theme - Overview](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-logbook.png)
### History
![Theme - Overview](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-history.png)
### Developer Tools
![Theme - Overview](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-developer-tools.png)
### Configuration
![Theme - Configuration](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-configuration.png)
### Profile
![Theme - Configuration](https://raw.githubusercontent.com/houtknots/UglyChristmas-Theme/master/docs/theme-profile.png)

## Installation

### Preparation
1. Make sure that under the **configuration.yaml** file you have the following:

<pre>
frontend:
  themes: !include_dir_merge_named themes/
</pre>

2. Under the Home Assistant **Config** folder, create a new folder named **themes**
3. **Restart** Home assistant to apply the changes. 

### HACS installation
1. Go into the Community Store (HACS)
2. Search for "Ugly Christmas Theme"
3. Open the Theme 
4. Press the "Install" button
5. Restart Home-Assistant or reload your themes

### Manual installation
1. In the Home assistant **themes** folder, create a file named `uglychristmas.yaml`
2. In this GitHub repo, go into the **themes** folder, open the `uglychristmas.yaml` file and copy the content
3. Paste the content in the `uglychristmas.yaml` file created under your Home Assistant themes folder