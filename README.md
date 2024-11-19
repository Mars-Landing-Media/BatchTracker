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
   - Filter by categories, statuses, or environments to quickly locate specific batches.  

2. **Update Set Promotion Tracking**:  
   - Keep track of batch promotions across development, test, and production environments.  
   - Visual indicators highlight pending, in-progress, and completed promotions.  

3. **Audit-Friendly Reporting**:  
   - Generate detailed reports for each batch, including batch contents, timestamps, and promotion history.  
   - Exportable reports ensure easy sharing and audit compliance.  

4. **Automated XML Export**:  
   - Effortlessly export update set XML files directly from the Batch Tracker interface.  
   - Reduces manual effort during large-scale promotions or migrations.  

5. **Customizable Categories and Tags**:  
   - Organize batches with categories and tags for better structure.  
   - Tailor categories to align with organizational processes or project milestones.  

6. **Role-Based Access Control**:  
   - Assign roles to limit who can view, edit, or promote batches.  
   - Ensure security by controlling access based on user responsibilities.  

7. **Batch Execution Insights**:  
   - Real-time insights into batch execution statuses.  
   - Track the success or failure of individual update sets within a batch.  

## How It Works

Batch Tracker integrates seamlessly with ServiceNow to help developers and admins efficiently manage update sets. It enables batch creation, visualization, and promotion, offering tools to maintain transparency and streamline workflows during the development lifecycle.

### Accessing the Application

1. Log in to your ServiceNow instance.
2. Navigate to the application navigator and search for **"Batch Tracker"**.
3. Open the **Batch Tracker Dashboard** to view, manage, and create batch entries.

For a detailed walkthrough, refer to the **How-To Document** included in the repository.

## Example Use Cases

- Visualize and manage update sets for a release in one consolidated view.
- Automate the generation of XML files for batch promotion to higher environments.
- Track batch contents and their statuses across development, testing, and production.
- Organize update sets by category to align with development processes.

## Installation

### Step 1: Download and Import the Update Set
1. Download the Batch Tracker update set from the Mars Landing Media GitHub repository or official distribution channel.
2. Navigate to **System Update Sets > Retrieved Update Sets** in your ServiceNow instance.
3. Upload the update set and commit it.

### Step 2: Configure the Application
1. Open the **Batch Tracker Portal** settings module in the application navigator.
2. Start creating and managing batches.

### Step 3: Test and Deploy
1. Create a test batch of update sets.
2. Review the batch in the Batch Tracker dashboard.
3. Deploy to production when satisfied with the setup.

## Example Configuration

### Example Batch Entry
| Field           | Value                  |
|------------------|------------------------|
| Name            | `Release 1.2 Updates` |
| Category        | `Feature Release`     |
| Status          | `In Progress`         |
| Environment     | `Development`         |

### Example Report Entry
| Field           | Value                  |
|------------------|------------------------|
| Batch Name      | `Release 1.2 Updates` |
| Total Update Sets | `15`                 |
| Promotion Status | `Pending`            |

## Documentation

For a comprehensive guide to configuring and using Batch Tracker, refer to the **How-To Document** included in this repository. It contains step-by-step instructions, best practices, and troubleshooting tips.

## Licensing

This application is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

Batch Tracker simplifies update set management and promotes transparency and efficiency for ServiceNow development teams. For detailed instructions and support, visit the [Mars Landing Media GitHub repository](https://github.com/Mars-Landing-Media).
