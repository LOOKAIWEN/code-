https://create.withcode.uk/run/BYs

print("Title of program: CCA Matching Personality test")
print()
print("Welcome to DHS! Please answer the following questions truthfully and we'll suggest a CCA for you!")
print("Please respond with a number between 1 - 5, where 1 is strongly disagree and 5 is strongly agree.")
print()
print("Good luck!")

tech1 = input("I enjoy building and fixing things.")

outdoor1 = input("I'll go crazy if I do not go out of the house for the whole day.")

music1 = input("I can see colours in my mind when I hear music.")

tech2 = input("I know how to build apps and websites.")

outdoor2 = input("I'm good with tying knots and ropes.")

music2 = input("I play a musical instrument well.")

tech3 = input("I have always displayed a keen interest in teachnology.")

outdoor3 = input("I enjoy indulging in outdoor activities.")

music3 = input("I have a love for music.")

tech_final = int(tech1) + int(tech2) + int(tech3)
outdoor_final = int(outdoor1) + int(outdoor2) + int(outdoor3)
music_final = int(music1) + int(music2) + int(music3)

print()

if tech_final > outdoor_final and tech_final > music_final:
  print("You might be suitable for Infocomm club! What do you think?")
elif outdoor_final > music_final:
  print("You might be suitable for ODAC! What do you think?")
else:
  print("You might be suitable for Band! What do you think? ")

print()  
print("Hope this mini test has been useful to you!")
print()
print("All the best to you in discovering the best CCA for yourself:)))")


  

