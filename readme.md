# CSVtoICSconverter

## Requirements

You need the followin to be able to run this code:

* Python >= 2.7
* icalendar >= 5.0.5 (`pip install icalendar`)

## Usage

First install the script and it's requirements:

```
git clone https://github.com/fricker12/CSVtoICSconverter
cd CSVtoICSconverter
pip install requirements.txt
```
Then run the script as follows:
```
python converter.py birthday.csv birthday.ics
```

A file called `birthday.ics` will be generated, which you can import into your calendar application.