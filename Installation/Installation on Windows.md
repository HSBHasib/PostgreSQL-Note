## 1. Installation on Windows

### Download and Install
1. Visit [PostgreSQL Official Download Page](https://www.postgresql.org/download/windows/)
2. Download the installer (recommended: latest stable version)
3. Run the installer and follow these steps:
   - Choose installation directory (default: `C:\Program Files\PostgreSQL\16`)
   - Select components: PostgreSQL Server, pgAdmin 4, Command Line Tools
   - Set data directory (default: `C:\Program Files\PostgreSQL\16\data`)
   - **Set superuser password** (remember this!)
   - Set port (default: 5432)
   - Set locale (default is fine)

### Verify Installation
```bash
# Open Command Prompt or PowerShell
psql --version
# Should output: psql (PostgreSQL) 16.x
```

### First Time Setup
```bash
# Connect to PostgreSQL as superuser
psql -U postgres

# You'll be prompted for the password you set during installation
```
