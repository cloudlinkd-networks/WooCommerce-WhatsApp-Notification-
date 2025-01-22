<p align="center">
<img alt="Logo banner" src="https://github.com/cloudlinkd-networks/whatsapp-notification/blob/main/logo.png"/></p>
</br>

# CloudLinkd WhatsApp</br></br>WordPress/Woo-Commerce WhatsApp Notifications Integration

![Example dashboard](https://raw.githubusercontent.com/cloudlinkd-networks/WHMCS-WhatsApp-Notification/refs/heads/main/screenshot-4.png)
</br></br>

Our aim is to deliver maximum functionality, enabling you as a site owner to configure the plugin exactly as needed, all while maintaining an user-friendly interface.<br>
However, it's beneficial to be familiar with all the available options.<br>

The plugin is organized into three primary sections:<br>

Installation, Settings and Test Gateway.

Installation :

- Download the "cloudlinkd+wpnotif-v3.0.1.1.zip" file from the releases tab.
- Do not unzip the downloaded .zip file.
- Log in to your WordPress admin panel.
- Select the plugins, then Add new.
- Browse your computer to select the “cloudlinkd+wpnotif-v3.0.1.1.zip” file download.
- Click Install Now and WordPress will do its magic and install the Plugin.
- After the installation is complete, activate the plug-in.

Settings :

- Go to gateway tab and enable WhatsApp
- Select Whatsapp Gateway option and select "Custom WhatsApp Gateway"
- WhatsApp Gateway URL: "https://wa.cloudlinkd.com/send-message?"
- HTTP Method: "Post"
- Gateway Parameters: "&api_key=your-cloudlinkd-api-key&sender={sender_id}&number={to}&message={message}" - Get the API Key from https://wa.cloudlinkd.com
- Send as Body Data: "Yes"
- Encode Message: "No"
- Phone Number: with + and country code
- Sender ID: Your Device/Phone number ( *Without country code + )

Test Gateway Setting :

- Message Content: Any test message of your choice
- Phone Number: Your receiver phone number
- Click Test and you will see the test response like {Success:true}

----------

## Credits

All credits to the [Team CloudLinkd](https://www.cloudlinkd.com) and the original creators of these files.</br>
