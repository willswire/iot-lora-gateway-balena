# iot-lora-gateway-balena
 of our beta boards and can test then please report any issues.

## Device Environment Variables
The software only requires 3 variables to be set. The variables  can be set in the application's envrionment variables.  Refer to [this documentation](https://www.balena.io/docs/learn/manage/serv-vars/) on setting environment variables in balenaCloud

For each gateway you must then go into it and set two device variables:

```CONTACT_EMAIL``` - The email address of the primary TTN admin.

```TTN_ID``` - This is the ID as in the TTN Console.

```TTN_KEY``` - This is the Gateway's Key as from the TTN Console.
