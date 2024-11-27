---
description: >-
  Steps for setting up the mainsail theme for your user interface. Complete the
  installation with the provided instructions and enjoy the improved visual
  experience.
---

# Mainsail Theme Setup

## Connect to SSH

{% stepper %}
{% step %}
### Launch your SSH client.

First, launch your SSH client, in my case it's [Putty](https://www.putty.org/).

<img src="https://docs2.zerog.one/images/other/mainsail/theme/step1.png" alt="" data-size="original">


{% endstep %}

{% step %}
### Sign in

Then enter your Raspberry’s local IP address in the “Host” or “Server” field.

Follow the prompts to connect to your Raspberry. Note that your local IP address may differ from the one used in the example.
{% endstep %}

{% step %}
### Check your SSH Console

Your console should look similar to this.

<img src="https://docs.zerog.one/assets/images/howto/theme/step2.png" alt="" data-size="original">


{% endstep %}
{% endstepper %}

### SSH Console & Commands

{% stepper %}
{% step %}
### Execute the following Commands

```bash
cd ~/
git clone https://github.com/ZeroGDesign/zerog-mainsail-theme.git
bash ~/zerog-mainsail-theme/install.sh
```
{% endstep %}

{% step %}
### Double check

If done correctly out would look somewhat like this

<img src="https://docs.zerog.one/assets/images/howto/theme/step3.png" alt="" data-size="original">

{% hint style="warning" %}
The input field still shows a command we have to run, press **ENTER** on your keyboard to run the command.
{% endhint %}
{% endstep %}

{% step %}
### Ran the Code

Once executed, your console should display the message ‘_Theme has been installed, have fun!_’ indicating that this step is now complete.

<img src="https://docs2.zerog.one/images/other/mainsail/theme/step4.png" alt="" data-size="original">
{% endstep %}
{% endstepper %}

## Dashboard

{% stepper %}
{% step %}
### Locate your Config Files

Locate the file ‘_moonraker.conf_’ and click on it.

<img src="https://docs2.zerog.one/images/other/mainsail/theme/step6.png" alt="" data-size="original">
{% endstep %}

{% step %}
### Adding Them Update Script

Scroll down until you find the text _\[update\_manager]_.

_If you see an additional line that reads “enable\_auto\_refresh: True”, do not remove it. Simply proceed to the next line. Note that this line may not be present for all users._

<img src="https://docs2.zerog.one/images/other/mainsail/theme/step7.png" alt="" data-size="original">
{% endstep %}

{% step %}
### Insert Code

```yaml
[update_manager client ZeroGTheme]
type: git_repo
path: ~/zerog-mainsail-theme
origin: https://github.com/ZeroGDesign/zerog-mainsail-theme.git
install_script: install.sh
is_system_service: False
```
{% endstep %}

{% step %}
### Confirm Changes

Confirm your code looks somewhat similar to this.

<img src="https://docs2.zerog.one/images/other/mainsail/theme/step8.png" alt="" data-size="original">
{% endstep %}
{% endstepper %}



## Final Steps

{% stepper %}
{% step %}
### Press Save & Restart

<img src="https://docs2.zerog.one/images/other/mainsail/theme/step9.png" alt="" data-size="original">
{% endstep %}

{% step %}
### Restart Moonraker

If a notification appears asking you to **try again**, click on it to proceed.

<img src="https://docs2.zerog.one/images/other/mainsail/theme/step10.png" alt="" data-size="original">
{% endstep %}

{% step %}
### Refresh your Browser

Refresh your browser to check if the ZeroG theme is now visible.

<img src="https://docs2.zerog.one/images/other/mainsail/theme/step11.png" alt="" data-size="original">

###
{% endstep %}
{% endstepper %}

### Update Manager

On the right-hand side, you will see the **Update Manager**. You should now notice that **ZeroGTheme** has been added. This will enable you to easily obtain the latest updates as they become available for the ZeroG Mainsail Theme.

![](https://docs2.zerog.one/images/other/mainsail/theme/step12.png)

### That's it, Enjoy!

![](https://docs2.zerog.one/images/other/mainsail/theme/step13.png)
