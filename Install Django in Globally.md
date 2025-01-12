To install Django globally, follow these steps:

### 1. Install Python and `pip` (if not already installed)
Make sure Python and `pip` are installed on your system. You can check by running:
```bash
python --version
pip --version
```

### 2. Install Django Using `pip`
With `pip` installed, you can install Django globally by running:
```bash
pip install django
```

This will install the latest version of Django globally on your system, making it accessible from any directory.

### 3. Verify Django Installation
To confirm that Django has been installed globally, you can check the version by running:
```bash
django-admin --version
```
This should output the installed Django version.

### 4. Update Django (Optional)
If you ever need to update Django to the latest version, you can use:
```bash
pip install --upgrade django
```

### 5. Uninstall Django (Optional)
If you want to uninstall Django, you can run:
```bash
pip uninstall django
```

By installing Django globally, it will be available for all projects on your system without needing to set up a virtual environment each time. However, using a virtual environment is generally recommended for managing dependencies per project.
