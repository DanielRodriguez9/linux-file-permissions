# 🔐 File Permissions Management in Linux

This repository documents a hands-on task completed as part of the **Google Cybersecurity Analyst course**, focusing on analyzing and modifying file and directory permissions in a Linux environment. The objective was to strengthen system security by controlling who can read, write, or execute specific resources.

> 📌 **Note:** The full report is in **Spanish**, as the course was taken in that language.

## 📄 Full Report (PDF)
📎 [View detailed report in PDF](./permisos_archivos_linux_actividad_cartera.pdf)

The document includes step-by-step explanations, terminal commands, and screenshots showing the entire process.

---

## 🧪 Practical Evidence

### 📁 1. Checking permissions with `ls -la`
Used to identify the current permissions of files and directories under the `projects` folder.

![ls -la](./capturas/detalles_archivo_directorio_ls.png)

---

### ✏️ 2. Changing permissions with `chmod`
Write permissions were removed for "others" on selected files.

![chmod](./capturas/cambios_permiso_archivo_chmod.png)

---

### 🕵️‍♂️ 3. Managing permissions for hidden files
Adjusted read/write access for `.project_x.txt`.

![chmod hidden file](./capturas/cambios_permiso_archivo_oculto.png)

---

### 🔒 4. Restricting access to a private directory
Only the user `researcher2` should have access to the `drafts` directory.

![chmod directory](./capturas/cambios_permiso_directorio.png)

---

## ✅ Conclusion

This task helped reinforce key concepts of **file permission management in Linux**, which are fundamental to maintaining operating system security. Commands like `chmod`, permission flags (`rwx`), and access control mechanisms were practiced and applied to real scenarios.

---

