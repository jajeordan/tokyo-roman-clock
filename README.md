# Tokyo Analog Clock

An analog clock application built with Python and Pygame that displays the current time in Tokyo. The clock features Roman numerals, three clock hands (hours, minutes, and seconds), and an AM/PM indicator.

## Features

- Real-time Tokyo time display
- Roman numeral clock face
- Hour, minute, and second hands
- AM/PM indicator
- Clean, classical design

## Requirements

- Python 3.x
- pygame
- pytz

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR-USERNAME/tokyo-analog-clock.git
```

2. Navigate to the project directory:
```bash
cd tokyo-analog-clock
```

3. Install required packages:
```bash
pip install pygame pytz
```

## Usage

Run the clock:
```bash
python tokyo_clock.py
```

- The clock will automatically display the current Tokyo time
- The window can be closed by clicking the close button
- The display updates every second

## Project Structure

```
tokyo-analog-clock/
│
├── tokyo_clock.py    # Main clock application
└── README.md        # Documentation
```

## Technical Details

The clock implements:
- Time zone conversion using pytz
- Graphics rendering with Pygame
- Trigonometric calculations for hand positions
- Real-time updates

## Learning Outcomes

Through this project, I practiced:
- Working with Python libraries (Pygame, pytz)
- Handling time zones and datetime operations
- Basic computer graphics and geometry
- Real-time application development
- User interface design

## Future Improvements

Potential features to add:
- Multiple time zones
- Custom themes
- Digital time display option
- Alarm functionality
- Resizable window

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to fork this project and submit pull requests with improvements!
