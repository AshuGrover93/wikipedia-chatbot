# wikipedia-chatbot
The chatbot helps you in getting info related to the desired topic.

## Introduction
The python program will scrape data from wikipedia related to a topic and store it in a local corpus. Then will provide related information on asking queries using the corpus data.

## Python Libraries required:
```python
nltk
sklearn
wikipedia
```


## Example:
Run the code:

![1](https://user-images.githubusercontent.com/44069711/58540119-56e12d80-8216-11e9-8a5e-e5d10ecc7517.PNG)

Then enter the person/thing/organisation etc. you want the data to be fetched for. I enter 'Sachin Tendulkar', the cricketer for instance.
Then the data for him wil be scrapped from wikipedia and stored locally.

![2](https://user-images.githubusercontent.com/44069711/58540109-55176a00-8216-11e9-8320-de4aa679d7d4.PNG)


Data fetching takes a few seconds and when it is fetched you are prompted for input queries related to the subject entered. As one can see in the screenshots below.

![3](https://user-images.githubusercontent.com/44069711/58540112-56489700-8216-11e9-995b-bcd31a45b5bb.PNG)
![4](https://user-images.githubusercontent.com/44069711/58540114-56489700-8216-11e9-90dc-05fd37ab5578.PNG)

When related data is not available in the locally stored corpus, you get an error message. For instance here Sachin and hollywood have no correlation.

![5](https://user-images.githubusercontent.com/44069711/58540115-56e12d80-8216-11e9-9506-aafe4e7268cc.PNG)


Lastly, a 'bye' will exit the program.

![6](https://user-images.githubusercontent.com/44069711/58540118-56e12d80-8216-11e9-8e99-e83a6e7c6f55.PNG)



Thanks. Inputs for the same are welcome.


## License
[MIT](https://choosealicense.com/licenses/mit/)
