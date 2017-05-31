# ParseChats
This project will be used to build a parser to parse chat messages written using English alphabets for non-english language.

Country like India people use English words frequently when then converse. This prompts them to write words from Indian language even using English alphabets. 
This creates a problem for the language parsers used to parse these chat messages as they cannot match the words in the standatd English dictionary

This is a righ source of information, if companies mine these texts/messages then they will better understand the consumer demand. Friends more often than not they will converse in their native language. They will exchange views and opinions in their native language. However they fallback to English alphabets during the conversation. This is easy as most of us have grown up using English keyboards. We are fast typing using English keyboards.

for example : Ami kaal akta Chinese resturant e kheye chilam, bhalo chilo na. Khub bhir chilo kintu khabar ta taratari enechilo. / I had food in a Chinese Resturant yesterday, the resturant was not good. 
It was very crowded but still they managed to bring the order quickly.
In the above conversation one of the person is narrating his/her experience with the Resturant. The issue is words like Ami/I kaal/yesterday is not available in dictionaries as the dilect is embedded in these words, 
for example kaal/kal sounds similar phonetically. Hence these variations are huge. Similar is the case with other Indian Languages.    

The approach I would take is to split the sentence based on word boundaries, and then  learn from the proximity. This will be used to create a graph and identify dependencies. The occurances will decide whether there is correlation strong or weak between words. Since, the problem domain is phonetic words written using english alphabets I feel word stems can be derived. The next problem to olve is to identify the real intent of the sentence. If we analyse the above sentence it is quite ambiguous whether the conversation is anout the food quality or the overall quality of the Resturant. Based on the context as I speak Bengali myself I am quite confident the conversations is abot food. Bengali's are food lovers. However this contextualisation may not be correct for other parts of India. 

-------->>>>> Add the appoach

AT THIS POINT I AM CREATING A PROTOTYPE..........

There are fillers in the sentence, or rather noise which needs to be removed. 

My intention of creating this project is an attempt to solve this problem.


