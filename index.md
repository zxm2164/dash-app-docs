---
layout: default
---



##	What is it?

DaSH is a desktop application which can be used to remotely monitor web applications.  DaSH is tightly integrated with the mGuard Secure Cloud which is essential to the application’s operation.  Once configured, DaSH is able to establish a secure VPN connection to visualize devices all around the globe.  It is not only useful for visualizing machines and device operation, but also for maintaining devices in the field such as ethernet switches, routers, and any device with a web based interface.  Using DaSH, you can bookmark your devices and return to them on demand, seamlessly and securely.

***

#### Table of Contents
* Table of Contents
{:toc}

***

##	Initial Setup

<img src="{{ site.github.url }}/assets/images/dash-splash.gif" class="centered" alt="Drawing" style="width: 300px;"/>

In order to start using DaSH, you must have

1. mGuard Secure Cloud account created
2. mGuard devices configured
3. Secure Cloud Client installed and configured

#### Account
  You can skip this section if this is already completed.  Using the [mGuard Secure Cloud Website](https://us.cloud.mguard.com) directly is recommended for initial setup.  Simply use the sign up dialog to create an account.

![signpup]({{ site.github.url }}/assets/images/signup.gif)

#### mGuard Devices
  After signing up and creating an account, create mGuard configurations.  In DaSH, these are known as "Sites."  Any device which is connected to the "LAN" connection of the mGuard is known in DaSH as a "Target."

#### Secure Cloud VPN Client

You will need to download, install, and configure the mGuard Secure VPN Client.

[mGuard Secure Cloud VPN Client](https://www.phoenixcontact.com/online/portal/de/pxc/product_detail_page/!ut/p/b1/3ZfJjqM6GIWfpR6AwhAIsGQMMwTMuEFMIWEIUwhJnr5Tpau7uFfdtWllEXuBjCwdfcf-D_xojEYIRgCGoAGzxdAQjc_p9VSll1N_TtuvdbxNIAdF0ca3mLUnOaAIJC_qhMN4No4GaAiIxK3pSYX8oOna5NXgpkLv7HPr6Kl8Nji3kQ_YINYOo-Ms0c4Zs649ccihHdmZsjaHzmWnfidNvXjklB0Wq1kzWIOMdE4wlLGvldWI6KNsVSmpsS5l9flucUeRO1SDZV-I5TpKmn0krMpqIy_rguNJaHiDlVpPAuvHxxMi-gMEwH5ijJ4bqITZmVuAE1sMSHsSsBwubihpqxIqgUI09D1SF3plFQVc5-4cNFiYL7h8Xmd81Uicg7t10PLQplKf70_xlaZIEogKxXmIfgpKK1geuSNHJuukvjZPI8e37PVgi5XSipu93NEWrsrbhK7VmUL8zp1re5ycrezsGQr3-rCQK04cGUoLZEM48O4IB4hEqa3btM0el8AiCuxWhLL8WK2M9IdlCz5-Atu-Kxj5rmDUm4Jx71pj3LvWGPeuNca9a40571pjzrteReddw4MC7wqGf4NFFPcNJrrJKJ3ZnSmI3a1Y5OnuBUizxDvrCN1mlzBEYChxo08GlT30_d6y6JvfydYaSvHYCwIMeN0YZ0vNQ5eVZ66fRWPoqmBgyUTocIK0glnGizM8FkVfFl5gJONmKwtZUSJ7RhnMUyi2Y7IXSNHvm3lDuSWS1Wxzj5GGYdJ4pqtNqklYpNehdA_DuwmQhyQUcOr5JA-PivKBqmh8yrrPNe8-wedwyz-HqS-W_JIU5SU9tcmQViXqq_nleZbGKoihc4HCKsnXvC04SzuVN0VSEW2ktQ3Ejw-NBIV8PpJrCri1VakNbukzgsSDUg-UBi8ibari7ogIXk1nIctfa6xeLVrQvXVQ5_ruTLodAobpl8rI8Gya4-GcRjBe5EdSPXuBAI3_-Lv_1Q18bwC_GSxA3aJMBDGxQ14Qfzhw8vsmf3dI90F5NA-nBisOG1I3IGdj0DfcZuObUFINRjXnmr2ByVsNylRMqD1MgV0ho9uF73gcy5E-0_0oiL9aEHuxoP5qQeHVlgqbFwvCv0_421hoT_PlOxTmZypEl--El1jBJkZdB9XhrsUUv4jKZtAdOxOVpH-m-YUsFKO_qOrJ2OUh7dz2s8DV5_PabBdgiDfcfJxEwiK42WY1SQd1fmQ5kPQufCDzIEZMP3T6rTlzDRkfwO0KDwuCi07tC_ZyaIyQN0pxSxcjtCy_Qpy9XPP9Q29JOOnHwFo0DMevi-GU-cWe5gr2wbKmc34_gzWh3cj2UVPuu_IHkzfE_0x-7HG3WW8GuJlY7eFGk3yZbJlFiRm6uILsafIjVo06ej7N57D_MZm1mntZ_CS4fbEgtXmxoAleLfhqQgn_64IBGv25vQmmcu6XKS9RpygP6dJe0H2e5sdSL69la399z7t4uiPpb2cGauI_b1aM_nciEct-fPwCOBXVWg!!/dl4/d5/L2dBISEvZ0FBIS9nQSEh/pw/Z7_9GN6024610FQ50AB2E37F6J4B7/act/id=0/p=downloadId=3889427/p=action=downloadFile/354833595392/-/)

##	Application Startup

If this is your first time opening the app, DaSH will present you with the mGuard Secure Cloud website.  Here, you must enter your account information as expected.  After entering your credentials, DaSH will store this login information for future use.  
<img src="{{ site.github.url }}/assets/images/acc-collection.gif" class="centered" alt="Drawing" style="width: 600px;"/>

After being successfully logged in, the main application window will be opened.

To be able to connect to your remote sites, DaSH will automatically start the mGuard Secure VPN Client for you.  At which point, don't forget to click start to establish your tunnel.

<img src="{{ site.github.url }}/assets/images/mgsvc.gif" class="centered" alt="Drawing" style="width: 600px;"/>

##	Sites

When the application page is initially loaded, DaSH will scan your configured Secure Cloud Account for established VPN tunnels.  It will automatically add a new site each time an unrecognized site is found.  As of version 1.0.0, DaSH requires the use of the Secure Cloud website to configure new sites.  This can be done through the "Website" tab of the application, or directly from the website itself.  Adding "Sites" is accomplished through the "Service Targets (Machines)" tab.  Then click the '+' symbol to add a new mGuard device.

DaSH will remember these configured sites, and display their status via the connection indicator in the top right of the site.  If a site/mGuard is active, it will be shown in green.  If the site has been retained in memory, but is no longer talking to the cloud, the indicator will be red.  

In the event that an mGuard/site is removed from the account, you can use the edit button to toggle edit mode, and then use the delete button to remove that site from DaSH.  Please note, you may need to restart the application in order to see the changes take affect.

[] image here

### Customizing a Site

DaSH gives you the ability to customize your sites.  Although DaSH will use the preconfigured site name from the mGuard Secure Cloud Website, DaSH gives you the ability to add some customization.  By clicking the edit button while on the "Sites" page, each site may have an image uploaded to represent itself.

<img src="{{site.github.url}}/assets/images/img upload.gif" class="centered" alt="Drawing" style="width: 600px;"/>


### Changing Layout

You can customize the layout of your sites as well.  To do this, click the edit button in the menu bar.  Then, you may click and drag a site to the desired location on screen.  You may also use the bottom right corner of the site to resize the site element.  When you are done laying out all sites, click the edit button again to store the layout configuration.  It will be retained each time the application is restarted.

<img src="{{site.github.url}}/assets/images/sites-layout.gif" class="centered" alt="Drawing" style="width: 600px;"/>

##	Targets

  After establishing a few sites, navigate to the targets page by clicking on a site.  This action starts a VPN tunnel and allows network traffic to travel from your PC to the end network.  Notice that the selected site is shown at the top of the application.   

  <img src="{{site.github.url}}/assets/images/site-target.gif" class="centered" alt="Drawing" style="width: 600px;"/>

  Each site may have any number of targets.  Each 'target' represents a web enabled device.  Configure a target by first clicking the edit button.  When in edit mode, click the add button.  Then, use the add target dialog to configure a new web view.  

  When the new target (web view) is created, every time the corresponding site is selected, the web view will be automatically loaded.  In the event that the content cannot be loaded for some reason, the message 'Failed to Load' will be shown on that target.  In this event, check that the target's URL had been configured correctly.  This can be modified by hovering over the target of interest and clicking its edit button.  Simply change the URL of the device and click submit.

  If you desire to delete a target, use this target edit button and the delete button to remove it from DaSH's memory.

##	Website

  The website page allows you to interact with the configuration of your cloud service.  When you deploy a new mGuard device in the field, you will add and configure it here, allowing it to be added to your database of remote devices.  Here, you can also implement user administration to your cloud system, giving you the ability to add DaSH accounts and access to your field devices.
