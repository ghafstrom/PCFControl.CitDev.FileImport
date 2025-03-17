# Custom File Upload Control for Power Apps (Canvas App)  

This repository contains a **custom PCF control** for file uploads in **Canvas Apps**. The control allows users to upload files via **clicking a button** or **drag-and-drop**, with various customization options.  

### ✨ Features:  
- Supports **single and multiple file uploads**.  
- Choice between **Button** and **CompoundButton** styles.  
- Customizable **icons** related to file uploading.  
- Supports **file extension filtering**.  
- **Drag-and-drop** functionality.  
- **Theme-aware colors** (adapts to the current Power Apps theme).  
- Built-in **upload progress animation** (can be disabled).  
- Modern **text and display styles**, similar to Canvas Apps’ native controls.

![PCFControl.CitDev.FileImpor](https://citdev.pl/blog/wp-content/uploads/2025/02/Untitled-1-320x320.gif)
![PCFControl.CitDev.FileImport](https://citdev.pl/blog/wp-content/uploads/2025/02/animacja.gif)
![PCFControl.CitDev.FileImport](https://citdev.pl/blog/wp-content/uploads/2025/03/2025-03-16_18h39_48.png)

### 📁 File Data Structure  
Uploaded files are stored in a **JSON array** with the following properties:  
- `name` – file name with extension  
- `size` – file size in bytes  
- `contentBytes` – Base64-encoded file data  

### 🔗 More info To learn more about the control, visit my blog -> [Karol Kozłowski | CitDev](https://citdev.pl/blog/)
