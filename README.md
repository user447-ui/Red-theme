# Blue Theme by taikun114
![Blue Theme](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Blue%20Theme.png)

## Screenshots

### Dashboard
#### Light
![Dashboard Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Dashboard%20Light.png)

#### Dark
![Dashboard Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Dashboard%20Dark.png)

### Map

#### Light
![Map Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Map%20Light.png)

#### Dark
![Map Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Map%20Dark.png)

### Logbook

#### Light
![Logbook Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Logbook%20Light.png)

#### Dark
![Logbook Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Logbook%20Dark.png)

### History

#### Light
![History Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/History%20Light.png)

#### Dark
![History Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/History%20Dark.png)

### Developer tools

#### Light
![Developer Tools Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Developer%20Tools%20Light.png)

#### Dark
![Developer Tools Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Developer%20Tools%20Dark.png)

### Configuration

#### Light
![Configuration Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Configuration%20Light.png)

#### Dark
![Configuration Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Configuration%20Dark.png)

### Profile

#### Light
![Profile Light](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Profile%20Light.png)

#### Dark
![Profile Dark](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/docs/Profile%20Dark.png)

## Installation

### Using the theme for the first time

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  themes: !include_dir_merge_named themes
```
If it already exists, nothing needs to be done.

### Fonts setup
To use the fonts specified in this theme, you need to add a resource from the Dashboard Settings.

Go to Home Assistant `Settings` -> `Dashboards` -> `Resources` and add resources with the following settings:

#### URL:
```
https://fonts.googleapis.com/css2?family=Cousine:wght@400;700&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Noto+Sans+JP:wght@100..900
```

#### Resource type:
Select `Stylesheet`

### HACS

1. Go to the Community Store.
2. Click on the icon in the upper right corner and open `Custom repositories`.
3. In the `Repository` section, add this: `https://github.com/taikun114/Blue-Theme-by-taikun114`
4. In the `Type` section, select `Theme` then click `ADD`
5. Click `Blue Theme by taikun114` and click `Download`
6. Go to Profile Settings, change to the downloaded theme, and you're done!

### Manual

1. Download this theme file: [Blue-Theme-by-taikun114.yaml](https://raw.githubusercontent.com/taikun114/Blue-Theme-by-taikun114/main/themes/Blue-Theme-by-taikun114.yaml)
2. Open the `themes` folder in the Home Assistant config folder and create a folder named `Blue-Theme-by-taikun114` in it.
3. Put the `Blue-Theme-by-taikun114.yaml` that you just downloaded into the folder you created.
4. Open the Home Assistant Developer tools and click on `ALL YAML CONFIGURATION` under `YAML CONFIGURATION RELOADING`
5. Go to Profile Settings, change to the downloaded theme, and you're done!

## Important
This theme changes the spacing of [Mushroom](https://github.com/piitaya/lovelace-mushroom) Title Card.
Please note that this may result in a slightly broken layout if you are using Mushroom Title Card.

If you do not want the layout to be broken, remove the code specified in `Spacing` in `Mushroom Card Specific` in the theme file.

The theme file will be reset each time you update the theme.
So please note that you will need to follow the same procedure each time you update the theme.
