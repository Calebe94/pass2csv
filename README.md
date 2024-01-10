# pass2csv 🔑

`pass2csv` is a Shell script designed to parse and convert passwords stored using the `pass` password manager into a format compatible with KeePass, a popular password manager. It converts passwords into a CSV-like format that can be imported into KeePass or KeePassXC.

## Details ℹ️

The script performs the following actions:

- Processes each entry in the `pass` password store.
- Excludes `.git` folders and hidden files.
- Converts the passwords into a CSV-like format compatible with KeePass.

## Dependencies 🛠️

- `pass` password manager installed
- Shell shell

## Usage 🚀

1. **Clone the Repository**: Clone the `pass2csv` repository to your local machine.

```bash
git clone https://github.com/your-username/pass2keepass.git
```

2. **Set Environment Variables (Optional)**: If your `pass` password store is located in a directory other than the default (`~/.password-store`), set the `PASS_PATH` variable to the appropriate directory:

```bash
export PASS_PATH=/path/to/your/password-store
```

3. **Run the Script**: Execute the `pass2csv` script:

```bash
bash pass2keepass.sh > output.csv
```

This will generate an `output.csv` file containing the converted passwords in a KeePass-compatible format.

4. **Import into KeePass**: Open KeePass or KeePassXC, and import the generated `output.csv` file using the appropriate import functionality.

🚨 Make sure to review the output CSV file before importing it into KeePass to ensure all passwords are correctly formatted.

# Developer

| <img src="https://github.com/Calebe94.png?size=200" alt="Edimar Calebe Castanho"> |
|:---------------------------------------------------------------------------------:|
| [Edimar Calebe Castanho (Calebe94)](https://github.com/Calebe94)                  |

# License

All software is covered under [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).
