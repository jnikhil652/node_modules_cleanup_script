# Cleanup Node Modules Script

The "cleanup_node_modules.sh" script is a Bash script designed to recursively search for and delete the `node_modules` folders in all folders and subfolders within a specified directory. It can help you free up disk space by removing unnecessary dependencies from Node.js projects.

## Usage

1. Download the "cleanup_node_modules.sh" script and save it to your desired location.

2. Open a terminal or command prompt and navigate to the directory where you saved the script.

3. Make the script executable by running the following command:

   ```bash
   chmod +x cleanup_node_modules.sh
   ```

4. To use the script, provide the root directory of the drive you want to search as an argument. For example:

   ```bash
   ./cleanup_node_modules.sh /path/to/drive
   ```

   The script will then go through all folders and subfolders in the specified drive and delete any `node_modules` folders it finds.

## Caution

- The script will permanently delete the `node_modules` directories. Make sure you have a backup or understand the implications before executing it.

- It's recommended to review the directories that will be affected by running the script to ensure no critical files are accidentally deleted.

## Disclaimer

This script is provided as-is, without any warranties or guarantees. The author is not responsible for any data loss or damage caused by running this script. Use it at your own risk.

## License

This script is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Additional Notes

If you encounter any problems or have questions about the script, feel free to [open an issue](../../issues) on GitHub.

---

_Remember to customize this README file based on your specific script's features, usage instructions, and any additional information you want to provide to users._
