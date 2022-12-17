# Colorless Green

> An algorithm that produces sentences according to a randomly generated sentence structure populated by randomly picked words from a dictionary.

## Usage

This code has been hosted on AWS Lambda and you may make calls to it using the following link: [API Gateway](https://2tcsy75xbl.execute-api.us-east-1.amazonaws.com/default/colorlessGreen)

The API accepts two parameters

- Characters

  Accepts a comma-separated list of characters to involve in the story.
  
  An example call with this parameter could be [`https://2tcsy75xbl.execute-api.us-east-1.amazonaws.com/default/colorlessGreen?characters=Will,John,Anne`](https://2tcsy75xbl.execute-api.us-east-1.amazonaws.com/default/colorlessGreen?characters=Will,John,Anne)
  
 - Length
 
    Accepts an integer-value length that specifies the number of sentences to produce.
    
    An example call with this parameter could be [`https://2tcsy75xbl.execute-api.us-east-1.amazonaws.com/default/colorlessGreen?length=3`](https://2tcsy75xbl.execute-api.us-east-1.amazonaws.com/default/colorlessGreen?length=3)
