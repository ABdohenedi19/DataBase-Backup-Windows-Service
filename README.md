# DatabaseBackupService

A **Windows Service** for automated database backups.  
It can run in two modes:
- **Console Mode** → run and monitor the service interactively.  
- **Background Mode** → run silently as a Windows Service.  

The service features:
- Scheduled backups of the target database.  
- Detailed logging of all operations.  
- Recovery mechanism to resume safely after failures.  

---

## 📸 Screenshots

### Run in Console Mode
![Console Mode 1](https://github.com/user-attachments/assets/938c888c-d58b-405b-9ce6-a728e49b9ee1)  
![Console Mode 2](https://github.com/user-attachments/assets/59a77814-001b-45f7-9ae8-cc12e499509b)  

### Run in Background Mode
![Background Mode 1](https://github.com/user-attachments/assets/2ae2b7ba-5ab9-4e1b-82bc-fa1aa6ad7c77)  
![Background Mode 2](https://github.com/user-attachments/assets/ce7d6256-cd76-44ce-bffc-60f9f7367570)  

---

## 🚀 How to Download & Run

1. Go to the **[Releases](../../releases)** page of this repository.  
2. Download the latest build (`DatabaseBackupService.zip`).  
3. Extract the files to a local folder.  

### Run in Console Mode
```bash
DatabaseBackupService.exe -console



