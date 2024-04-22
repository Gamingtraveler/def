while True:
    ### a welcome message
    print("Welcome to the ... dungeon !")
    print("You are a participation from big time game.")
    print("As the participation you need to find the treasure and way out.")
    print("choice you character")

    print("adam")
    print("jackson")

    ### Prompt user for a choice
    
    characterChoice = input("> ")

    ## raw    
    if (characterChoice =="adam"):
        print("choice you way adam")
        print("left way or right way")
    

        wayChoice = input("> ")

        if(wayChoice == "left way"):
          print("You go to Left way.")
          print("As you walk in, you see a sleeping giant snake .")
          print("Do you want to kill that snake or bypass away?")
          print("yes or no")

          snakeChoice = input("> ")

          if(snakeChoice == "yes"):
            print("You try to kill the snake.")
            print("You dead.")
            player_dead = input("Do you want to start new game? (yes/no): ").lower()

            if player_dead == "yes":
                  continue
            else:
                 print("Exiting the game. Goodbye!")

            ###
                      
          elif(snakeChoice == "no"):
            print("You decide to not kill the giant snake.")
            print("you see 3 creature you rember they called fur wendigo,rake and chimera")
            print("you want kill them or no ")

          creatureChoice = input("> ")

          if(creatureChoice == "yes"):
            print("you were bitten by a chimera")
            print("you dead")
            player_dead = input("Do you want to start new game? (yes/no): ").lower()

            if player_dead == "yes":
                continue
            else:
                print("Exiting the game. Goodbye!")
                break

            ###

          elif(creatureChoice == "no"):
            print("you try to speak with them and the need help")
            print("you giving them antri curse")
            print("the turn into moose,a man and cat.the man say his nam paul.paul say thank you.he tell how they tunr in to a monster")
            print("they are same participation before you. but paul try to speak with giant snake ")
            print("ironicly the snake angry and turn the into monster")
            print("you and paul decide make party to expolere other word")
            player_dead = input("Do you want to start new game? (yes/no): ").lower()

            if player_dead == "yes":
                continue
            else:
                print("Exiting the game. Goodbye!")
                      
                break
            ###

          else:
            print("Invalid choice. Please enter yes or no.")

        if(wayChoice == "right way"):
          print("You chose to go into the Right way.")
          print("As you walk in, you see medusa and rock golem")
          print("Do you want to or fight them or no?")

          fightChoice = input("> ")

          if(fightChoice == "yes"):
            print("you turning into stone")
            print("you dead")
            player_dead = input("Do you want to start new game? (yes/no): ").lower()

            if player_dead == "yes":
                continue
            else:
                print("Exiting the game. Goodbye!")
                      
                break
            ###
       
          elif(fightChoice == "no"):
            print("You decide using anti cursed on you bag.")
            print("medusa turn into  normal human and the rock giant turn into monkey.")
            print("they talk to you and telling how they turn into monster")
            print("they are same participation before you because they want open some treasure.ironicly its wrong treasure")
            print("they see demigod out from the box and make them be monster")
            print("you find exit way and start new adventure with them")
            player_dead = input("Do you want to start new game? (yes/no): ").lower()

            if player_dead == "yes":
                continue
            else:
                print("Exiting the game. Goodbye!")
                      
                break


        ###
            
    if(characterChoice == "jackson"):
        print("choice you path jackson")
        print("thorfin path or eren path ")

        pathChoice = input("> ")

        if(pathChoice == "thorfin"):
           print("you kind to other people right")
           print("so choice what do you want")
           print("mud biome or dessert biome")

        biomeChoice = input("> ")
        
        if(biomeChoice == "mud"):
          print("you go to mud biome")
          print("you see a kitsune bleeding")
          print("you try to save her")
          print("use alcohol or cloth")

          helpChoice = input("> ")
          if(helpChoice == "alcohol"):
            print("she alive")
            print("now she follow you")
            print("you choice to live with her")

          elif(helpChoice == "cloth"):
            print("she die")
            print("her body turned into smoke")
            print("you die")
            player_dead = input("Do you want to start new game? (yes/no): ").lower()

            if player_dead == "yes":
                continue
            else:
                print("Exiting the game. Goodbye!")
                              
                break
        
        if(biomeChoice == "dessert"):
           print("you walking to dessert")
           print("you find temple you get in")
           print("you see sekeleton try to kill you")    
           print("you use a rock to fight them")        
           print("you see a chest with much diamond you go home and live happy") 
           player_dead = input("Do you want to start new game? (yes/no): ").lower()

           if player_dead == "yes":
              continue
           else:
            print("Exiting the game. Goodbye!")
                              
           break
        if(pathChoice == "eren"):
         print("so you will sacrfie the word just for you love")
         print("its good but not every people like that")
         print("choice your biome")
        
    biomeChoice2 = input("> ")
    
    if(biomeChoice2 == "jungle"):
          print("you see a village with many dark live")
          print("you see your best frind in jail")
          print("you try to burn the village")
          player_dead = input("Do you want to start new game? (yes/no): ").lower()

          if player_dead == "yes":
            continue
          else:
            print("Exiting the game. Goodbye!")
                              
            break
        
    elif(biomeChoice2 == "beach"):
          print("you village with mermaid")
          print("they look perform the ceremony")
          print("in altar you see your best friend be an offering")
          print("you kill all the village and save your friend")

       
else:
  print("try again.")



