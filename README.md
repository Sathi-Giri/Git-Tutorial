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
