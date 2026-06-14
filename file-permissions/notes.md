# File Permissions Notes

## Structure of Permissions
Owner | Group | Others

---

## chmod commands used

- chmod 777 file1.txt → full access (read/write/execute for everyone)
- chmod 644 file1.txt → owner can write, others can read
- chmod 600 file2.txt → only owner can read/write

---

## Meaning of common permission sets

- 777 → rwx rwx rwx (everyone full access)
- 644 → rw- r-- r--
- 600 → rw- --- ---

---

## Permission types

| Permission | Meaning 
|------------|--------
| r          | read (4) 
| w          | write (2) 
| x          | execute (1) 

---

## Numeric permission breakdown

| Number | Breakdown | Meaning 
|--------|-----------|--------
| 7      | 4+2+1     | rwx 
| 6      | 4+2       | rw- 
| 5      | 4+1       | r-x 
| 4      | 4         | r-- 
| 3      | 2+1       | -wx 
| 2      | 2         | -w- 
| 1      | 1         | --x 
| 0      | 0         | --- 

---

## Permission code meanings

| Code |    Meaning    | Access 
|------|---------------|-----------------------
| rwx  | full access   | read + write + execute 
| rw-  | file editable | read + write 
| r--  | read-only     | view only 
| -w-  | write-only    | modify only 
| --x  | execute only  | run only 
| ---  | no access     | blocked completely
