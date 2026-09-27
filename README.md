## NOTE IMAGE STEPS ON BOTTOM FOR EASIER WAY ##

DNS Domain Blocking with OpenDNS
This guide explains how to configure OpenDNS on a network you administer and use its dashboard to block specific domains.

Note: Only make these changes on networks and devices that you are authorized to administer. Do not use DNS changes to bypass an organization's security, filtering, or monitoring controls.

1. Get your OpenDNS nameservers
Sign in to your OpenDNS account.

Open your network/dashboard settings.

Add your network if you haven't already.

Locate the OpenDNS nameserver addresses assigned to your configuration.

There should be two nameserver addresses.

2. Configure DNS on Windows
Open Settings.

Go to Network & Internet.

Open the properties for your Wi-Fi or Ethernet connection.

Find the DNS server assignment setting.

Select Edit and choose Manual.

Enable IPv4.

Enter the two OpenDNS nameserver addresses.

Save the changes.

You may need to reconnect to the network or restart the connection for the new DNS configuration to take effect.

3. Configure domain blocking
Open the OpenDNS dashboard.

Go to your network's settings.

Find the Web Content Filtering or equivalent filtering section.

Choose the appropriate custom filtering option.

Save the configuration.

4. Add a domain to the block list
Open the domain-management or individual-domain blocking section and add the domain you want to restrict.

For example:

ibosscloud.com (this is what you block if you have iboss restrictions)

Select the appropriate blocking option and save the configuration.

5. Test the configuration
After saving the settings:

Clear your DNS cache if necessary.

Reconnect to the network.

Try accessing the domain from a device using your configured DNS.

Verify that the filtering policy is being applied.

Troubleshooting
If the domain is still accessible:

Verify that Windows is actually using the intended DNS servers.

Check whether the device is using another DNS service.

Check whether DNS-over-HTTPS is configured separately.

Confirm that the domain was entered correctly in the filtering configuration.

Allow some time for DNS/filtering changes to propagate.

Authorization
Only use these procedures to manage DNS and web access on networks you own or are authorized to administer.

WAIT
You must wait around 1-10 minutes to kick in if it doesnt you have done something wrong please check the instructions list again or check the images I have put in the files pages. (labeled step 1-10) under this text you will see them in order 

## Setup Steps

![Step 1](./images/first%20step.png)

![Step 2](./images/second%20step.png)

![Step 3](./images/third%20step.png)

![Step 4](./images/fourth%20step.png)

![Step 5](./images/fifth%20step.png)

![Step 6](./images/sixth%20step.png)

![Step 7](./images/seventh%20step.png)
