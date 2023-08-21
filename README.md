# injectShellCode
# Usage: gcc -o fileName fileEXE
# Idea:
  Insert the code at the end of the file, do not change the data of the file. Change the AddressOfEntryPoint to point to this code. After the code runs and displays the MessageBox, there is a Jmp command to return to the original AddressOfEntryPoint.
