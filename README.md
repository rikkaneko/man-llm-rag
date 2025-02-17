# man-llm-rag
Help assistant for linux commands using small LM models with RAG (Retrieval Augmented Generation).  
Below is the output from qwen:2.5:14b, which I plan to produce similiar result using smaller model with RAG.
## Expected output
```bash
$ help chmod --ask
# What do you want to know about `chmod`?
# > How to set read/write permission for directories recursively?
# If you want to apply this to a directory named `dir`, you would run:
# `chmod -R 755 /path/to/dir`
# 
# Here's a breakdown of the command:
# - `chmod`: The command used to change file permissions.
# - `-R` or `--recursive`: Applies the command to the directory and all its subdirectories and files.
# - `755`: The octal permission code where:
# - `7` (binary `111`) means read, write, and execute (`rwx`) for the owner.
# - `5` (binary `101`) means read and execute (`r-x`) for the group.
# - `5` (binary `101`) means read and execute (`r-x`) for others.
# 
# This command will set the permissions such that the owner can read, write, and execute files and directories,
# while the group and others can only read and execute.
