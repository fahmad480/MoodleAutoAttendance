# Moodle Class Auto Attendance

This bot will help you to skip from your daily class, this bot always help you to fill your attendance list


## Requirements

- Google Chrome v86 ( You can use another webdriver like Firefox )
- Python 3.6
- Moodle account

## Install

- Clone first this git

```cmd
git clone https://github.com/zFz0000/MoodleAutoAttendance.git
```

- Access the folder

```cmd
cd MoodleAutoAttendance
```

- Install the requirements

```cmd
pip install -r requirements.txt
```

- Change your Moodle URL, username and password in ```CREDS``` variabel inside ```attendance.py```

```python
URL = "YOUR MOODLE URL ( ENDED WITH /MY )"

CREDS = {'username' : 'YOUR_MOODLE_USERNAME','passwd':'YOUR_MOODLE_PASSWORD'}
```

- Start the bot

```cmd
python attendance.py
```

## Inspired By
[@teja156](https://github.com/teja156/microsoft-teams-class-attender)


## License

[MIT](https://choosealicense.com/licenses/mit/)
