[&lt;&lt; return to homepage](../)

# Bitcoin Blockchain Download

Downloadable blockchain for Bitcoin Core Portable and locally installed Bitcoin pruned to 2.2GB

## How To Download

Go to the [Bitcoin Blockchain Releases page](https://github.com/Blockchains-Download/Bitcoin/releases) and download the 4 files for the most recent release. It will be files named Bitcoin-Blockchain-DATE.exe, Bitcoin-Blockchain-DATE.7z.001, Bitcoin-Blockchain-DATE.7z.002, Bitcoin-Blockchain-DATE.7z.003.
 
## How To Extract

Ensure all files are in the same directory. Check the Bitcoin-Blockchain-DATE.exe to ensure it is digitally signed by Rare Ideas, LLC. Run the EXE. For Bitcoin Portable, select to extract the files to your BitcoinPortable\Data\Bitcoin directory. If the Bitcoin directory doesn't yet exist, create it. For a locally installed Bitcoin client, extract to %APPDATA%\Bitcoin, usually located at C:\Users\YourUsername\AppData\Roaming\Bitcoin

## Configure Pruned Mode

Bitcoin Portable can be configured for pruned mode by creating an ANSI text file called [Bitcoin.conf](Bitcoin.conf) in your BitcoinPortable\Data\Bitcoin directory with a single line reading prune=2200 and nothing else. For a local Bitcoin client, download the file to %APPDATA%\Bitcoin, usually located at C:\Users\YourUsername\AppData\Roaming\Bitcoin
