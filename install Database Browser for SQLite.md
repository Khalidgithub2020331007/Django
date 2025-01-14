To install **Database Browser for SQLite** (also known as **DB Browser for SQLite**) on a Linux system, follow these steps based on your distribution:

---

### **For Debian/Ubuntu-based Distributions**
1. **Update your package list**:
   ```bash
   sudo apt update
   ```

2. **Install DB Browser for SQLite**:
   ```bash
   sudo apt install sqlitebrowser
   ```

3. **Run DB Browser for SQLite**:
   ```bash
   sqlitebrowser
   ```

---

### **For Fedora-based Distributions**
1. **Install DB Browser for SQLite**:
   ```bash
   sudo dnf install sqlitebrowser
   ```

2. **Run DB Browser for SQLite**:
   ```bash
   sqlitebrowser
   ```

---

### **For Arch-based Distributions (e.g., Manjaro)**
1. **Install DB Browser for SQLite** using `pacman`:
   ```bash
   sudo pacman -S sqlitebrowser
   ```

2. **Run DB Browser for SQLite**:
   ```bash
   sqlitebrowser
   ```

---

### **For OpenSUSE**
1. **Install DB Browser for SQLite**:
   ```bash
   sudo zypper install sqlitebrowser
   ```

2. **Run DB Browser for SQLite**:
   ```bash
   sqlitebrowser
   ```

---

### **If It's Not Available in Your Package Manager**
If the package isn't available or you want the latest version, you can use the **official AppImage** or **build it from source**.

#### **Using AppImage**
1. **Download the AppImage**:
   ```bash
   wget https://github.com/sqlitebrowser/sqlitebrowser/releases/latest/download/DB.Browser.for.SQLite-x86_64.AppImage
   ```

2. **Make it executable**:
   ```bash
   chmod +x DB.Browser.for.SQLite-x86_64.AppImage
   ```

3. **Run the AppImage**:
   ```bash
   ./DB.Browser.for.SQLite-x86_64.AppImage
   ```

#### **Build from Source**
If you prefer building from source, follow the instructions on their [GitHub page](https://github.com/sqlitebrowser/sqlitebrowser).

---

### **Verify Installation**
To confirm the installation, you can check the version:
```bash
sqlitebrowser --version
``` 

Enjoy working with SQLite databases! 😊
