---
title: Create a Dev Space for SAP Fiori Apps
description: Create an SAP Business Application Studio dev space, a preconfigured environment with the required tools and extensions tailored for a specific business scenario.
auto_validation: true
time: 5
tags: [ tutorial>beginner, topic>sapui5, products>sap-fiori, products>sap-business-technology-platform, products>sap-btp-cloud-foundry-environment]
primary_tag: products>sap-business-application-studio
author_name: Raz Korn
author_profile: https://github.com/raz-korn
---

## Prerequisites
  - You have access to SAP Business Application Studio (see [Set Up SAP Business Application Studio for Development](appstudio-onboarding)).


## Details
### You will learn
  - How to create an SAP Business Application Studio dev space for SAP Fiori apps

Dev spaces are like isolated virtual machines in the cloud that can be instantly spin-up. Each dev space type contains tailored tools and pre-installed run-times for a target scenario such as SAP Fiori or mobile development. This simplifies and saves time in setting up the development environment as there's no need to install anything or upgrade, letting developers focus on their business domain, anytime, anywhere.

---

[ACCORDION-BEGIN [Step 1: ](Open SAP Business Application Studio)]
1. Go to your [SAP BTP Trial](https://account.hanatrial.ondemand.com) account and log in to your SAP BTP cockpit.

2. You might be asked to accept the legal terms. Check the box and click **Accept**.

    !![BTPlegalterms](BTP-Terms-.png)

3. Click **SAP Business Application Studio** to launch SAP Business Application Studio.

    !![launch sap business application studio](BTP-Access-AppStudio-.png)

4. You might be asked to accept the legal terms. Check the box and click **OK**.

    !![legalterms](AppStudio-Terms-.png)

5. A new tab opens. If you have not created a dev space, the welcome page for SAP Business Application Studio loads.

    !![sap business application studio welcome](BAS_Welcome-.png)

    >If this is not the first dev space, the dev space manager for SAP Business Application Studio loads.

    >!![Create Dev Space](BAS-Dev-Space-Manager-Empty-.png)


[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 2: ](Create a preconfigured SAP Fiori dev space)]

1. Choose **Create Dev Space** in the welcome page or dev space manager.

2. Enter `Demo_Fiori` for your dev space **name**.

3. Choose **SAP Fiori** as the application type.

4. Click **Create Dev Space**.

    !![Create Dev Space](AppStudio-Create-Dev-Space-Fiori-.png)

    >The dev space is in status **STARTING**. Wait until it is in status **RUNNING**. This might take a couple of minutes.

    !![Dev Space Starting](BAS-Dev-Space-Starting-.png)

[VALIDATE_1]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 3: ](Open the SAP Fiori dev space)]

1. **Click** the name of the dev space you created.

    !![Open Dev Space](BAS-Open-Dev-Space-.png)


2. The SAP Fiori dev space opens and the **Welcome** tab appears.

    !![Open Dev Space](BAS-Welcome-Tab-.png)

    >You may be prompted to accept the legal terms.

    >The purple color of the status bar indicates that there is no open workspace.


[DONE]
[ACCORDION-END]

---

Hooray!!! With this, you have successfully completed the creation of a dev space for SAP Fiori applications development.

>After a period of idle time the dev space is automatically stopped. In order to re-start the dev space open the [dev space manager](https://triallink.eu10.trial.applicationstudio.cloud.sap/), click the **Play** icon, and click the dev space.

>The period for idle time for Factory accounts is different than for trial accounts.

---
