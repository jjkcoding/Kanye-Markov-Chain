# Kanye-Markov-Chain

One of my statistics professors mentioned that Markov Chains could be used to identify key phrases and help translate an unknown language. To further help us understand this concept of first and second order Markov Chains and n-grams, I created three different models of randomly generated scripts based on Kanye's song lyrics. 

## Models: 
1)  The first model is an independent and identically distributed (iid) random sample based on Kanye's lyrics. 
2) The second model uses a first order Markov Chain based on the latest generated word and Kanye's lyrics. It would do an iid based on each word that follows the latest generated word in Kanye's original lyrics. 
3) The third model would do the same thing as the second model, but the script would be based on a second order Markov Chain. It would use both the latest generated word and the word before that to view all the following words in Kanye's original lyrics to do an iid random sample.

## Would any of these models create a script similar to Kanye's original lyrics?
No, all the models did not create anything as amazing as Kanye's lyrics. However, the first and second order Markov Chain based models did create somewhat of a similar version to Kanye's original script.
