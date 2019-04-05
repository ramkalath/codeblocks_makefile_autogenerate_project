if you are using Ubuntu 18.04 or any other version, the code needs some modifications.

Firstly, whereever you find '.codeblocks' change it to .config/codeblocks

Here are the places you need to change it
1) In the pdf file codeblocks_setup.pdf
2) In cbproject.py (follow the instructions in codebocks_setup.pdf to obtain this file) change .codeblocks to .config/codeblocks/
3) finally, in .bashrc change to 

  alias cb_project_create="python ~/.config/codeblocks/cbproject.py"
  cb(){codeblocks $1>/dev/null &!}
  
  if it does not work, email me at ramkalath_at_gmail.com.
