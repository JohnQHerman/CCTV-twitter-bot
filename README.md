# Unsecured CCTV Cameras Bot

A Python bot that scrapes random unsecured CCTV cameras and posts them to a Twitter account.

You can see the bot in action [here on its Twitter page](https://twitter.com/Unsecured_CCTV)

<img src="https://user-images.githubusercontent.com/95893344/229968711-b8198a32-d031-4f5b-acc3-d69823556f51.png" alt="West Des Moines, Iowa" width="400"/> <img src="https://user-images.githubusercontent.com/95893344/229968930-2830ccb5-4cf6-493a-83d8-037cd353add0.png" alt="Olomouc, Czech Republic" width="400"/>

## 🚀 Usage

1. Clone this repository to your local machine.
2. Run `pip install -r requirements.txt` to install the necessary dependencies.
3. Set up a Twitter Developer account and obtain the necessary API credentials. You can find a guide [here](https://developer.twitter.com/en/docs/basics/authentication/guides/access-tokens.html).
4. Create a `credentials.csv` file in the root directory of the project and add your API credentials in the following format:

   ```
   CONSUMER_KEY,CONSUMER_SECRET,ACCESS_TOKEN,ACCESS_TOKEN_SECRET
   ```

5. Launch the bot by running `python twitterbot.py`.

## 🙌 Credits

This project was developed by John Q. Herman [(sharkobarko)](https://twitter.com/sharkobarko) under the [MIT](https://choosealicense.com/licenses/mit/) license, with camera feeds sourced from [Insecam.org](http://www.insecam.org/static/sitemap.xml)
