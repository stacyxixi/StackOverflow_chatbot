# Chatbot project

This folder contains the code for the chatbot project.

## Instruction
Train the bot with the ipython notebook to generate pickle files. Then run
Python3 /path/main_bot.py --token="your token obtained from Telgram Messenger @BotFather"

## Dependencies
Docker container: akashin/coursera-aml-nlp

## Troubleshooting

### Bot crashes with the unicode error 

If your bot code crashes with the error that ends with `UnicodeEncodeError: 'ascii' codec can't encode character`,
your terminal likely has problems showing unicode symbols. To fix this you can change your terminal local by adding
the following lines to you `~/.bashrc` file (or any other shell configuration):

```
export LC_ALL=en_US.UTF-8
export LANG=en_US.UTF-8
export LANGUAGE=en_US.UTF-8
```

You can find more details in this [article](https://perlgeek.de/en/article/set-up-a-clean-utf8-environment).
