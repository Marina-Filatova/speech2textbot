# speech2textbot
## Setup
### 1. Install ffmpeg on the device
**If you are using Windows 10/11**

Step 1. Download the latest version of ffmpeg for Windows from this [link](https://www.ffmpeg.org/).

Step 2. Rename the extracted folder to ffmpeg and move it into the root of C: drive.

Step 3. Run cmd as an administrator and set the environment path variable for ffmpeg by running the following command:

`setx /m PATH "C:\ffmpeg\bin;%PATH%"`

Step 4. Restart your computer and verify the installation by running:

`ffmpeg -version`

Step 5. Done, you're great

**If you are using Windows Linux**

Step 1. Use the command:

`sudo apt install ffmpeg`

Step 2. Check the installation success:


`ffmpeg -version`

Step 3. Done, you're great!
### 2. Create a virtual environment with Python 3.12.2<

Step 1. Launch venv

First comes the general command for all operating systems:

`python3.12 -m venv venv`

Step 2. Activate the virtual environment

**If you are using Windows 10/11**

`venv\Scripts\activate.bat`

**If you are using Linux**

`source venv/bin/activate`

Step 3. Done, you're great!!

If everything is done correctly, the following entry will be displayed:

`(venv) root@purplegate:/var/test#`
### 3.Now you can start working directly with the bot
Step 1. Install dependencies:

`pip install -r requirements.txt`

Step 2. Launch the bot:

`python whisper-bot.py`

Step 3. Done, you're great!!!
## Technical requirements:
- Windows 10/11 or Linux OS
- Minimum amount of RAM - 8
- Minimum disk space: 20 GB
- Minimum number of processor cores: 2
- Processor Intel Cascade Lake processor (Intel Xeon Gen2) and above
- Python 3.12
