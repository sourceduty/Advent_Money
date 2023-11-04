## Advent_Money

🪙 Software concept for revealing a digital money gift on Christmas day.

![Ad_1](https://github.com/sourceduty/Advent_Money/assets/123030236/2ebd2f50-aae9-473e-9e76-f044e9ea0873)


### CONCEPT

A digital Christmas advent money gift notification service. When customers buy the calendar gift, an email receipt is sent to both the customer and the gift receiver. Each of the 25 money gifts are revealed through SMS and email messages and notifications. All 25 money gifts are accumulated and released as one payment gift on Christmas day.

```
import datetime

# Assuming the gift amount is securely stored and retrieved
GIFT_AMOUNT = '100.00'

# Get the current date
current_date = datetime.date.today()

# Check if today is Christmas
def reveal_gift():
    if current_date == datetime.date(current_date.year, 12, 25):
        print(f'Merry Christmas! 🎄 You have received a digital money gift of ${GIFT_AMOUNT}!')
    else:
        print('The gift will be revealed on Christmas Day!')

# Run the gift reveal function
reveal_gift()
```

This script will check the current date, and if it's December 25th, it will print a message revealing the digital money gift. 

If it's not Christmas Day, it will inform the user to wait until Christmas to reveal the gift. 
