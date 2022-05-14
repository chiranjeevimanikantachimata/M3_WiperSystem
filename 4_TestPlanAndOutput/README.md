# HIGH LEVEL TEST PLAN 
 
<html> 
<body> 
<!--StartFragment--> 
 
Test ID | Description | Input | Expected output | Actual Output | status 
-- | -- | -- | -- | -- | -- 
01 | Ignition On |  Pressing Button 1st 2sec  | key status | Key Status Displayed |✅ 
02 | Wiper On | Pressing user button once | Wiper Status-1Hz | Wiper Status Displayed |✅ 
03 | Wiper On | Pressing user button twice | Wiper Status-4Hz | Wiper Status Displayed |✅ 
04 | Wiper On | Pressing user button thrice | Wiper Status-8Hz | Wiper Status Displayed |✅ 
05 | Ignition Off | Pressing Button 1st 2sec  | Ignition key status | key status Displayed |✅ 
 
<!--EndFragment--> 
</body> 
</html> 
 
 
# LOW LEVEL TEST PLAN 
 
<html> 
<body> 
<!--StartFragment--> 
 
Description | Input | Expected output | Actual Output | Status 
-- | -- | -- | -- | --  
ignition_on() | User Button Press 1st 2sec | RED LED ON | RED LED ON | ✅ 
LED cycle | Button Press once | All LEDs ON | All LEDs ON | ✅ 
LED cycle | Button Press twice | All LEDs ON | All LEDs ON | ✅ 
LED cycle | Button Press thrice | All LEDs ON | All LEDs ON | ✅ 
ignition_off() | User Button Press 2nd 2sec | RED LED OFF | RED LED OFF | ✅ 
 
<!--EndFragment--> 
</body> 
</html>


# **OUTPUT IMAGES**

![photo_2022-05-14_10-35-29](https://user-images.githubusercontent.com/101035658/168411780-85ceb31f-dbbc-4c14-ae01-5dbc8445adcb.jpg)

![1 3](https://user-images.githubusercontent.com/101035658/168411717-9fbd2982-7714-4823-b76f-bcbfead5c014.jpg)

![1 6](https://user-images.githubusercontent.com/101035658/168411757-99b6207d-f961-4ea3-aeeb-11d38c6190f4.jpg)

![1 4](https://user-images.githubusercontent.com/101035658/168411715-de195ad6-be5c-4b78-a796-84a4938f9c92.jpg)

![1 2](https://user-images.githubusercontent.com/101035658/168411718-58d5b9da-4e82-444d-a0ed-2113f8d969ed.jpg)

