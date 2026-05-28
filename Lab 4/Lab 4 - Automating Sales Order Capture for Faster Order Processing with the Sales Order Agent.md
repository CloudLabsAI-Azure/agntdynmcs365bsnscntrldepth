# Lab 4: Automating Sales Order Capture for Faster Order Processing with the Sales Order Agent.

**Introduction**

In this lab, you will learn how the Copilot-powered **Sales
Agent** in Dynamics 365 Business Central helps automate customer inquiries and generate sales quotations directly from email requests.

The lab demonstrates how to activate and configure the Sales Agent, receive customer inquiries via email, review Copilot-driven decisions, and send quotation responses automatically. This hands-on experience shows how sales teams can respond faster to customer requests while reducing manual effort and improving accuracy.

## Task 1: Activate the Sales Agent

1. Navigate to Microsoft 365 administration accessing the below URL and sign in with the admin tenant.

   ```
   https://www.microsoft.com/en-us/microsoft-365/business/microsoft-365-administration
   ```

1. In the Microsoft 365 administration click on **Admin Sign in**

   ![](./media/adminlogin.png)

1. You'll see the **Sign into Microsoft Azure** tab. Here, enter your **credentials (1)** and select **Next (2)**:

   - **Email/Username:** <inject key="AzureAdUserEmail"></inject>

     ![Enter Your Username](../masterdoc/media/odlusr.png)

1. Next, provide your **password (1)** and select **Sign In (2)**:

   - **Password:** <inject key="AzureAdUserPassword"></inject>

      ![Enter Your Password](../masterdoc/media/password.png)

      > **Note:** If you see **Temporary Access pass**, enter the the password and select **Sign In (2)**:

       - Enter **Temporary Access Pass:** <inject key="AzureAdUserPassword"></inject> **(1)**

          ![](../masterdoc/media/image.png)

1. If it ask for **You need to set up multifactor authentication**, click on the **Skip it for now**

   ![](./media/skipmfa.png)   

1. Go to **Users** **(1)** → **Active users** **(2)** in the Microsoft 365 Admin Center, then select the required **ODL_User <inject key="DeploymentID" enableCopy="false"></inject>** **(3)** account from the list.

   ![](./media/selectodluser.png)

1. In the **ODL_User <inject key="DeploymentID" enableCopy="false"></inject>** **(3)** account, select the **Mail** tab, then under More actions, choose **Convert to shared mailbox**.

mail-convert.png

1. Navigate to Dynamics 365 Business Central accessing the below URL and sign in with the admin tenant.

   ```
   https://www.microsoft.com/en-us/dynamics-365/products/business-central/sign-in
   ```

   ![](./media/l3e1t1s1.png)

1. From the top navigation bar, click the **Sales Agent (1)** icon and click **Activate (2)** to start setting up the Sales Agent.

   ![](./media/l4e1t1s2.png)

1. Turn On the **Activate (1)** toggle and In the Mailbox section, click the horizontal **ellipsis (⋯) (2)** to configure how invoices will be received.

   ![](./media/l4e1t1s3.png)

1. Click **Next** to assign an email account to the agent.

   ![](./media/l4e1t1s4.png)

1. From the available options, select **Current user (1)**, allowing the agent to use the signed-in user’s mailbox for receiving invoices, then click **Next (2)**.

   ![](./media/l4e1t1s5.png)

1. Click **Next** again to confirm the mailbox setup.

   ![](./media/l4e1t1s6.png)

1. Click **Finish** to complete the mailbox configuration.

   ![](./media/l4e1t1s7.png)

1. Verify that **Current user** appears in the **Email accounts** section and click **OK** to finalize the setup.

   ![](./media/l4e1t1s8.png)

1. Click the **right-arrow (\>)** icon to access additional configuration options.

   ![](./media/l4e1t1s9.png)

1. Review the available configuration sections 

   - **Respond to inquiries** - which controls how the agent reviews and responds to messages from registered and unregistered senders.

   - **Create sales documents** - which determines whether the agent sends quotations for confirmation and creates orders from quotes.
   
   Leave the default settings unchanged for this lab.

1. Click **Update** to save the Sales Agent configuration.

   ![](./media/l4e1t1s10.png)

1. Verify that the Sales Agent status shows it is configured
    successfully.

   ![](./media/l4e1t1s11.png)

## Task 2 : Send a Customer Inquiry Email

1. Please use your personal email ID to send the mail. Create a new email and send it to the below email address:

   - **Email/Username:** <inject key="AzureAdUserEmail"></inject>

1. Set the subject as **Inquiry About Chairs** and add the provided email content.

   ```
   Hi,

   My name is Meagan Bond from the School of Fine Art. We are in the process of purchasing chairs and would like to know what options you have available.

   Please share the available models, pricing, and lead times at your earliest convenience.

   Thank you
   ```

1. Send the email to initiate the sales inquiry process.

   ![](./media/l4e1t2s2.png)

## Task 3: Reviewing and Responding to Sales Inquiries in Business Central

1. Navigate back to the **Sales Agent** in the Business Central portal.

1. Notice the notification indicating a **new sales inquiry** has been received.

1. Click the new sales order **notification** to open the request.

   ![](./media/l4e1t3s1.png)

1. Click **Review** to examine the incoming email.

   ![](./media/l4e1t3s2.png)

1. Review the inquiry details and allow the agent to determine the next step for generating a quotation.

   ```
   Note : Wait for 2-3 minutes to complete
   ```
1. Click **Continue** to proceed.

   ![](./media/l4e1t3s3.png)

1. After processing the inquiry, the Sales Agent prepares a response email based on the received request.

1. Click **Review** to review the drafted response.

   ![](./media/l4e1t3s4.png)

1. Review the quotation details created from Business Central item data and click **Continue** to allow the agent to send the quotation email.

   ![](./media/l4e1t3s5.png)

1. Navigate back to your personal email inbox and review the quotation response received, which includes the furniture details requested in the original inquiry.

   ![](./media/image16.png)

## Conclusion

By completing this lab, you have successfully configured the Sales Agent and used Copilot to automate customer inquiry handling and quotation creation. You experienced how incoming emails are reviewed , interpreted, and transformed into structured sales responses without manual intervention. 

This lab highlights how Copilot helps sales teams respond faster to customer needs, improve accuracy, and enhance customer satisfaction using Dynamics 365 Business Central.
