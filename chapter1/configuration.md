## Basic Configuration

### Launch webportal
In `appliance_console`, we can check either `ManageIQ Server` is running or not. If not then we can start it by entering digit `14` in the advanced setting.  After that when we hit IPv4 address which is given in `appliance_console` in web browser we can see the ManageIQ's Log In page.

![login](../images/chapter1/manageiq_login.png "ManageIQ Log In Page")

### Log In
There are default credentials for ManageIQ. We can change it but we will discuss it later here.

- **Login:** admin
- **Password:** smartvm

Now we can see the dashboard which looks like following image

![dashboard](../images/chapter1/manageiq_dashboard.png "ManageIQ Dashboard")

In the extreme left, we can see the vertical navigation bar. We can easily navigate through elements in menu from those bars.

### Change Configuration
In upper right corner, we can see dropdown bar for EVM. Go to **EVM  &rarr;  Configuration**

![server configuration](../images/chapter1/manageiq_configuration.png "EVM Configuration")

Here, we can see

#### In Setting section

- **Hostname, IP Address :** hostname and IP of appliance is shown

- **Company Name :** Company Name is shown but we can change it and that name is reflected over interface

- **Zone, Appliance Time Zone and Default Locale:** You can change default time zone and locale as per wish

- **Server Control** decides roles of each appliance. So don't On any options without need and put all other options default

#### In Access Control

We can change default credentials of User. Also we can use Groups and Role section in appliance for ease.

![access control](../images/chapter1/manageiq_edituser.png "Edit User")

### My Settings

In EVM's dropdown go to My Settings i.e **EVM &rarr; My Settings**. We can change visual, Default views, Default Filters and Time Profiles of interface.

![my settings](../images/chapter1/manageiq_mysettings.png "My Settings")


That defines apperance of UI as well as Default Start Page. So you can customize it.





