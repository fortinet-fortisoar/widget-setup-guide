| [Home](../README.md) |
|----------------------|

# Usage

The Setup Guide icon is available immediately when an administrator logs into FortiSOAR.

![Setup Guide on logging into FSR](./res/setup-guide-launch-point.png)

To view the details of the FortiSOAR Setup Guide, click the FortiSOAR **Setup Guide** icon ![](./res/icon-setup-guide.svg).

![Quick Start view of the Setup guide](./res/setup-guide.png)

The FortiSOAR Setup Guide has two flavors.

- **Quick Start**: Select Quick Start to quickly set up FortiSOAR with the minimum required settings for optimal functioning. *Quick Start* contains important system configurations that FortiSOAR highly recommends you set up.

- **Production**: Select Production to set up FortiSOAR with all the required settings for optimal functioning in a production environment. *Production* contains tasks that are dependent on the user and environment preferences.

The FortiSOAR Setup Guide is divided into sections for each phase of getting FortiSOAR ready:

- **Deploy**: For tasks related to setting up the server with appropriate hardware configurations, network and security tunings, data protection, etc. The 'Deploy' section also provides information about the 'FortiSOAR Trial License,' which is easy to activate and can be used in development environments without incurring additional licensing costs. For more information about the 'Trial License', see the Licensing FortiSOAR chapter in the "Deployment Guide."

- **Streamline**: For tasks related to setting up the incident response platform, which is augmented with automation of common tasks such as enrichment and mitigation.

- **Accelerate**: For tasks related to accelerating your response time by leveraging various pre-defined playbooks to respond to specific types of threats, and installing solution packs targeted towards management of specific SOAR scenarios, such as Threat Intel management, Vulnerability Management, etc.

- **Maintain**: For tasks related to enabling monitoring and sustenance so that the server performs optimally and remains highly available throughout your usage.

FortiSOAR Setup Guide opens in the Quick Start mode that contains limited items to set up. To view the complete list of tasks:

1. Select **Production**.

2. Click '![right icon](./res/icon-chevron-right.svg)' against each section to expand all its tasks. The following image shows the expanded task *Leveraging the FortiSOAR Trial License for Development Environments* under Deploy.

    ![Setup Guide - Production tasks and details for the Deploy task](./res/setup-guide-expanded.png)

Each task contains a brief description and a link to either the documentation containing detailed information, or, the FortiSOAR page or section to set up that particular task. For example:

- Click the **sizing guide** link in **Review the Sizing and Configuration** row to open the *Sizing Guide* and check the configuration for your anticipated workload. 

- Click **Review** in the **Define Notification Rules** task to open the **Notifications** page. Here, you can set up rules and notifications channels to notify users and teams various tasks they need to complete or view.

For each task you have three options:

- **Mark as Done**: Click this button to mark the task as done, once you complete it.

    ![](./res/setup-guide-done.png)

    - Click **Mark as Done** to display that task with a green circular check ![icon green check](./res/icon-mark-as-done.svg). A **Reset Task Options** button appears in its place.

    - Click **Reset Task Options** button to bring back the options, in case you clicked **Marked as Done** in error.

- **I will complete later**: Select this button to skip that task and complete it at a later time.

    - Click **I will complete later** to collapse that task's row

    - The task action buttons remain active and appear when the row is expanded

- **Not Applicable**: Select this button if a task does not apply to your FortiSOAR environment.

    ![](./res/setup-guide-na.png)

    - Click **Not Applicable** to display that task with a struck-out, circular check ![icon not applicable](./res/icon-not-applicable.svg). A **Reset Task Options** button appears in its place.

    - Click **Reset Task Options** button to bring back the options, in case you clicked **Not Applicable** in error.

# Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) |
|-----------------------------------------|-------------------------------------------|
