#shellsploit-library


Python library for shellsploit-framework(https://github.com/b3mb4m/shellsploit-framework) project.


#Usage
----------

       import shellsploit

       shellsploit = shellsploit.Engine()
       
       #Create shellcode
       shellcode = shellsploit.shellcode("linux86/binsh_spawn")
      
       #Encode it
       print shellsploit.encode("x86/xor", 1, shellcode)
       
       
       
#Bugs/Requests
---------------

Please do not forget to report bugs! You can submit an issue, pull request, or you can pm via email,


######b3mb4m@protonmail.com
