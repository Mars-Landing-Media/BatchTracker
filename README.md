# Batch Tracker - Mars Landing Media LLC

**Developer**: Jon DeLuna  

---

**⚠ Important Notice**  
The Batch Tracker report logo can be updated by modifying the system property `marslanding.batchtracker.report.logo`. To change the logo:  
1. Convert your desired image to a base64 format using a tool like [Base64 Guru](https://base64.guru/converter/encode/image/svg).  
2. Update the property value with the generated base64 string.  
Additionally, you can adjust the logo size in the report page's Service Portal widget CSS for precise control over the display.

---

## Description

Batch Tracker is a ServiceNow application designed to streamline the management of update set batches in lower environments. With batch visualization, release reporting, and automated XML downloads, it offers an efficient approach to handling update sets with transparency.

## Features

Batch Tracker is packed with features to enhance your update set management processes:

1. **Batch Management Dashboard**:  
   - Centralized dashboard for viewing and managing update set batches.  

2. **Audit-Friendly Reporting**:  
   - Generate detailed reports for each batch, including batch contents.  
   - Exportable reports ensure easy sharing and audit compliance.  

3. **Automated XML Export**:  
   - Effortlessly export update set XML files directly from the Batch Tracker interface.  
   - Reduces manual effort during large-scale promotions or migrations.  

4. **Scope Deconfliction Support**:  
   - Detect and resolve conflicts in update sets across multiple application scopes.  
   - Visual indicators highlight conflicts, helping teams prioritize resolution.  
   - Log detailed information about conflicting records for faster troubleshooting.  

7. **Role-Based Access Control**:  
   - Assign roles to limit who can view, edit, or promote batches.  
   - Ensure security by controlling access based on user responsibilities.  


## How It Works

Batch Tracker integrates seamlessly with ServiceNow to help developers and admins efficiently manage update sets. It enables batch creation, and visualization, offering tools to maintain transparency and streamline workflows during the development lifecycle.

### Accessing the Application

1. Log in to your ServiceNow instance.
2. Navigate to the application navigator and search for **"Batch Tracker Portal"**.
3. Open the **Batch Tracker Dashboard** to view, manage, and create batch entries.

For a detailed walkthrough, refer to the **Mars Landing Media - Batch Tracker Doc** included in the repository.

## Example Use Cases

- Visualize and manage update sets for a release in one consolidated view.
- Automate the generation of XML files for batch promotion to higher environments.
- Generate and download project or personal XML backups. Download files are automatically named according to your named configuration...not a sys_id (thank goodness).

## Installation

### Step 1: Download and Import the Update Set
1. Download the Batch Tracker update set from the Mars Landing Media GitHub repository.
2. Navigate to **System Update Sets > Retrieved Update Sets** in your ServiceNow instance.
3. Upload the update set and commit it.

### Step 2: Configure the Application
1. Open the **Batch Tracker Portal** settings module in the application navigator.
2. Start creating and managing batches.

## Documentation

For a comprehensive guide to configuring and using Batch Tracker, refer to the [Mars Landing Media - Batch Tracker Doc.pdf](Mars_Landing_Media_BatchTracker_Doc.pdf) included in this repository. It contains step-by-step instructions.

## Licensing

This application is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---


