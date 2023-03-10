# Minecraft-Troller-
#WARNING:this tool is for EDUCATIONAL PURPOSES ONLY,this tool was created for no evil,i handle no responsibility with your actions 
#importing modules

import time

import random

#creating the logo

print("""

███╗   ███╗██╗███╗   ██╗███████╗ ██████╗██████╗  █████╗ ███████╗████████╗    ████████╗██████╗  ██████╗ ██╗     ██╗     ███████╗██████╗ 

████╗ ████║██║████╗  ██║██╔════╝██╔════╝██╔══██╗██╔══██╗██╔════╝╚══██╔══╝    ╚══██╔══╝██╔══██╗██╔═══██╗██║     ██║     ██╔════╝██╔══██╗

██╔████╔██║██║██╔██╗ ██║█████╗  ██║     ██████╔╝███████║█████╗     ██║          ██║   ██████╔╝██║   ██║██║     ██║     █████╗  ██████╔╝

██║╚██╔╝██║██║██║╚██╗██║██╔══╝  ██║     ██╔══██╗██╔══██║██╔══╝     ██║          ██║   ██╔══██╗██║   ██║██║     ██║     ██╔══╝  ██╔══██╗

██║ ╚═╝ ██║██║██║ ╚████║███████╗╚██████╗██║  ██║██║  ██║██║        ██║          ██║   ██║  ██║╚██████╔╝███████╗███████╗███████╗██║  ██║

╚═╝     ╚═╝╚═╝╚═╝  ╚═══╝╚══════╝ ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝        ╚═╝          ╚═╝   ╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚══════╝╚══════╝╚═╝  ╚═╝
""")
                                                                                                                                       











#prompting the user for input

print('\nWelcome to the Force Op Program!')

ip = input('\nPlease enter the IP of the Minecraft Server: ')

#generating a random number

randnum = random.randint(0,1000)

#initiating the force op process

print('\nInitiating Force Op Process...')

time.sleep(2)

print('\nForce Op Process Successful!')

#displaying the result

print('\nForce Op Successfully Applied to Server: ' + ip + '\nForce Op Code: ' + str(randnum))

#ending the program

print('\nThank you for using the Force Op Program!')
