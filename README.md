# unicatter

# skill-capped-lol-link-parser

**Deprecated**

This project parses links from https://better-skill-capped.com/ and returns them in the IDE.
After parsing links, you can set up VLC or another Media player to play them.

Unfortunately it will output also other links, such as the creator's github, etc.
You will need to clean it up yourself until I fix it, sorry.


**Dependencies**: Selenium, Webdriver


**Usage**:
Install selenium with
> pip install selenium
 
 
Install the Webdriver for the browser you use:
> https://www.selenium.dev/documentation/en/webdriver/driver_requirements/

Run the .py with your favorite IDE.


You can choose to either:
- Parse the links to the actual videos
- Parse the links to the m3u8 files, which can be downloaded and readily played in VLC (given that you have a working internet connection, are logged in and subscribed to SKillcapped).


To clean up the links (until I fix this), you can use Sublime Text (https://www.sublimetext.com/) or other text editors to delete all lines containing "github", "4500.m3u", etc.
If you're not sure how, check over here! https://stackoverflow.com/questions/25253519/sublime-delete-all-lines-containing-specific-value


**To-do list**
- Automate the cleaning up of the links
- Set a way to check the boxes for different roles, categories of videos, etc.
- Make a downloader for the links parsed.
- No need to install dependencies


**Special thanks to**
https://www.skill-capped.com/
https://better-skill-capped.com/
