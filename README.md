<p align="center">
<img alt="Logo banner" src="https://github.com/cloudlinkd-networks/whatsapp-notification/blob/main/logo.png"/></p>
</br>

# CloudLinkd WPNotif</br></br>WordPress/Woo-Commerce SMS & WhatsApp Notifications Integration

Our goal is to provide the maximum possible functionality so that you as a site owner can configure the plug-in in the desired way and all this while keeping the interface easy to understand. But it is always good to know all the options. The plugin is divided into three main sections Installation, Settings, Test Gateway.

Installation:

- Download the "cloudlinkd+wpnotif-v3.0.1.1.zip" file from the releases tab.
- Do not unzip the downloaded .zip file.
- Log in to your WordPress admin panel.
- Select the plugins, then Add new.
- Browse your computer to select the “cloudlinkd+wpnotif-v3.0.1.1.zip” file download.
- Click Install Now and WordPress will do its magic and install the Plugin.
- After the installation is complete, activate the plug-in.

Settings:

- Go to settings tab and enable WhatsApp
- Select Whatsapp Gateway option and select "Custom Whatsapp Gateway"
- WhatsApp Gateway URL: "https://wa-api.cloudlinkd.com/send?"
- HTTP Method: "Post"
- Gateway Parameters: "receiver={to}&msgtext={message}&token=your-cloudlinkd-token"
- Send as Body Data: "Yes"
- Encode Message: "No"
- Phone Number: with + and country code

Test Gateway Setting:

- Message Content: Any test message of your choice
- Phone Number: Your receiver phone number
- Click Test and you will see the test response like {Success:true}
