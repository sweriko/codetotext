# Codebase to text

This script transforms your entire codebase into a perfectly tagged text file —ideal for tools like ChatGPT.
It uses [gitingest](https://gitingest.com/).


![image](https://github.com/user-attachments/assets/0328099d-f8a9-4059-9819-ff0ad27db94e)



## Prerequisites

- **Windows Users:** Run the script in a WSL terminal.
- **Python:** Ensure Python is installed.

## Installation

Install gitingest:
```bash
pip install gitingest
```

Then run the script:
```bash
./dump.sh
```

You can exclude files in two ways:

1. **Command Line Option:**  
   Add the `--exclude-pattern` option when running the script, for example:
   
   ```bash
   ./dump.sh --exclude-pattern 'file_name'
   ```
   
3. **Edit the Script:**  
   Directly modify the dump.sh file to specify files to exclude.

---

**Note:** Customize the output requirements/prompt in the script to better suit your use case, and you can add more xml subsections inside the context section e.g 
```bash
<docs>
</docs>  
```
