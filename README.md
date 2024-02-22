# Roblox Studio Discovery Workshop (Part 1)


## | Prerequisites |

- [Roblox Studio](https://roblox.com)
- [Flathub](https://flathub.org/setup/Ubuntu) (if you're on linux)
- [Vinegar](https://flathub.org/apps/org.vinegarhq.Vinegar) (if you're on linux)


## | Starting |

First, create a new project (baseplate)
![roblox studio main menu](image.png)

Once you created your project, your first step will be to save it, give it a name and make sure team create is turned on.

### New world, new buildings, learn how to place a Part!
Your first goal is to place a part in the workspace, and set its size to (3, 3, 3), and make sure it's anchored.

### New world, new rules, make your first script!
Usually, developers start with making a print("hello world") script, but if you noticed, making a new script in roblox studio just does that by default! <br>
Erase that line, and start making your own script! <br>
Your goal: making the part invisible after 10 seconds. (You can ask questions, but your most useful ressource will be the [documentation](https://create.roblox.com/docs/fr-fr/reference/engine)!

### New world, new design, discover the beauty of a good UI!
Now comes the design part! You must design your very first UI!
Figure out how to make a round circle in the middle of your screen.

### New world!
Congratulations, you discovered all the key elements to make an inventory system! The final boss of this workshop will be to make a functionning inventory system, but, don't worry, I'm never gonna let you down!

#### What's a server, what's a client, and how to communicate???
In Roblox Studio, there are 3 important concepts to remember:
- Client Sided
    - Everything that is happening on your machine, that only you can see.
- Server Sided
    - Everything that is happening on the server, that everyone can see.

- Replicated
    - Replicated elements are elements played by every clients.

To make your inventory system, every single of these concepts will need to be understood.

Make a localscript in "StarterPlayerCharacter" and make it send a message to a script in "ServerScriptService" using a RemoteEvent stored in "ReplicatedStorage"

<br>
Great! you made it through the hardest part!
<br>
Now you have all the keys needed to make your own inventory system, so glhf! (Don't hesitate to ask questions if you're struggling, I may provide some useful tips who knows?)


## | Useful links |
<li> https://create.roblox.com/docs/fr-fr/reference/engine </li>
<li> https://devforum.roblox.com/ </li>
