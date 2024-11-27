# Mainsail Theme Setup

## Connect to SSH

First, launch your SSH client, in my case it's [Putty](https://www.putty.org/).

<div align="left"><img src="https://docs2.zerog.one/images/other/mainsail/theme/step1.png" alt=""></div>

Then enter your Raspberry’s local IP address in the “Host” or “Server” field.

Follow the prompts to connect to your Raspberry. Note that your local IP address may differ from the one used in the example.

### SSH Console

Your console should look similar to this

<div align="left"><img src="https://docs.zerog.one/assets/images/howto/theme/step2.png" alt=""></div>

### Execute Commands

```bash
cd ~/
git clone https://github.com/ZeroGDesign/zerog-mainsail-theme.git
bash ~/zerog-mainsail-theme/install.sh
```

Copy

If done correctly out would look somewhat like this image:

<div align="left"><img src="https://docs.zerog.one/assets/images/howto/theme/step3.png" alt=""></div>

{% hint style="info" %}
The input field still shows a command we have to run, press **ENTER** on your keyboard to run the command.
{% endhint %}

Once executed, your console should display the message ‘_Theme has been installed, have fun!_’ indicating that this step is now complete.

<div align="left"><img src="https://docs2.zerog.one/images/other/mainsail/theme/step4.png" alt=""></div>

***



### Config Files

Locate the file ‘_moonraker.conf_’ and click on it.

![](https://docs2.zerog.one/images/other/mainsail/theme/step6.png)

### Theme Update Script

Scroll down until you find the text _\[update\_manager]_.

If you see an additional line that reads “enable\_auto\_refresh: True”, do not remove it. Simply proceed to the next line. Note that this line may not be present for all users.

<div align="left"><img src="https://docs2.zerog.one/images/other/mainsail/theme/step7.png" alt=""></div>

Insert the following code

```django
[update_manager client ZeroGTheme]
type: git_repo
path: ~/zerog-mainsail-theme
origin: https://github.com/ZeroGDesign/zerog-mainsail-theme.git
install_script: install.sh
is_system_service: False
```

Copy

Your configuration should now somewhat look like the following:

<div align="left"><img src="https://docs2.zerog.one/images/other/mainsail/theme/step8.png" alt=""></div>

***

## Saving Changes

Click on the **Save & Restart** button.

<div align="left"><img src="https://docs2.zerog.one/images/other/mainsail/theme/step9.png" alt=""></div>

***

## Restart Moonraker

If a notification appears asking you to **try again**, click on it to proceed.

<div align="left"><img src="https://docs2.zerog.one/images/other/mainsail/theme/step10.png" alt=""></div>

### Refresh your Browser

Refresh your browser to check if the ZeroG theme is now visible.

<div align="left"><img src="https://docs2.zerog.one/images/other/mainsail/theme/step11.png" alt="test"></div>

### Update Manager

On the right-hand side, you will see the **Update Manager**. You should now notice that **ZeroGTheme** has been added. This will enable you to easily obtain the latest updates as they become available for the ZeroG Mainsail Theme.

![](https://docs2.zerog.one/images/other/mainsail/theme/step12.png)

***

## Enjoy

![](https://docs2.zerog.one/images/other/mainsail/theme/step13.png)
