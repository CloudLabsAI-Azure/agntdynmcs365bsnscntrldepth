# Lab 5 - Map e-documents to purchase order lines with Copilot in Dynamics 365 Business Central

**Introduction**

In this lab, you will explore how e-documents are processed and mapped to purchase orders in Dynamics 365 Business Central using Copilot. The lab begins by accessing a sandbox environment and
generating the required demo data using the Contoso Demo Tool. Participants then work with linked purchase orders created from e-documents and learn how Copilot assists in matching e-document lines with purchase order lines. Through hands-on exercises, you will gain practical experience in reviewing, validating, and saving Copilot-generated matches, while also understanding the different matching options available within the e-document mapping process.

## Task 1: Open Business Central Admin Center and Access Sandbox Environment

1. Navigate to the Business Central home page.

1. Open the **Dynamics 365 Business Central** portal. From the top navigation bar, select **Companies(1)** and switch to **My Company(2)**.

   ![](./media/firstimage.png)

1. In the browser’s address bar, locate the current environment URL. Remove everything after the tenant ID (including `/production`).

   ![](./media/secondimage.png)

1. Append `/admin` to the end of the modified URL, as shown below, and then press **Enter**.

   ![](./media/three.png)

1. From the top menu, click **New** to start creating a new environment.

   ![](./media/l5t1s5.png)

1. In the Create environment page, enter the following values:

   - Name: **cronus_sandbox (1)**

   - Type: **Sandbox (2)**

   - Country: **United States (US) (3)**

   - Version: **28.0 (4)**

1. After entering the details, click **Create (5)** . The environment creation process begins and the status shows that the environment is being configured.

   ![](./media/l5t1s6.png)


1. In the Admin Center, locate and select the **cronus_sandbox** environment.

   ![](./media/l5t1s7.png)

1. Click on the **Environment URL** to open the selected sandbox environment.

   ![](./media/l5t1s8.png)

## Task 2: Generate Demo Data Using Contoso Demo Tool

1. Once inside the sandbox environment, press **Alt + Q** on the keyboard to open the search.

1. In the search field, enter **Contoso Demo Tool** and select it from the results.

   ![](./media/l5t2s1.png)

1. In the Contoso Demo Tool page, locate the **Data Name** field.

1. Select the **vertical menu (1)** option for the Name field and choose **Select More (2)**.

   ![](./media/l5t2s2.png)

1. From the list of available demo data:

   - Select all data options

   - **Do not select**: Subscription and Billing

1. After selecting the required demo data, click **Generate** from the top of the page.

   ![](./media/l5t2s3.png)

1. When prompted, click **Yes** to confirm the generation process.

   ![](./media/l5t2s4.png)

1. Click **OK** once the process is completed successfully.

   ![](./media/l5t2s5.png)

## Task 3: Open Linked Purchase Orders from E-Document Activities

1. Navigate back to the Business Central home page.

   ![](./media/image9.png)

2. Scroll down to locate the **E-Document Activities** section.

3. Select **Linked Purchase Orders**.

   ![](./media/image10.png)

4. Review the list of available purchase orders created from demo data.

## Task 4: Map E-Document Lines for the First Purchase Order

1. Select the **first purchase order** from the list.

2. On the purchase order page, choose **Map E-Document Lines**.

   ![](./media/image11.png)

3. Copilot automatically matches the e-document lines with the purchase
    order lines.

4. Review the suggested matches.

5. Select **Keep it** to save the matched purchase order.

   ![](./media/image12.png)

6. Select **Back** to return to the purchase order list.

   ![](./media/image13.png)

## Task 5: Explore E-Document Mapping Options with Another Purchase Order

1. Open the **next purchase order** from the list to further explore
    e-document mapping.

   ![](./media/image14.png)

2. On the purchase order page, select **Map E-Document Lines** from the
    top bar.

   ![](./media/image15.png)

3. Review the matching results:

    - Auto-matched lines

    - Copilot-matched lines

4. Select **Discard it** to explore alternative matching options.

   ![](./media/image16.png)

## Task 6: Match E-Document Lines Using Copilot

1. On the purchase order matching page, review the available options:

    - Match with Copilot

    - Match manually

    - Match automatically

   ![](./media/image17.png)

2. For this lab, select **Match with Copilot**.

   ![](./media/image18.png)

3. Copilot matches all e-document lines with the purchase order lines.

4. Review the matching suggestions carefully.

5. Select **Keep it** to save the final mapping.

   ![](./media/image19.png)

**Conclusion**

By completing this lab, participants gain a practical understanding of
how Copilot enhances the e-document mapping experience in Dynamics 365
Business Central. Participants successfully generated demo data,
reviewed linked purchase orders, and used Copilot to automatically match
e-document lines with purchase order lines. They also explored different
matching scenarios, including reviewing and discarding matches to better
understand the available options. This lab demonstrates how Copilot can
reduce manual effort, improve accuracy, and streamline procurement
workflows by simplifying the process of mapping vendor e-documents to
purchase orders.
