# Rock, Paper, Scissors

You will be re-creating the classic game Rock, Paper, Scissors.  You will do this inside the file **logic.js**.  You will need to give the user a list of options to choose from.  They can either be the classic options (Rock, Paper, and Scissors) or you can make up your own.  Then, you will create a function **playGame** that will accept the user's choice as an input.  Your function should do all of the following actions.
- Remind the user of their choice.
- Randomly assign an option to the computer.  (Note: Math.random() will be needed here.)
- Tell the user which choice the computer made.
- Tell the user who won and why.

Below are some sample examples of the game.  You can run the game by going to Finder and double clicking on the file RPS.app (just like any other app you run on your Mac.)

```
  ____            _                                          
  |  _ \ ___   ___| | __                                      
  | |_) / _ \ / __| |/ /                                      
  |  _ < (_) | (__|   < _                                     
  |_| \_\___/ \___|_|\_( )                                    
               |  _ \ _|/_ _ __   ___ _ __                    
               | |_) / _` | '_ \ / _ \ '__|                   
               |  __/ (_| | |_) |  __/ |_                     
               |_|   \__,_| .__/ \___|_( )                    
                        __|_|      _   |/                   _
                       / ___|  ___(_)___ ___  ___  _ __ ___| |
                       \___ \ / __| / __/ __|/ _ \| '__/ __| |
                        ___) | (__| \__ \__ \ (_) | |  \__ \_|
                       |____/ \___|_|___/___/\___/|_|  |___(_)

? Which do you choose? Rock
You chose rock.
The computer chose scissors.
Rock beats scissors.  You win!
```
--

 ```
   ____            _                                          
  |  _ \ ___   ___| | __                                      
  | |_) / _ \ / __| |/ /                                      
  |  _ < (_) | (__|   < _                                     
  |_| \_\___/ \___|_|\_( )                                    
               |  _ \ _|/_ _ __   ___ _ __                    
               | |_) / _` | '_ \ / _ \ '__|                   
               |  __/ (_| | |_) |  __/ |_                     
               |_|   \__,_| .__/ \___|_( )                    
                        __|_|      _   |/                   _
                       / ___|  ___(_)___ ___  ___  _ __ ___| |
                       \___ \ / __| / __/ __|/ _ \| '__/ __| |
                        ___) | (__| \__ \__ \ (_) | |  \__ \_|
                       |____/ \___|_|___/___/\___/|_|  |___(_)

? Which do you choose? Paper
You chose paper.
The computer chose scissors.
Scissors beats paper.  You lose.
```

--

 ```
   ____            _                                          
  |  _ \ ___   ___| | __                                      
  | |_) / _ \ / __| |/ /                                      
  |  _ < (_) | (__|   < _                                     
  |_| \_\___/ \___|_|\_( )                                    
               |  _ \ _|/_ _ __   ___ _ __                    
               | |_) / _` | '_ \ / _ \ '__|                   
               |  __/ (_| | |_) |  __/ |_                     
               |_|   \__,_| .__/ \___|_( )                    
                        __|_|      _   |/                   _
                       / ___|  ___(_)___ ___  ___  _ __ ___| |
                       \___ \ / __| / __/ __|/ _ \| '__/ __| |
                        ___) | (__| \__ \__ \ (_) | |  \__ \_|
                       |____/ \___|_|___/___/\___/|_|  |___(_)

? Which do you choose? Paper
You chose paper.
The computer chose paper.
You tied.
```
