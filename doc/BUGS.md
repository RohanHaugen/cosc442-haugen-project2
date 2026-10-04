1. No tests run.
testAddItem_addsItem_correctSlot()/every single one
VendingMachineJava assigns slots by doing i<=4, creating 5 slots for a 4 slot system
I looked at the error message saying Index 4 out of bounds for length 4
I changed i<=4 to i <4