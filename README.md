# akko-themes
A repository for my Akkoma themes.

## how to use
You can download whichever files you like and upload them under Settings > Theme > Load Preset and then load the file.

## how to upload if you're an admin
Navigate to your static folder. If you're using YunoHost, this will be /home/yunohost.app/akkoma/static
```
cd (WHATEVER THE PATH IS)/static
```
Create your themes folder if you haven't already and then enter it.
```
mdkir themes
cd themes
```
Clone this repository into it.
```
git clone https://github.com/pinkgator/akko-themes
```
Open the styles.json file for editing. For YunoHost folks this is /home/yunohost.app/akkoma/static/styles.json
```
vi (WHATEVER THE PATH IS)/static/styles.json
```
Add the following to it inside the brackets:
```
"vampyr": "/static/themes/akko-themes/theme_vampyr.json",
"neon-lights": "/static/themes/akko-themes/theme_neonlights.json"
```
