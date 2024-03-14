
![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/189289bc-ae81-4bab-a355-eb25e089518e)
FIG.1 COPYING LOCAL FILES IN A CONTAINER

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/296a8635-b99d-46ce-ad2e-cf2d05da27b2)

FIG.2 RUNNING create_large_file.sh script

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/ad2cf3ea-41b9-4e8b-85a6-c472bfe9724e)

FIG.3 Creating the bash script where are all the functions required

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/ef32bddb-f722-4394-8d6b-e616d3dfd1eb)

FIG.4 Function for checking the privileges. EUID -> Effective User ID, -ne -> not equal

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/d82c27e5-bf40-4479-a466-42899dff68d6)

FIG.5 Function for showing the error

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/f53841d8-02f9-4200-9bc1-1ccc11a41cf7)

FIG.6 Function for print home directory of the curent user

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/fffdfe81-ea00-45a6-87a0-41b1abd20e1d)

FIG.7 Function for listing all usernames from passwd. cut -> function for cutting text, -d: -> delimiter, in our case ":", -f -> which field we select, in our case 1, -z -> if strign is NULL

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/9859b7f6-bac5-41b6-9b21-f77ba403ac87)

FIG.8 Function for counting users wc -l -> function for counting lines in a text file

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/159febc2-11aa-4412-a85a-3004c1c88144)

Fig.9 Function for printing home directory for any user we enter. getent -> function for getting info about users, grups, password from system data base. in our case from passwd we want users

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/6b86ac8c-a4d3-44f8-9768-d28522a25884)

Fig.10 Function for printing unic ID for users which are in a range we select -v -> variable parameters (min and max) -F -> field delimiter

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/1463c125-0962-4a48-8bb4-0479f4a8b9fe)

FIG.11 Function for listing all users with standard shell. grep -> used for searching string in text files or pipes, =E -> extended expression

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/05348647-6a38-4ca9-8223-625424c198d4)

FIG.12 Function for replace. sed -> process text flux, /,// -> old text   \,\\ -> new text  , s,g -> global replacing

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/d04547d6-cbf7-4eda-b105-90ba3f149ce6)

FIG.13 Function for printing private IP  

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/5189ddc4-a09a-4411-b248-37021a0baa52)

FIG.14 Function for printing public IP

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/16e62e56-605e-4e7a-87da-d56a27aeb70f)

FIG.15 Adding user john

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/c619a8d3-f17c-44b0-afb8-a449162cb0b4)

FIG.16 Function for selecting user john

![image](https://github.com/ValiFloricescu/DevOps_Test/assets/116838797/e8c2100b-c4d8-425f-8674-b1d42fa33a65)

FIG.17 Printing john home directory

