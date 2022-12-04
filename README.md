## Arduino Boards for Omen Devices

Contains definitions for:

1. Omen ConMan (based on Adafruit ItsyBitsy M0)
1. Omen Raven  (based on Adafruit ItsyBitsy M0)

### Installation

Add this URL to your list of Board Manager URLs:

https://raw.githubusercontent.com/crstffr/omen.boards/main/packages_omen_index.json

## Generating New Files

```bash
// Copy src to temp versioned folder
cp ./src ./Omen-0.0.5

// Zip the versioned folder
zip -r Omen-0.0.5.zip ./Omen-0.0.5 

// Get file size, put in JSON file
stat ./Omen-0.0.5.zip

// Get checksum, put in JSON file
sha256sum ./Omen-0.0.5.zip

// Remove temp versioned folder
rm -rf ./Omen-0.0.5
```
