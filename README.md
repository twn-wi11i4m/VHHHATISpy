# VHHH ATIS

## Overview

This Python script allows you to fetch the Automatic Terminal Information Service (ATIS) data for Hong Kong International Airport (VHHH) from the official ATIS webpage (http://www.hkatis.com/atis/atis.php). ATIS provides important information to pilots and air traffic controllers, including meteorological data, runway conditions, and other essential details for safe flight operations.

## Requirements

- Python 3.7 or above
- Required libraries: `requests`, `BeautifulSoup`

## Usage

1. Clone or download this repository to your local machine.

2. Install the required Python libraries if you haven't already:

   ```bash
   pip install requests beautifulsoup4

## Supplementary
(This section is from AIP Hong Kong, updated at 2024-05-27)
### Aeronautical Broadcasting Service
3.3.1 b) VHF Automatic Terminal Information Service (ATIS) broadcasts information on H24 basis:

|                        |            |
|------------------------|------------|
| For arriving aircraft  | 128.20 MHZ |
| For departing aircraft | 127.05 MHZ |

### ATS Data Link Service
3.4.1 a) Data Link Automatic Terminal Information Service (D-ATIS);

|                        |            |
|------------------------|------------|
| For arriving aircraft  | code VHHHA |
| For departing aircraft | code VHHHD |

### Other Information Services
3.5.1 Automatic Terminal Information Service (ATIS) broadcast are available H24 via the following telephone hotlines:

|                |                |
|----------------|----------------|
| Arrival ATIS   | +852 3141 2820 |
| Departure ATIS | +852 3141 2705 |


## Disclaimer

Please ensure that you comply with the terms of use and guidelines provided by the Hong Kong ATIS website when accessing and using their data. This script is for educational and informational purposes only.

## License

This script is provided under the MIT License.

Support me via [🛢️Buy Me some AVGAS](https://www.buymeacoffee.com/Williamntw) !
