Цветанка Црљеница 173299

![control_flow_graph](https://github.com/ccrljenica/SI_2023_lab2_173299/assets/63556447/0f55e045-a454-441a-bc1e-a272cd5b0536)

цикломатската комплексност  = 8, има 8 региони

Every branch:
1. 
user is null.
user.getPassword() is null.
user.getEmail() is null.

2.
existingUser.getEmail()==user.getEmail()
email contains @ and .        
existingUser.getUsername() == user.getUsername()  

3.
passwordLower.contains(user.getUsername().toLowerCase())

4.
user.getUsername().toUpperCase())
password.length()>8

5.
user.getUsername()==null  
existingUser.getEmail() != user.getEmail()
