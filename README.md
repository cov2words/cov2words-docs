# COV2WORDS

## Introduction

To provide the hotline, Amazon Connect is used as a scalable customer center solution. On this basis, a chatbot was programmed, which interacts with the user via voice or text input. Amazon Lex and AWS Lambda are used for speech recognition and validation. The current goal is to provide an interface where each hospital can create its decision tree. However, this interface will probably not be realized by us. In addition to our hotline solution, there is already an app and a webpage solution, which will be implemented this week. We only share some medical history based on 30 chatbot question, the hospital interprets it and can give their recommendation.

Simple word pairs - to be used as analog QR-code

The response possibilities amount to approximately 300 million combinations. To encode them in a user-friendly way, each combination is mapped to a word pair from the dictionary. The customer has verbally conveyed the word pair together with the recommendation after the survey. He can memorize it or note this word pair and share it with a doctor. A further service developed with Ionic and provided as an app can be used by health care personnel to generate and view the corresponding medical history from the word pair. Furthermore, a QR code is also created for which a procedure for integration into the hospital information system already exists.

## Full Documentation
See the [Wiki](https://github.com/cov2words/cov2words-docs/wiki) for full documentation, examples, configuration details and other information.

See Rest API documentation [here](http://api.cov2words.com/swagger-ui.html).

## Communication
mail@cov2words.com

cov2words.slack.com
