# Reddit Word Cloud bot

[![forthebadge](http://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)

This script is written to make a word cloud from different subs. It looks through the top posts and collects the top comments and creates a dataframe, which it uses to clean with Pandas and nltk. Then it creates wordcloud from there.
# Table of contents

- [Installation](#installation)
- [Recommended configurations](#recommended-configurations)
- [License](#license)


# Installation

[(Back to top)](#table-of-contents)

1. Install Python (preferably, version >= 3.7)
2. Install a pip3
    ```bash
    $ sudo apt install python3-pip -y
    $ pip install -r requirements.txt
    ```

3. Edit the sub list with your preferred sub names :
    ```bash
    subreddits = ["dnd"]
    ```

4. Set your credentials of Reddit API; API creds can be obtained from [Reddit API](https://www.reddit.com/prefs/apps)
5. Run the python script:
    ```bash
    $ python main.py
    ```

6. Wait for the code to complete running and build your word cloud image.

# Recommended configurations in script

[(Back to top)](#table-of-contents)
feel free to set custom configs
1. Set top posts limit :
    ```sh
    top = subreddit.top(limit=1000)
    ```

2. Set credentails from 

    ```sh
    client_id="",
    client_secret="",
    password="",
    requestor_kwargs={"session": session},
    user_agent="ChangeMeClient/0.1 by YourUsername",
    username="",
    ```

# License

[(Back to top)](#table-of-contents)


The MIT License (MIT) 2017.