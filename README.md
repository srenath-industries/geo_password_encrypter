![alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.istockphoto.com%2Fphotos%2Fglobe&psig=AOvVaw3dNZ2RhPOWK4AuOY-iBQH5&ust=1638419539934000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCLCzzMjiwfQCFQAAAAAdAAAAABAD.jpg?raw=true)

# Note: Internet is mandatory for getting your current location

## Project Description

This program is to create a encryption password with a given Key and can get access when both the encryption  is at same location as 
   the password is created with the latitude and longitude
----------------------------------------------------------------
# Change the ipinfo API Token (if needed):

Code:
     <p>gsk_geo_encryption.TOKEN="API_TOKEN"</p>
----------------------------------------------------------------
## Getting the encrypted_password and timer with a class:


Code:
<p>object1=gsk_geo_encryption.Keys()<p>
password,seconds=object1.password_encrypted()

----------------------------------------------------------------
Classes: 
        <p> Keys
----------------------------------------------------------------
Inbuilt Functions(Unchangable):
<p>
                  geo_lat_long_convertor()
<p>
                  encryption()
<p></p>
----------------------------------------------------------------
<p>
Usable Functions(Changable):<p>
                            password_encrypter
<p>

---------------------------------------------------------------
Exceptions:
<p>
           ConnectionError

