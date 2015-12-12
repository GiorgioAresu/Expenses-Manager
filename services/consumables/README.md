# Consumables

Provides functionality for consumables goods and running costs, such as car fuel and electricity/gas/water bills.

## Supported fields
- Price
- Date
- Units (ie. liters, used for stats)
- Landmark (ie. car mileage, used for stats)
- Notes

## Usage

#### Build docker image 

`docker build -t giorgioaresu/consumables .`

#### Run the image

`docker run -p <port>:10101 -d giorgioaresu/consumables`

where `<port>` is the port you want to bind to