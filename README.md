# Malaysia Postcodes

A Comprehensive List of Malaysia Postcodes, Complete with City and State Information, available in JSON format.

## Overview

This repository provides an extensive collection of Malaysia postcodes, indexed by city and state. It serves as a useful resource for developers, researchers, and anyone interested in postal data for Malaysia.

## Data Structure

The data is structured in JSON, and the format is as follows:

```json
{
   "name": "Kelantan",
   "city": [
       {
        "name": "Pasir Mas",
        "postcode": [
            "17000",
            "17007",
            "17009",
            "17010",
            "17020",
            "17030",
            "17040",
            "17050",
            "17060",
            "17070"
        ]
       }
   ]
}
```

## Table of Contents

- [All Postcodes](all.json)
- [Johor](johor.json)
- [Kedah](kedah.json)
- [Kelantan](kelantan.json)
- [Kuala Lumpur](kuala_lumpur.json)
- [Labuan](labuan.json)
- [Melaka](melaka.json)
- [Negeri Sembilan](negeri_sembilan.json)
- [Pahang](pahang.json)
- [Pulau Pinang](pulau_pinang.json)
- [Perak](perak.json)
- [Perlis](perlis.json)
- [Putrajaya](putrajaya.json)
- [Sabah](sabah.json)
- [Sarawak](sarawak.json)
- [Selangor](selangor.json)
- [Terengganu](terengganu.json)

## What's New

For the latest updates, see the [Changelog](CHANGELOG.md).

- [Added new postcode 80888 for Ibrahim International Business District (IIBD) in Johor (2025-12-28)](CHANGELOG.md#2025-12-28)
- [Postcode data accuracy improvements for Pulau Pinang and Johor (2025-06-27)](CHANGELOG.md#2025-06-27)
  - Added missing postcode 79050 to Iskandar Puteri (Johor)
  - Removed 12 invalid postcodes from Pulau Pinang cities to match official reference
  - Removed incorrect postcode 71590 from Pekan Nenas (Johor)
- [Complete coverage review and fixes for multiple states (2025-06-26)](CHANGELOG.md#2025-06-26)
  - Added missing locations: Tenghilan (Sabah), Pusat Mel Miri & Sibu Jaya (Sarawak)
  - Renamed Penang to official name "Pulau Pinang" and updated file name
  - Fixed formatting issues in Negeri Sembilan, Pahang, and Perak
  - Removed invalid postcodes and corrected city names across multiple states
- [Added new postcode for TRX (Tun Razak Exchange) in Kuala Lumpur (2025-03-10)](CHANGELOG.md#2025-03-10)
- [Removed incorrect-length postcodes from various cities (2023-08-27)](CHANGELOG.md#2023-08-27)

## NPM

For those interested in installing this dataset via NPM, you can do so with our [malaysia-postcodes](https://github.com/AsyrafHussin/npm-malaysia-postcodes) package.

## Contributing

If you find any inaccuracies, typos, or missing data, we welcome contributions! Please feel free to open an issue or submit a pull request.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
