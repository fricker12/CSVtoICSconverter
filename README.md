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

# Windows Setting to enable unicode

![Use this]
(https://github.com/fricker12/CSVtoICSconverter/blob/39a476736369666b66482bc33411386ac340f31d/windows%20settings%20enanle%20unicode/1.jpg)
(https://github.com/fricker12/CSVtoICSconverter/blob/39a476736369666b66482bc33411386ac340f31d/windows%20settings%20enanle%20unicode/2.jpg)
(https://github.com/fricker12/CSVtoICSconverter/blob/39a476736369666b66482bc33411386ac340f31d/windows%20settings%20enanle%20unicode/3.jpg)

Then run the script as follows:
```
python converter.py birthday.csv birthday.ics
```

A file called `birthday.ics` will be generated, which you can import into your calendar application.