# documentation for the project
Graduation project in a domotic context
## How to run the app
1) Install Electron via `npm install -g electron-prebuilt@1.4.15`.
2) Install dependencies by executing `npm install`under the project directory.
3) Run the app via `electron <app-path>` (or `electron .` if you are in the project directory).
If you want to know more about Electron app's development, please refer to the [official docs](https://github.com/electron/electron/blob/master/docs/tutorial/quick-start.md).
### Note :
The application is configured to connect to a local database, reconfigure database connection attributes or create similar local database as the default configuration
## Implemented functionalities
* Management of users' roles and access rights.
* Administrator roles : Manage users (view, add, delete), select consumption details to display for an expert / normal user
* Expert / Normal user roles : View consumption details, view consumption chart (of the day,last month or last trimester), view consumption consultation history
## Unimplemented functionalities
* Integrate native applications to get consumption data from ZigBee network
* Test the application on the embedded architecture
