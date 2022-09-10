# microsoft autopilot

[![microsoft autopilot](gett-stateed.png)](https://github.com/softwarelaab/microsoft.autopilot/)

Windows Autopilot is a collection of technologies used to set up and pre-configure new devices, getting them ready for productive use. Windows Autopilot can be used to deploy Windows PCs or HoloLens 2 devices.

## How to enroll devices using Windows Autopilot?

Step 1: On the Windows Business Store, navigate to Manage -> Devices and select Autopilot deployment
Step 2: Create a new Windows Autopilot deployment profile and by default users are allowed to skip the following steps while activating the device
 * Cortana, OneDrive and OEM registration setup
 * Work or school setup
 * Sign-in experience with company brand
* Additionally, the following settings can be configured:
 * Skip Privacy Settings
 * Disable local admin account creation on the device
 * Skip End User License Agreement (EULA)
Step 3: Obtain the device details from your resellers, upload the CSV file containing the details and associate the Windows Autopilot deployment profile.
Step 4: The device will be enrolled and available on the Mobile Device Manager Plus server for user assignment

## Benefits of using microsoft Autopilot

_Windows microsoft Autopilot or Microsoft  deployment provides organizations the following benefits:_

* **Aids large scale enterprise device deployment:** With microsoft Autopilot, organizations can deploy hundreds of devices with minimal admin interaction, thereby reducing the time spent on configuring and provisioning devices
* **Automated user assignment:** Employees can automatically register the devices enrolled using Windows Autopilot with their respective microsoft accounts. Thus, significantly reducing the time spent on distributing the apps and content on devices.
* **Eliminate the need for OS imaging and deployment:** With Microsoft Autopilot, you can ensure Windows devices are provisioned with the required apps, content and configurations instead of using the time-consuming OS imaging process.
* **Customizable branding:** Organizations can optionally re-brand the login screen with the organization's logo, a banner and custom texts, while configuring Windows Autopilot and also provide the device user a customized out-of-the-box experience (OOBE).

## Understanding the AutoPilot Intunes Relationship

_The out-of-the-box promise that AutoPilot delivers is hinged to Intune — which acts as the driver that pushes installs and updates to devices. Here’s how it works._

* IT will configure the AutoPilot workflows and register devices in Intune. IT will have to grab the device ID from the hardware vendor during this step.
* Your business buys new devices.
* Users unbox the devices and sign in to their Microsoft account (with an active network connection)
* Intune syncs AutoPilot and the devices and pushes configurations and updates for the devices.
