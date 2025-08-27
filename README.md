# HR - All Employee Content (UiPath RPA)

This RPA project automates the **distribution of HR content** (videos, files, or text) stored in a shared folder by sending it directly to all employees through **WhatsApp**.  

It ensures timely delivery of HR announcements, campaigns, or documents to the entire organization.

---

## 📌 Project Description

The bot retrieves HR content from a predefined **shared folder**, constructs a WhatsApp message (with attachments if any), and sends it automatically to the employee distribution list.  

This reduces manual effort from HR teams and ensures consistent communication across all employees.

---

## ✨ Key Features

- Retrieves HR content (video, file, text) from shared folder  
- Automatically composes WhatsApp messages with attachments  
- Sends to all employees in distribution list  
- Logs sent messages and errors for audit purposes  
- Built with **UiPath REFramework** for stability and error handling  

---

## 📂 Project Structure

| Folder/File                    | Description                                                   |
|--------------------------------|---------------------------------------------------------------|
| `Main.xaml`                    | Entry point of the automation                                |
| `OneDrive.xaml`                | Workflow to fetch files from OneDrive/Shared folder          |
| `ConstructMessage.xaml`        | Builds WhatsApp message (text + attachment)                  |
| `WhatsApp_OpenAndSendMsg.xaml` | Sends message via WhatsApp Desktop/Web                       |
| `Data/`                        | Configurations and supporting files                          |
| `project.json`                 | UiPath project metadata                                      |
| `README.md`                    | This documentation                                           |

---

## 🚀 How to Run

1. Ensure HR content is available in the **shared folder** (OneDrive/HR repository).  
2. Open `Main.xaml` in UiPath Studio.  
3. Update `Config.xlsx` or arguments if needed (e.g., folder paths, WhatsApp settings).  
4. Run the process manually or publish to **UiPath Orchestrator**.  
5. Verify WhatsApp messages are delivered to the employee distribution list.  

---

## 📋 Requirements

- UiPath Studio (Enterprise, v22.10 or higher)  
- Access to HR shared folder (e.g., OneDrive)  
- WhatsApp Desktop installed and configured (logged in with HR official number)  
- Excel (optional, if employee list managed via Excel)  

---

## 📬 Contact

For questions, improvements, or collaboration:  

- Email: **fadillah650@gmail.com**  
- LinkedIn: [Enrico Naufal Fadilla](https://linkedin.com/in/enrico-naufal-fadilla-54338a256)  
