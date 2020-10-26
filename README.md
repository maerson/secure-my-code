# secure-my-code

# Introduction

Usually I develop some small projects on the computer owned by the company.
I suspect IT possibly scan my computer in some secrety way. Also I don't trust *Github*/*GitLab*.

So the requirement is:
  - encrypted source code stored in Github.
  - encrypted source code stored in Disk.
  - encrypt/decrypt on the fly when editing the document.


# Implement

I write a small python script to achieve this goal, benefiting from the Python Script plugin of the Notepad++.

## Usage
  - Firstly, copy the python script to your notepad++ plugin dir(for example: npp.7.9.portable\plugins\PythonScript\scripts).
  - Launch notepad++, goto "plugins" -> "Python Script" -> "Script" -> "secure-my-code.py".
  - For the first time, it requests the password to encrypt the document and keeps it in memory.
  - If the user need to change the password, repeat the step 2 again.

## Dependency

  - https://github.com/ricmoo/pyaes
  - https://github.com/bruderstein/PythonScript

