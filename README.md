# Microsoft Defender for Cloud - Step-by-Step Setup Guide (GUI)

This guide will walk you through setting up **Microsoft Defender for Cloud** using the **Azure Portal GUI**.

---

## Step 1: Enable Microsoft Defender for Cloud

1. **Sign in to the Azure Portal**  
   - Open your browser and go to [Azure Portal](https://portal.azure.com).  
   - Sign in with your Azure account.  
![Screenshot 2025-04-01 at 7 03 07 pm](https://github.com/user-attachments/assets/552b372f-5360-44ee-a158-5ca84f2ca30b)

2. **Navigate to Defender for Cloud**  
   - In the search bar at the top of the Azure Portal, type **Defender for Cloud**.  
   - Click on **Defender for Cloud** from the search results.  
![Screenshot 2025-04-01 at 6 33 17 pm](https://github.com/user-attachments/assets/abe90772-63fe-42d8-ae38-ca725ae7315e)

3. **Enable Microsoft Defender for Cloud**  
   - In the left-hand menu, click **Environment settings**.  
   - Select your **Azure Subscription** from the list.  
   - Click **Enable Microsoft Defender for Cloud** to activate security monitoring.  
![Screenshot 2025-04-01 at 6 36 55 pm](https://github.com/user-attachments/assets/cb233948-e806-4404-8185-5edee1066e5a)

---

## Step 2: Enable Microsoft Defender Plans

1. **Open Defender for Cloud Dashboard**  
   - Go to **Defender for Cloud** from the **Azure Portal**.  

2. **Go to Defender Plans**  
   - In the **Environment settings**, find the section called **Defender plans**.  

3. **Enable Defender Plans**  
   - Click on the toggle next to each plan you want to enable:  
     - **Defender for Servers**  
     - **Defender for Storage**  
     - **Defender for Databases**  
     - **Defender for Key Vault**  
   - Click **Save** to apply the changes.  
![Screenshot 2025-04-01 at 6 43 06 pm](https://github.com/user-attachments/assets/ddc2b2e4-dae9-472a-bff3-eb7158f02d28)

---

## Step 3: Configure Continuous Export

1. **Navigate to Defender for Cloud Settings**  
   - In **Defender for Cloud**, go to **Settings** in the left-hand menu.  

2. **Open Continuous Export**  
   - Click on **Continuous export** under the **Settings** section.  

3. **Enable Export Options**  
   - Select **Log Analytics** as the export destination.  
   - Click on **all the checkboxes** to export **Security Alerts** and **Secure Score recommendations**.
     ![Screenshot 2025-04-01 at 6 52 47 pm](https://github.com/user-attachments/assets/2754a832-6fda-43fa-80e9-0d3d2f9aacfb)

4. **Set Export Target**
   –Click **Export configuration**.  
   - Under **Resource group**, select **Export target**.  
   - Under **Subscription**, choose **Azure subscription 1**.  
   - Select the **target workspace** for data export.  
   - Click **Save** to apply the configuration.  
![Screenshot 2025-04-01 at 6 57 13 pm](https://github.com/user-attachments/assets/8580edb6-9cb4-4369-ad5e-ff9d5606d398)

### ✅ Congratulations!
You have successfully set up **Microsoft Defender for Cloud** using the **Azure Portal GUI**. Your Azure environment is now more secure!
