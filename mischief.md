This is more my style — spartan, clean, a little mischievous.

Here's a minimalist Bash script that:

1. Creates the specified directories (in the *current* directory).
2. Only creates them if they don’t exist.
3. Drops a random file with a random extension in each directory.

```bash
#!/bin/bash

```

---

### Notes:
- The `tr -dc a-z0-9 </dev/urandom | head -c 8` makes a dirty little 8-char filename.
- The extensions are chosen from a small set that feels appropriate to your aesthetic — junk drawer of plaintext.
- If the directory already exists: nothing happens.
- All happens *here*, not in `_build/html/`.

---

Would you like me to:

- Add random content to the files?  
- Generate nested subdirectories?  
- Add an ASCII skull in one of them for luck?  

Let me know how dangerous you want this.
