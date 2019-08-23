# GSoC 2019 project, Icons Picker and Custom font generator

## Description
In most of the cases around 80% of icons in an iconic font are unused. This reduces the performance of a web page unnecessarily. This project aims to solve that problem by allowing users to Select icons and generate custom font from them. Recurrent users can also import the Icons configuration file to continue building the same font from where they left.

## Code

### API Back-end:
Made an API using NodeJS and Express that generates cutom font using `grunt` from the List of icons (EOS Set, Extended version, animated icons) in the API request JSON.

Repository: https://gitlab.com/SUSE-UIUX/eos-icon-picker

My contributions: https://gitlab.com/SUSE-UIUX/eos-icon-picker/merge_requests?scope=all&utf8=%E2%9C%93&state=merged&author_username=kbhutani0001


### Front-end:
Made front end to allow users to select icons and Generate custom font. Also allows user to continue building a previous font by importing a `config.json` file.

Repository: https://gitlab.com/SUSE-UIUX/eos-icons-landing

My contributions: https://gitlab.com/SUSE-UIUX/eos-icons-landing/merge_requests?scope=all&utf8=%E2%9C%93&state=merged&author_username=kbhutani0001

Website hosted at: https://eos-icons.eosdesignsystem.com/extended/icons-picker.html