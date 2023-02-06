# HOSPITAL MANAGEMENT SYSTEM
## PROJECT OVERVIEW 
In this project **HOSPITAL MANAGEMENT SYSTEM** website is to manage patients during the *Covid pandemic situation*,the patients with medical issues cannot come to hospital for all situation,so this website is helpfull for them to consult a doctor.
### MODULE DESCRIPITION
1. admin login
* admin home page
2. patient login
* patient home page
3. doctor login
* doctor home page
### SAMPLE CODING
#### NEW REGISTRATION
```python
u = input("Input your username!!:")
        p = input("Input the password (Password must be strong!!!:")
        mycursor.execute("insert into user_data values('" + u + "','" + p + "')")
        mysql.commit()
        
#### Enter the username and password of the user whose data is to display
```python
   a = int(input("ENTER YOUR CHOICE:"))
                # if user wants to enter administration option
                if a == 1:
                    print("""
                            1. Display the details
                            2. Add a new member
                            3. Delete a member
                            4. Make an exit
                                                     """)
                    b = int(input("Enter your Choice:"))
                    if b == 1:
                        print("""
                                1. Doctors Details
                                2. Nurse Details
                                3. Others
                                                 """)
