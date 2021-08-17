# OneSignalTaskDemoTest
OneSignalTaskDemoTest is the ASP.NET MVC project.
# Steps to run application
Open OneignalTask->appsettings.Development.json and change:
  1) Set Server in the DefaultConnection and in the "Serilog"->"connectionString" instead of "serverName";
  2) Set your OneSignal ApiKey in the OneSignalOptionsApi instead of "apiKey";
# Authentication and authorization
There are 2 roles Admin and Readonly.
Admin can perform all CRUD operations while the Readonly role can only view data.

All new users get the Readonly role by default.

Admin credentials 

Email: admin@test.com

Password: admin

Readonly credentials

Email: readonly@test.com

Password: readonly

## Logging

The application supports logging.
