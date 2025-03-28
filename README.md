# Breadboard-Vending-Machine-Portfolio-Page

# Overview
This project is a simplified vending machine circuit built on a breadboard, demonstrating fundamental digital logic concepts such as SR latches and delayed resets. The design simulates how a vending machine processes coin input and dispenses an item.
# Components Used

-Breadboard

-Slide switches (to represent coin inputs)

-Push-button switches (to simulate item selection)

-LEDs (to indicate machine state and item dispensing)

-Resistors 

-Integrated Circuits (ICs) for logic gates (AND, OR, NOR, etc.)
# Truth Table 
![Screenshot 2025-02-27 090014](https://github.com/user-attachments/assets/68b060fb-265d-4c2a-ac9e-380bed0e4270)

When A = 0 and B = 0, the latch holds its previous state, meaning no new action is taken.

When A = 0 and B = 1, the latch is set, meaning the vending machine is ready to dispense an item.

When A = 1 and B = 0, the latch is reset, meaning the machine does not dispense.

When A = 1 and B = 1, the state is invalid and should be avoided.

# Circuit Diagram
![Screenshot 2025-02-27 090323](https://github.com/user-attachments/assets/3d5ce77d-1240-4647-9246-0c48292d78e9)
![Screenshot 2025-02-27 090233](https://github.com/user-attachments/assets/d8f2429b-d206-4c2f-9453-4598023b4b0b)
# How it works 

# Coin Input
![Screenshot 2025-02-27 120412](https://github.com/user-attachments/assets/f0d02cc5-7677-4d41-8d9c-d570fabe10e0)

A user presses a switch, representing a valid coin input.

The logic gate network verifies the correct input combination.

If valid, the circuit sets the SR latch, meaning the vending machine is ready.

# Item Selection

![Screenshot 2025-02-27 120420](https://github.com/user-attachments/assets/301a000f-aedf-4e36-a756-3dbb04e3df2c)

The user presses a push-button switch, signaling item selection.

The SR latch maintains a high output, turning on an LED that represents the vending action.

# Delayed Reset Activation
![Screenshot 2025-02-27 120446](https://github.com/user-attachments/assets/edc46590-d5ae-451a-b925-893b41cfd25a)


The capacitor starts charging, preparing the reset mechanism.

The capacitor-resistor pair introduces a time delay before resetting.

# Reset & Ready for Next Transaction
![Screenshot 2025-02-27 120412](https://github.com/user-attachments/assets/1680e85c-dad8-4550-8238-e9b916f7f1b1)


The vending machine returns to its initial state, ready for another transaction.

# Old School Vending Machine
![Screenshot 2025-02-27 122704](https://github.com/user-attachments/assets/c4afed0f-69ee-4579-acc3-f41cbf934822)

Old-school vending machines, like the classic Coca-Cola machines from the 1950s, used electromechanical systems to process coins and dispense items. Our breadboard vending machine simplifies this by using basic digital logic components like switches, LEDs, and an SR latch. Instead of motors and sensors, our design uses logic gates to control when an item is dispensed. This project is a small-scale, educational version of how vending machines function at their core.

# Rasberry Pi Vending Machine 
A Raspberry Pi is a small, low-cost computer that you can use for many different projects, like building a robot, creating a home media center, or learning to code. It works like a regular computer—you can connect a monitor, keyboard, and mouse to it—but it's much smaller and cheaper. People use it for fun DIY projects, education, and even advanced tech applications!

# Creating A Vedning Machine 

In this picture, we are putting together the breadboard which basically works as the visualization for what we code to the Raspberry Pi.

![IMG_4756](https://github.com/user-attachments/assets/82493798-f6a7-48f5-8099-9702263e7718)

![IMG_4759](https://github.com/user-attachments/assets/8c201683-a104-49d1-81ab-fa7b47cd51e5)
# Diagrams 

![Screenshot 2025-03-27 104608](https://github.com/user-attachments/assets/949d5555-8369-4c40-aff3-f434573bf6c3)

![Screenshot 2025-03-27 100230](https://github.com/user-attachments/assets/bea775c9-ac54-4b2c-8ab2-c0dd78c9226e)

# LED ON
![IMG_4754](https://github.com/user-attachments/assets/643ba8ae-cde7-4a27-9694-53601648505c)

# LED OFF
![IMG_4760](https://github.com/user-attachments/assets/726a8747-9f9a-4135-99e5-754d8c31a174)










# References 
Justice, M. (2021). How Computers Really Work: A Hands-On Guide to the Inner Workings of the Machine. No Starch Press.

AuctionZip. (n.d.). Vintage 1960's Coca-Cola Cavalier CS-64 Vending Machine Professional Restoration. Retrieved February 27, 2025, from https://www.auctionzip.com/auction-lot/vintage-1960-s-coca-cola-cavalier-cs-64-vending-m_5974FD4AB6/







