[&lt;&lt; return to homepage](../)

# Dogecoin Blockchain Download

Downloadable blockchain for Dogecoin Portable (and Dogecoin) configured to prune at 2.2GB

## How To Download

Go to the [Dogecoin Blockchain Releases page](https://github.com/Blockchains-Download/Dogecoin/releases) and download the files for the most recent release. It will be 3 files named similarly to Dogecoin-Blockchain-DATE.exe, Dogecoin-Blockchain-DATE.7z.001, Dogecoin-Blockchain-DATE.7z.002.

## How To Extract

Ensure all 3 files are in the same directory. Check the Dogecoin-Blockchain-DATE.exe to ensure it is digitally signed by Rare Ideas, LLC. Run the EXE. For Dogecoin Portable, select to extract the files to your DogecoinPortable\Data\Dogecoin directory. If the Dogecoin directory doesn't yet exist, create it. For a locally installed Dogecoin client, extract to %APPDATA%\Dogecoin, usually located at C:\Users\YourUsername\AppData\Roaming\DogeCoin

## Configure Pruned Mode

Dogecoin Portable can be configured for pruned mode by creating an ANSI text file called [dogecoin.conf](dogecoin.conf) in your DogecoinPortable\Data\Dogecoin directory with a single line reading prune=2200 and nothing else. For a local Dogecoin client, download the file to %APPDATA%\Dogecoin, usually located at C:\Users\YourUsername\AppData\Roaming\DogeCoin
