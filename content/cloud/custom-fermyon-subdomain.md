title = "Apply Custom Fermyon Subdomain"
template = "cloud_main"
date = "2022-04-26T17:00:00Z"
enable_shortcodes = false
[extra]
url = "https://github.com/fermyon/developer/blob/main//content/cloud/custom-fermyon-subdomain.md"

---

- [Prerequisites](#prerequisites)
- [Select Your Spin Application](#select-your-spin-application)
- [Apply New Custom Fermyon Domain](#apply-new-custom-fermyon-domain)
- [Validate Custom Fermyon Subdomain Name](#validate-custom-fermyon-subdomain-name)
- [Next Steps](#next-steps)

Every Spin application running on Fermyon Cloud receives a domain name that has the following format: `<your-App-Name-randomlyAssignedString>.fermyon.app`. For a more easily recognizable domain name, you may want to change your Spin application's domain name from `slats-the-cat-o7jecuug.fermyon.app` to `slatsthecat.fermyon.app`.

Custom Fermyon subdomain names allow you to change the randomly generated domain name for your application.

## Prerequisites

Log into [Fermyon Cloud](https://cloud.fermyon.com) and ensure you have a Spin application running on Fermyon Cloud. If you do not have a Spin application yet, follow our [quickstart guide](quickstart.md) to deploy one. 

![Cloud UI with 1 application](../../static/image/cloud-dash-w-quickstart-app.png)

## Select Your Spin Application

Select the application whose domain name you intend to modify. Then select the *Edit Subdomain Name* button in the top right corner.

![Cloud UI with app panel view open](../../static/image/app-panel-view-w-edit-subdomain-button.png)

## Apply New Custom Fermyon Subdomain

In the text box, you will see your application's current domain record. 

![Custom subdomain panel with original subdomain](../../static/image/custom-subdomain-panel-original.png)

Input your preferred subdomain name that meets the following characteristics:

- character length is at least 3 
- character length is less than 63 characters
- subdomain name is unique 

Then click save to apply your changes. 

![Custom subdomain panel with new subdomain](../../static/image/custom-subdomain-panel-renamed.png)

## Validate Custom Fermyon Subdomain Name

If you view the application's domain name in the panel view, you should see it has been updated to reflect your custom Fermyon subdomain name.

![App panel view with custom subdomain name](../../static/image/custom-subdomain-app-panel-view.png)

![Spin app responding at quickstart.fermyon.app](/static/image/quickstart-custom-subdomain.png)

## Next Steps

Congratulations, you have successfully applied a custom Fermyon subdomain to your Spin application. 

- [Delete an application](delete)
- Find known issues and file new ones with on the [Fermyon Cloud Feedback GitHub repository](https://github.com/fermyon/feedback)
