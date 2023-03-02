# Linkedin-scrapper
 This repo permits you to retrieve all employees data from a Linkedin company.
 You can output the result to a csv.

 I am using Linkedin voyager API to retrieve data : https://www.linkedin.com/voyager/api/.

 Any user will not be warned.

1. Install requirements

> pip install -r requirements

2. Prebuilt commands

        ---- Credentials ----

        -e  precise email to connect with Linkedin
        -p  precise password to connect with Linkedin, it might be between quotes

        Credentials are not saved to any distant server or anything, it's only used by the program.

        I don't recommend to use '-p' argument, because the plain text password could appear in command history

        ---- Parameters ----

        -o  output result to a output.csv
        -no no output
        -c  precise which company you want to retrieve employees from (e.g. apple, uber-com, ...)
        -ec precise how much employee should the program output (it has to be divisible by 25, default 25)
        -h  show this help menu
        

Important : This might be use for entertainment only.