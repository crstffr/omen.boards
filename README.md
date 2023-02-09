## Arduino Boards for Omen Devices

Contains definitions for:

1. Omen Cobra  (based on Adafruit ItsyBitsy M4)
2. Omen ConMan (based on Adafruit ItsyBitsy M0)
3. Omen Raven  (based on Adafruit ItsyBitsy M0)

### Installation

Add this URL to your list of Board Manager URLs:

https://raw.githubusercontent.com/crstffr/omen.boards/main/packages_omen_index.json

## Generating New Files

```bash
// Copy src to temp versioned folder
cp -r ./src ./Omen-0.0.N

// Zip the versioned folder
zip -r Omen-0.0.N.zip ./Omen-0.0.N 

// Get file size, put in JSON file
stat -l ./Omen-0.0.N.zip

// Get checksum, put in JSON file
sha256sum ./Omen-0.0.N.zip

// Remove temp versioned folder
rm -rf ./Omen-0.0.N
```
