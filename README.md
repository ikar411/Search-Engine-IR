# Domain Specific Information Retrieval System
## Assignment-1 CS F469 IR

### :busts_in_silhouette: The Team
* Raaed Ahmed Syed
* Ritika Reddy
* Anvitha Nallan
* Anurag Sidharth Aribandi

### :cd: Dataset
* A collection of all the conversations that occurred over 10 seasons of **Friends, a popular American TV sitcom** that ran in the 1990s. 

* Across the 10 seasons there are *236 episodes, 3,107 scenes (conversations), 67,373 utterances, and 700 characters (users).* 

* The available *metadata* varies by seasons, but can include: character entities, emotion, a tokenized version of the text, caption information, and notes about the transcript.

### :key: Run the Code
* Save file as IR_1.py
* Open terminal in the directory containing the python program and run the command python IR_1.py
* When prompted enter a partial or full dialogue from the TV show Friends. Include unique words and character names for better results.
* Choose a method to compute term frequency from the given options by typing in the option number.
* For documentation enter command >>>python -m pydoc IR_1 after entering the directory where the file is saved
  
### :books: Libraries Used
* Numpys
* Pandas
* NTLK

### :star: Output
* Top 10 scenes where the query dialogue is similar to a transcript in the scene.
* Format: Season-Number_Episode-Number_Scene-Number (Ex: s09_e05_c23)
* The score is also displayed next to the Scene data based on the option the user chose initially.

