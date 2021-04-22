# Cloudpath-Postman
This collection includes most of the API calls in Cloudpath release 5.8 to create and manage DPSK pools, DPSKs, properties, units and the Tenant Portal.
* Navigate to Configuration/API Keys in the Cloudpath UI and create an API key.
* Edit the host and APIKEY variables in the Pre-request Script of Authentication/1. Get token, then enter your credentials in the body.
* You can run all API calls in the order they appear. By the end, you can delete the objects you created.
* This collection assumes you start without any DPSK pool or property. If you have any, you might need to change the indices [] in the Tests script in some API calls.
* In Properties and units/1.Create Property and 5.Create unit, enter your email and phone number in the body. That way, you will receive an e-mail and SMS message with the link for your tenant portal. 
* Before proceeding to the calls in Tenant Portal, use the link in the e-mail or SMS to connect a device using the QR code or passphrase.
