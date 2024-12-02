# Blue Theme by taikun114
![Blue Theme](https://github.com/user-attachments/assets/a21e509e-f01e-4500-8431-28becc646378)

## Screenshots

### Dashboard
#### Light
![Dashboard Light](https://github.com/user-attachments/assets/0888d6db-3e51-4a54-82c4-3586b5d88920)

#### Dark
![Dashboard Dark](https://github.com/user-attachments/assets/8079c2e0-e30c-432b-8ebf-4ff2baba072f)

### Map

#### Light
![Map Light](https://github.com/user-attachments/assets/cac7e54b-a92d-4877-8146-e675fcf70930)

#### Dark
![Map Dark](https://github.com/user-attachments/assets/867245d3-037d-4e28-833a-4915900c28d8)

### Logbook

#### Light
![Logbook Light](https://github.com/user-attachments/assets/6b26bddb-4777-45d4-bfe0-355aa0c166aa)

#### Dark
![Logbook Dark](https://github.com/user-attachments/assets/21e3c591-f9cb-4df4-86f0-4e639c8bf16d)

### History

#### Light
![History Light](https://github.com/user-attachments/assets/c4ae2ab5-32dd-44b8-a374-486f082a558d)

#### Dark
![History Dark](https://github.com/user-attachments/assets/f7aa09ea-c2a6-438d-be7d-bb1c982ccf53)

### Developer tools

#### Light
![Developer Tools Light](https://github.com/user-attachments/assets/8e76e670-bc02-4ed4-86d5-f8310f4d81e9)

#### Dark
![Developer Tools Dark](https://github.com/user-attachments/assets/696e538f-e998-4942-9347-2182a5049510)

### Configuration

#### Light
![Configuration Light](https://github.com/user-attachments/assets/37d30d59-c836-4598-b471-619426e9f5c1)

#### Dark
![Configuration Dark](https://github.com/user-attachments/assets/047f0c34-3713-4522-8b78-60a3e37fd00a)

### Profile

#### Light
![Profile Light](https://github.com/user-attachments/assets/279c28ed-beeb-4439-8660-057b7a7ca2ce)

#### Dark
![Profile Dark](https://github.com/user-attachments/assets/63a3750b-6629-4c11-a0a0-ad9539a853f3)

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

Go to Home Assistant Settings -> Dashboards -> Resources and add resources with the following settings:

#### URL:
```
https://fonts.googleapis.com/css2?family=Cousine:wght@400;700&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Noto+Sans+JP:wght@100..900
```

#### Resource type:
Select `Stylesheet`

### Installation

1. Go to the Community Store.
2. Click on the icon in the upper right corner and open “Custom repositories”.
3. In the `Repository` section, add this: `https://github.com/taikun114/Blue-Theme-by-taikun114`
4. In the `Type` section, select `Theme` then click `ADD`
5. Click `Blue Theme by taikun114` and click `Download`
6. Go to Profile Settings, change to the downloaded theme, and you're done!
