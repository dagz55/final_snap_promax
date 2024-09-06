# 🌟 Azure Snapshot Management Project 🌟

Welcome to the Azure Snapshot Management project! This modern tool helps you efficiently manage Azure VM snapshots with ease and style. 💻☁️

## 🚀 Getting Started

### Prerequisites

- Python 3.8+ 🐍
- Azure CLI 🖥️
- Azure account with appropriate permissions 🔑
- direnv 🔧 (for managing environment variables)

### 📦 Installation

1. Clone this repository:
   ```
   git clone https://github.com/dagz55/azure-snapshot-management.git
   cd azure-snapshot-management
   ```

2. Set up direnv:
   ```
   direnv allow .
   ```
   This will automatically load the environment variables specified in the `.envrc` file when you enter the project directory.

3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

4. Configure Azure CLI:
   ```
   az login
   ```

## 🛠️ Usage

The main entry point for this project is `main.py`. You can run it using:

```
python main.py
```

This script will guide you through various snapshot management operations.

For specific operations, you can use the following scripts:

### 📸 Create Snapshots

Run the snapshot creation script:

```
python create_snapshot.py
```

### 🔍 Validate Snapshots

Validate your snapshots using:

```
python validate_snapshot_promax.py
```

### 🗑️ Delete Snapshots

Remove unnecessary snapshots:

```
python delete_snapy.py
```

### 🔄 Manage Snapshots

For comprehensive snapshot management:

```
python manage_snapshots.py
```

## 📊 Logging

Logs are stored in the `logs/` directory. Check `azure_manager.log` for detailed operation logs.

## 🛡️ Security

- Ensure your `credentials.txt` file is encrypted (`.gpg` extension).
- Never commit sensitive information to the repository.
- The `.envrc` file managed by direnv should not contain sensitive information. Use it for non-sensitive environment variables only.

## 🤝 Contributing

We welcome contributions! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for details.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 💡 Support

If you encounter any issues or have questions, please file an issue on the GitHub repository.

Happy snapshotting! 📸✨   %
