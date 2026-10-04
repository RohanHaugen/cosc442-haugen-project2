1. No tests run.
testAddItem_addsItem_correctSlot()/every single one
VendingMachineJava assigns slots by doing i<=4, creating 5 slots for a 4 slot system
I looked at the error message saying Index 4 out of bounds for length 4
I changed i<=4 to i <4
2. insertMoney isnt inserting 0 dollars
testInsertMoney_zeroValue_noIncrease()
insertMoney is checking if value <1
I saw that it was throwing an exception and saw where the exception was being thrown
I changed it to <0 as that is the opposite of >=0, as the documentation describes.