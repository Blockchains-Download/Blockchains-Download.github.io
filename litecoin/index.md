[&lt;&lt; return to homepage](../)

# Litecoin Blockchain Download

Downloadable blockchain for Litecoin Portable (and Litecoin) configured to prune at 2.2GB

## How To Download

Go to the [Litecoin Blockchain Releases page](https://github.com/Blockchains-Download/Litecoin/releases) and download the files for the most recent release. It will be 3 files named similarly to Litecoin-Blockchain-DATE.exe, Litecoin-Blockchain-DATE.7z.001, Litecoin-Blockchain-DATE.7z.002.

## How To Extract By Running

Ensure all 3 files are in the same directory. Check the Litecoin-Blockchain-DATE.exe to ensure it is digitally signed by Rare Ideas, LLC. Run the EXE. For Litecoin Portable, select to extract the files to your LitecoinPortable\Data\Litecoin directory. If the Litecoin directory doesn't yet exist, create it. For a locally installed Litecoin client, extract to %APPDATA%\Litecoin, usually located at C:\Users\YourUsername\AppData\Roaming\Litecoin

## How To Extract With 7-Zip

*It's not necessary to run the EXE to extract the files, you can also use 7-Zip*

Ensure all files are in the same directory. Open the file Litecoin-Blockchain-DATE.7z.001 in 7-Zip. For Litecoin Portable, select to extract the files to your LitecoinPortable\Data\Litecoin directory. If the Litecoin directory doesn't yet exist, create it. For a locally installed Litecoin client, extract to %APPDATA%\Litecoin, usually located at C:\Users\YourUsername\AppData\Roaming\Litecoin

## Configure Pruned Mode

Litecoin Portable can be configured for pruned mode by creating an ANSI text file called [litecoin.conf](litecoin.conf) in your LitecoinPortable\Data\Litecoin directory. For a local Litecoin client, download the file to %APPDATA%\Litecoin, usually located at C:\Users\YourUsername\AppData\Roaming\Litecoin. The file should contain:

prune=550

blockfilterindex=0

peerblockfilters=0
