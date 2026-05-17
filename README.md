# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit

### Name : MOHANA PRIYA R

### Reg No : 212224220065

## AIM: 

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version
   

## OUTPUT:
1 .**VIRTUAL BOX:**

Downloaded .exe file.

<img width="389" height="112" alt="Screenshot 2026-04-20 212902" src="https://github.com/user-attachments/assets/e0b3cb9d-7869-463d-9d4f-1cba0d67e784" />


Installer wizard.

<img width="430" height="338" alt="Screenshot 2026-05-17 185550" src="https://github.com/user-attachments/assets/eed15b94-03f7-4eae-a988-476795f079dc" />

Network interface warning.

<img width="405" height="327" alt="Screenshot 2026-05-17 185559" src="https://github.com/user-attachments/assets/e0a7eb1e-03bd-4580-9ee1-738e6bc67a46" />


Installation Begins.

<img width="414" height="338" alt="Screenshot 2026-05-17 185607" src="https://github.com/user-attachments/assets/829785b7-5818-4774-8ca8-33f357e37885" />


2 .**KALI LINUX:**

Installed kali linux.

<img width="814" height="532" alt="Screenshot 2026-05-17 185417" src="https://github.com/user-attachments/assets/c7e69a5f-1c58-469d-b97c-cec141699d42" />
<img width="489" height="446" alt="Screenshot 2026-05-17 185206" src="https://github.com/user-attachments/assets/e27f42a0-0c4c-49e6-a1cc-22c78788e61e" />

Kali linux terminal.

<img width="537" height="438" alt="Screenshot 2026-05-17 185309" src="https://github.com/user-attachments/assets/c0b6d756-d31c-47e1-a81b-2429465dd8a1" />


3 .**SLEUTH-KIT:**

<img width="1159" height="671" alt="Screenshot 2026-05-17 190448" src="https://github.com/user-attachments/assets/f441ff93-747b-4e0a-97f1-cb0203886060" />

<img width="370" height="380" alt="Screenshot 2026-05-17 190157" src="https://github.com/user-attachments/assets/d88e08b9-c7bd-4fba-86ff-dd04406865ef" />


<img width="507" height="537" alt="Screenshot 2026-05-17 190314" src="https://github.com/user-attachments/assets/2fa4a758-8c4e-48d3-804f-c1b8fa418277" />


<img width="634" height="709" alt="Screenshot 2026-05-17 190323" src="https://github.com/user-attachments/assets/e32a4a26-6223-4c77-bbbf-50b0acd09a16" />


<img width="549" height="586" alt="Screenshot 2026-05-17 190335" src="https://github.com/user-attachments/assets/c4643c0f-f3de-4b40-995e-533da7941d06" />


<img width="570" height="297" alt="image" src="https://github.com/user-attachments/assets/2512c2bb-e885-4829-92e1-271d5fd718fc" />


<img width="1368" height="392" alt="Screenshot 2026-05-17 180012" src="https://github.com/user-attachments/assets/a66af998-0ff9-4887-bf82-a72d5ad12272" />


<img width="1776" height="664" alt="Screenshot 2026-05-17 180021" src="https://github.com/user-attachments/assets/cb36614b-b2c9-4390-a6cf-c06ab5d59104" />


## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
