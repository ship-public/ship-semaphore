# Semaphore support for Ship

Welcome to Ship's [Semaphore](https://semaphoreci.com/) support! To learn how Ship can help you with your Semaphore projects, please see [our website](https://www.shipapp.io/integrations/semaphore).

To get Ship integrated, perform these steps:

## Step 1: Add the Ship App to your GitHub Organization

This can be done from our [GitHub Marketplace listing](https://github.com/marketplace/shipapp-io). Ship needs to
integrate with Github for user authentication, and it will also map Github commit details to your Semaphore events.

## Step 2: Get your Ship + Semaphore Webhook URL + API Key

Email [hello@shipapp.io](mailto:hello@shipapp.io) to get yours!

## Step 3: Setup Webhooks

For each Workflow / Pipeline you wish to monitor you need to set up **Webhook Notifications** . Semaphore doesn't allow
defining these globally for an organization, so you need to do this per project.

Semaphore offers multiple ways of defining webhooks, all of which are
described [in their documentation](https://docs.semaphoreci.com/essentials/webhook-notifications/) . Ship supports all
types of notification that Semaphore will send.

The only piece of Ship-specific data you need is the webhook URL with your API key - we'll send that to you when you
email us.

You should start seeing events in Ship the next time workflows run!

## Support

If you need any help please drop us a line at [support@shipapp.io](mailto:support@shipapp.io) .

Happy Shipping!
