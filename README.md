# Azure-week8-Assignment

Link for deployed webapp on azure Link: prernatest123.azurewebsites.net

Steps to Complete the Assignment
A. Schedule a Daily Backup of VM at 3:00 AM Using Vault

Create a Recovery Services Vault:

I logged into the Azure portal and navigated to "Recovery Services vaults."
I clicked "Create" and filled in the necessary details such as resource group, vault name, and region.

Configure Backup for VM:

In the Recovery Services vault, I selected "Backup" and chose "Azure" as the workload to back up.
I selected "Virtual machine" as the backup goal and then selected the VM to back up.

Create a Backup Policy:

I created a new backup policy and configured it to schedule daily backups at 3:00 AM.
I set the retention period according to my requirements, ensuring that older backups are retained as needed.

Enable Backup:

I applied the backup policy to the VM and enabled the backup.

B. Provision Backups in Backup Center

Access Backup Center:

I navigated to the "Backup Center" in the Azure portal.

Configure Backup Policy and Retention:

In the Backup Center, I reviewed the backup policy configured in the previous step.
I ensured the retention period was set correctly and retained older backups as required.

C. Create an Alert Rule for VM CPU Percentage

Navigate to Alerts:

In the Azure portal, I went to the "Monitor" section and selected "Alerts."

Create a New Alert Rule:

I clicked on "New alert rule" and selected the VM as the target resource.
Under "Condition," I set the criteria to "CPU percentage" and configured it to trigger when the CPU percentage is greater than 80%.

Configure Action Group:

I created an action group to specify the action to take when the alert is triggered. This included sending an email notification.
I provided the necessary details such as email addresses and configured the notification settings.

Review and Create:

I reviewed the alert rule configuration and created the alert rule.

Conclusion
By following the above steps, I successfully scheduled daily backups of a VM at 3:00 AM using a Recovery Services vault, created an alert rule for VM CPU usage exceeding 80%, and provisioned backups in the Azure Backup Center. This assignment provided practical experience in managing backups and monitoring resources in Azure.

