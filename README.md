# Telegram Dialogs Data Analysis: Step-by-Step Guide
How to complete an interesting project with just basic knowledge of Python and pandas.<br>
Used helpful repositories [telegram-data-collection](https://github.com/SanGreel/telegram-data-collection) and [telegram-dialogs-analysis-v2](https://github.com/SanGreel/telegram-dialogs-analysis-v2).

## How can this project help on your path?
*Consists of three steps to download and use your dialogs data from telegram app.<br> 
Gives big amount of data to scrutinize on and ideas for your data exploration!<br>
Boosts creativity and interest.*

### Requirements
Python 3.8.13 - highly recommended. <br>
Basic knowledge of Python and its pandas library.

## How to use?

### 0. Clone this Repository to your local device
Future ```data``` folder should be placed inside base folder.

### 1. Download Data from Telegram
*Downloading is going to take a lot of time in most cases.*<br>
Use guides from ***[telegram-data-collection repository](https://github.com/SanGreel/telegram-data-collection)*** developed by Andrew Kurochkin aka [SanGreel](https://github.com/SanGreel) for stability and speed. <br>

Also, as a second option, there is ***[telegram-data-collection repository](https://github.com/Artem-on-ishche/telegram-data-collection)*** developed by Artem Mykytyshyn aka [Artem-on-ishche](https://github.com/Artem-on-ishche).<br> 
Basically, it is somehow improved fork of previously mentioned repository. Some useful additions: skipping certain types of dialogs while downloading, keeping reaction to messages; disadvantage: slower than original.

### 2. Merge and Preview Data
Compile and prepare your data for easier use later on. <br>
Furthermore, take first steps into its analysis.<br>

Go to ```data-preparing-and-preview``` folder. Merge data by running all cells in ```0_merge_data.ipynb``` (through anaconda - jupyter notebook as a variant). <br>
Make a quick look through your data by running ```1_data_review.ipynb```.<br>
For more info read quide in [telegram-dialogs-analysis-v2](https://github.com/SanGreel/telegram-dialogs-analysis-v2) repository from [SanGreel(https://github.com/SanGreel).


### 3. Analyze Data
To view my ideas and process: run ```my-data-analysis/behaviour_patterns_exploration.ipynb``` file.<br>
Modify code as you like to perform your own deep data analysis)
