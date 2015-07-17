# IC.Social - Implementing a Twitter feed in Python
This code is from the original blog post from https://www.informaticscentre.co.uk/blog/implementing-a-twitter-feed-in-python that we published in 2013. This source code is compatible with Python 2.7+.

## Prerequisites 
1. Python 2.7+
2. Setup your application with Twitter's Developer API (https://dev.twitter.com/docs/auth/tokens-devtwittercom)
3. pip (https://pip.pypa.io/en/latest/installing.html)
4. oauth2 (```pip install oauth2```)

## How to use
You will need to modify the **start.py** file to include your own Twitter Application details. 
```python
consumerKey = ''
consumerSecret = ''
apiKey = ''
apiSecret = ''
```
Change the hash tag ```#informatictips``` in **start.py** to something of your choice.
```python
 tweets = twitterRepository.GetTweetsFromUnblockedUsers('#informaticstips', 20)
```

Start the application from your command line.
```
python start.py
```

## Optional
You may require PIL (Python Imaging Library) to display a background image on the canvas if your installation of Python does not include it. You can obtain it for your OS from http://www.pythonware.com/products/pil/.

## Python 3
We have updated the source code to be compatible with Python 3, you can find the blog post at https://www.informaticscentre.co.uk/blog/updating-the-twitter-feed-for-python-3 and the Python 3 Repository at https://github.com/informaticscentre/IC.Social.Python3.
