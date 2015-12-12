# Consumables

Provides functionality for consumables goods and running costs, such as car fuel and electricity/gas/water bills.

## Supported fields
- Price
- Date
- Units (ie. liters, used for stats)
- Landmark (ie. car mileage, used for stats)
- Notes

## Usage

`$ docker run -p <port>:10101 -d giorgioaresu/consumables`

where `<port>` is the port you want to bind to.

#### Build the container yourself 

`$ docker build -t $(whoami)/consumables .`