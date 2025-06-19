# Scripting_Project
simple and customizable shell script to automatically back up a directory and clean old backups. Ideal for system admins, developers, and hobbyists.

## 📦 Features

- Compresses target directory as `.tar.gz`
- Stores backups with timestamp
- Deletes backups older than N days
- Logs backup status to a file

## 🛠️ How It Works

The script:
1. Creates a compressed archive of the specified directory
2. Stores it in a backup folder
3. Deletes old backup files older than a configured threshold

## 📂 Directory Structure

- **SOURCE_DIR** → Directory to back up
- **BACKUP_DIR** → Where compressed backups are stored
- **LOG_FILE** → Output log file path
