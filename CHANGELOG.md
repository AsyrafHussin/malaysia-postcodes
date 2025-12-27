# Changelog

This changelog documents all notable changes to the `malaysia-postcodes` repository.

## [2025-12-28]

### Added

- Added new postcode for Ibrahim International Business District (IIBD) in Johor:
  - Ibrahim International Business District: `80888`
  - Effective date: 1 January 2025
  - Approved by Johor Menteri Besar on 24 March 2024
  - Official notification from Majlis Bandaraya Johor Bahru (MBJB) dated 15 December 2024
  - This area was formerly known as Johor Bahru City Centre (JBCC)

## [2025-06-27]

### Added

- Added missing postcode to Johor:
  - Iskandar Puteri: `79050`

### Removed

- Removed invalid postcode entries from Pulau Pinang:
  - Butterworth: `12344`, `12345`, `13030` (postcodes do not exist)
  - Bayan Lepas: `11902` (postcode does not exist)
  - Perai: `13690` (postcode does not exist)
  - Pulau Pinang: `10020`, `10110`, `10160`, `10420`, `10520`, `10668`, `11460` (postcodes do not exist)
- Removed incorrect postcode from Johor:
  - Pekan Nenas: `71590`

## [2025-06-26]

### Added

- Added missing location to Sabah:
  - Tenghilan: `89260`
- Added missing locations to Sarawak:
  - Pusat Mel Miri: `98070`
  - Sibu Jaya: `96010`

### Updated

- Renamed state from "Penang" to "Pulau Pinang" and renamed file from penang.json to pulau_pinang.json
- Fixed formatting in Negeri Sembilan:
  - Fixed "Pusat  Bandar Palong" (removed extra space) to "Pusat Bandar Palong"
- Fixed formatting in Pahang:
  - Fixed "Bandar Pusat  Jengka" (removed extra space) to "Bandar Pusat Jengka"
- Updated city names in Perak for accuracy:
  - Renamed "Seri Manjong" to "Seri Manjung" to match official name
  - Renamed "Tldm Lumut" to "TLDM Lumut" to match official format
  - Merged "Mambang Di Awan" postcodes (31920, 31950) into "Kampar"

### Removed

- Removed invalid postcode entry from Negeri Sembilan:
  - Bandar Baru Serting: `72130` (postcode does not exist - "Bandar Baru Serting" is an alternative name for "Bandar Seri Jempol")
- Removed invalid postcode entry from Perak:
  - Rantau Panjang: `42160` (postcode does not exist - 42xxx postcodes belong to Selangor, not Perak)
- Removed duplicate location entry from Perak:
  - Mambang Di Awan: merged into "Kampar" as postcodes 31920, 31950 belong to Kampar post office

## [2025-06-25]

### Updated

- Updated city names in Johor for accuracy:
  - Renamed "Nusajaya" to "Iskandar Puteri" to reflect official city name change
- Updated city names in Selangor for consistency:
  - Renamed "Klia" to "KLIA" to match official airport name format

### Removed

- Removed invalid postcode entry from Johor:
  - Ulu Choh: `81150` (postcode does not exist - actual location is "Kampung Bahagia Ulu Choh" under Pekan Nenas with postcode `81500`)

## [2025-03-10]

### Added

- Added new postcode for TRX (Tun Razak Exchange) in Kuala Lumpur:
  - Kuala Lumpur
    - TRX: `55188`

## [2023-08-27]

### Removed

- Removed incorrect-length postcodes from several cities.
  - Kedah
    - Alor Setar: `5110`, `5330`
    - Bedong: `8170`
    - Langkawi: `7520`
  - Perlis
    - Kangar: `1750`

## [2023-08-20]

### Updated

- Updated previously missing postcodes for several cities in Melaka.
  - Cities updated:
    - Melaka
    - Merlimau
    - Selandar
    - Sungai Rambai
    - Sungai Udang
    - Tanjong Kling

## [2020-01-01]

### Added

- Initial release of Malaysia Postcodes in JSON format. Includes:
  - All Postcodes
  - Johor
  - Kedah
  - Kelantan
  - Kuala Lumpur
  - Labuan
  - Melaka
  - Negeri Sembilan
  - Pahang
  - Penang
  - Perak
  - Perlis
  - Putrajaya
  - Sabah
  - Sarawak
  - Selangor
  - Terengganu
