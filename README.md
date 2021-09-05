# DwightBot
 A simple conversational DialoGPT-small model of Dwight from The Office
 
 * The data for this was collected from [foreverdreaming](https://transcripts.foreverdreaming.org/viewforum.php?f=574).  

* The scraper plus data can be found at [The-Office-Transcripts](https://github.com/XxTyaftioNxX/The-Office-Transcripts)

* The model can be re-used to create conversational bots of similar capabilities (depending on the number of dialouges) of other cast of The Office as well. For which you can just change the vairable *CHARACTER_NAME* to your preffered cast member. (Find out character names that align with the dataset used for examlpe; *Michael Scott* in the series is *Michael* in the dataset :D)

* The model was created using Google Colab and uploaded to HuggingFace and can be found  @[HypNyx/DialoGPT-small-DwightBot](https://huggingface.co/HypNyx/DialoGPT-small-DwightBot?text=Hey+my+name+is+Julien%21+How+are+you%3F)

* The Model was linked to Discord using repl.it (files in the same directory).

* [DwightSchruteBot](https://discord.com/oauth2/authorize?client_id=884187830870482984&permissions=0&scope=bot) can be added to your server, although the repl needs to be running for the Bot to be active on the server. 

* The bot runs at HuggingFace server if you want to try it out (P.S. super laggy adn might run into errors)

**TL;DR** 
* This Model has perplexity of tensor(6.14) and context_window of 6. The perplexity decreases with the number of epochs but there is no significance improvement in conversation and higher context_window sizes just requires larger training time and seems to make the model more confused.
* I would recommend trying out microsoft/DialoGPT-medium and training the model with more epochs if you have processing power at your expense. (P.S. i havent tried the medium model) 
