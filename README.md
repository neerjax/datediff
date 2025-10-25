# Date Difference Calculator

A simple, elegant utility to calculate the number of days between two dates, with a breakdown of weekdays and weekend days.

## Features

- Calculate total days between two dates
- Separate counts for weekdays (Monday-Friday)
- Separate counts for weekend days (Saturday-Sunday)
- Clean, modern user interface
- Responsive design
- Real-time validation

## Usage

1. Open `index.html` in any web browser
2. Select a start date
3. Select an end date
4. Click "Calculate Difference" or press Enter
5. View the results showing:
   - Total days between the dates (inclusive)
   - Number of weekdays
   - Number of weekend days

## How It Works

The calculator counts all days inclusively from the start date to the end date, including both boundary dates. It then categorizes each day as either:

- **Weekday**: Monday through Friday
- **Weekend**: Saturday and Sunday

## Technical Details

- Pure HTML/CSS/JavaScript (no dependencies)
- Works offline
- Compatible with all modern browsers
- Mobile-friendly responsive design

## Example

If you select:
- Start Date: January 1, 2025 (Wednesday)
- End Date: January 7, 2025 (Tuesday)

The result will show:
- Total Days: 7
- Weekdays: 5 (Wed, Thu, Fri, Mon, Tue)
- Weekend: 2 (Sat, Sun)
