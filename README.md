# devops_task7
# DevOps Internship - Task 7: Environment Variables

## 1. Custom Variable
- **Command:** `export INTERN_NAME="Janzj"`
- **Result:** Variable accessible using `$INTERN_NAME`.

## 2. The PATH Configuration
- **Objective:** Add `~/myscripts` to the system PATH so scripts can be run globally.
- **Action:** Edited `~/.bashrc` to append the directory.
- **Command:** `export PATH=$PATH:~/myscripts`

## 3. Verification
- **Script Created:** `greet`
- **Location:** `/home/janzj/myscripts`
- **Test:** Executed `greet` from the root directory (`/`).
- **Result:** Script executed successfully without needing the full path.
- <img width="966" height="1020" alt="Screenshot 2026-01-29 103531" src="https://github.com/user-attachments/assets/0091ae1d-1500-4de4-9255-21d3346cb51f" />
<img width="966" height="1020" alt="Screenshot 2026-01-29 103526" src="https://github.com/user-attachments/assets/5e28c75d-ee78-471a-8608-1e389b7e9729" />
