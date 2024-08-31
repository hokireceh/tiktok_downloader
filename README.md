# Tiktok Downloader

Source code for Telegram bot which functions to download TikTok videos without watermark.<br/>
This source code is not downloaded directly from TikTok but uses a third party.

# How to run on your local machine

1. Install python 3.8+
   You can download from official python website : https://python.org. <br />
   If you use Linux, you can directly install Python with the command
   ```bash
   sudo apt install python3 python3-pip -y
   ```
2. Clone or download this repository
   ```bash
   git clone https://github.com/hokireceh/tiktok_downloader.git
   ```
3. Goto TiktokDownloader folder<br/>
   ```powershell
   cd tiktok_downloader
   ```
4. Install required libraries <br />
   ```bash
   python -m pip install -r requirements.txt
   ```
   or
   ```bash
   python3 -m pip install -r requirements.txt
   ```
5. Copy .env.example into .env
   ```powershell
   cp .env.example .env
   ```
   or
   ```
   copy .env.example .env
   ```
6. Open .env in your code editor or something like that
7. Create Telegram token bot in Bot Father : https://t.me/BotFather
8. Copy and paste the token from bot father into .env
   ```env
   token_bot = "token_botxxxxxxxxx"
   ```
9. Create Api Hash and Api Id. You can create from https://my.telegram.org
10. Copy and paste Api Hash and Api Id into .env file
    ```env
    api_id = "123123"
    api_hash = "qwerertyiuo"
    ```
11. Finally, type the command below to run the program
    ```bash
    python main.py
    ```
    or
    ```bash
    python3 main.py
    ```
**if you want to run program 24/7, you can to run this program in linux server with using screen program**

Install screen
```bash
sudo apt install screen -y
```
Create session
```bash
screen -R <session name>
example : screen -R tiktok
```
Run the program 
```bash
python3 main.py
```
Save the session using keyboard shortcut **ctrl + a + d**

Done
# Follow me
* https://facebook.com/hokireceh.official
* https://instagram.com/hokireceh <br />
  *You can contact me with social media in above*
# Support me

* (Indonesia) 
* (Global/International) https://sociabuzz.com/vania_gemash/tribe
* Ton ```UQBOGHJAp7EXL5WgAw3E2wfOF7HBapd8YyQxU6wa7V1WZD6N```
* Dogs ```UQBOGHJAp7EXL5WgAw3E2wfOF7HBapd8YyQxU6wa7V1WZD6N```
* TRON / USDT (Tron20) ```TChYgcKG6zRwz5FP9UTZrAik3xDPa12M94```
