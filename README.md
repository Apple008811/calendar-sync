# Calendar Sync

A tool to sync events from multiple networking platforms (Eventbrite, Meetup, etc.) to iCalendar.

## Features

- Scrape event information from multiple websites (currently supports Eventbrite and Meetup)
- Convert event information to iCalendar format
- Generate .ics files that can be directly imported into calendar applications

## Installation

1. Make sure you have Python 3.7 or higher installed
2. Clone this repository:
```bash
git clone https://github.com/Apple008811/calendar-sync.git
cd calendar-sync
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the program:
```bash
python calendar_sync.py
```

2. The program will generate an `events.ics` file
3. Import the generated .ics file into your calendar application (e.g., Apple Calendar, Google Calendar)

## Supported Platforms

- Eventbrite
- Meetup

## Development Status

- Basic event information sync (title, time, location, description) is supported
- More features are under development

## Contributing

Feel free to open issues or submit pull requests to help improve this tool.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 