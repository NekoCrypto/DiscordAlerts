# Discord Alerts Validatore rewards is ready!
To set up alerts for your balance of rewards of TIA tokens for the Celestia Network, you can use the Celestia Network's ITN toolings.

o set up alerts for your balance of rewards of TIA tokens for the Celestia Network, you can use the Celestia Network's ITN toolings. Here are the step-by-step instructions:

Install the ITN toolings:
Open a terminal in your Linux machine
Run the following command: curl -s https://raw.githubusercontent.com/celestiaorg/celestia-utils/master/install_itn.sh | bash
This will download and install the ITN toolings in your machine.
Create a Discord webhook:
Log in to your Discord account and select the server where you want to receive the alerts.
Click on the channel where you want to receive the alerts, and then click on the gear icon to open the channel settings.
Click on the "Integrations" tab and then click on the "Create Webhook" button.
Enter a name for your webhook and click on the "Copy Webhook URL" button.
Set up the alert:
Open a terminal in your Linux machine
Run the following command: celestiacli itn set-reward-alert <address> <discord_webhook_url> <threshold>
Replace <address> with your Celestia Network address.
Replace <discord_webhook_url> with the Discord webhook URL you copied in step 2.
Replace <threshold> with the minimum reward balance that should trigger the alert.
For example, if you want to set an alert for a reward balance of 10 TIA tokens, you can run the following command: celestiacli itn set-reward-alert celestia1xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx https://discord.com/api/webhooks/xxxxxxxxxxxxxxxxxxxx/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx 10
This will set up an alert that will send a message to the Discord channel whenever your reward balance reaches or exceeds the specified threshold.
That's it! You have now set up alerts for your balance of rewards of TIA tokens for the Celestia Network.


# Instructions S-B-S:
<div>1.Install the ITN toolings</div>
<div>2.Create a Discord webhook</div>
<div>3. Set up the alert</div>
