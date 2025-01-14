<span class="badge-opencollective"><a href="https://github.com/ZarTek-Creole/DONATE" title="Donate to this project"><img src="https://img.shields.io/badge/open%20collective-donate-yellow.svg" alt="Open Collective donate button" /></a></span>
[![CC BY 4.0][cc-by-shield]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
online documentation. 

## Versions
* UnrealIRCd 6 is the *stable* series since December 2021. All new features go in there.
* UnrealIRCd 5 is the *oldstable* series. It will receive bug fixes until
  July 1, 2022 plus another 12 months of security fixes.
* For full details of release scheduling and EOL dates, see
  [UnrealIRCd releases](https://www.unrealircd.org/docs/UnrealIRCd_releases) on the wiki

## How to get started
### Use the wiki!
**IMPORTANT:** We recommend you follow our installation guide on the wiki instead of the
steps in this README. The wiki has more detailed information and is more easy to navigate.
* [Installing from source for *NIX](https://www.unrealircd.org/docs/Installing_from_source)
* [Installating instructions for Windows](https://www.unrealircd.org/docs/Installing_(Windows))

Please consult the online documentation at https://www.unrealircd.org/docs/ when setting up the IRCd!

### Step 1: Installation
#### Windows
Simply download the UnrealIRCd Windows version from www.unrealircd.org

Alternatively you can compile UnrealIRCd for Windows yourself. However this is not straightforward and thus not recommended.

#### *BSD/Linux/macOS
Do the following steps under a separate account for running UnrealIRCd,
[do NOT compile or run as root](https://www.unrealircd.org/docs/Do_not_run_as_root).

### Step 1: Compile the IRCd

* Run `./Config`
* Run `make`
* Run `make install`
* Now change to the directory where you installed UnrealIRCd, e.g. `cd /home/xxxx/unrealircd`

### Step 2: Configuration
Configuration files are stored in the `conf/` folder by default (eg: `/home/xxxx/unrealircd/conf`)

#### Create a configuration file
If you are new, then you need to create your own configuration file:
Copy `conf/examples/example.conf` to `conf/` and call it `unrealircd.conf`.
Then open it in an editor and carefully modify it using the documentation and FAQ as a guide (see below).

### Step 3: Booting

#### Linux/*BSD/macOS
Run `./unrealircd start` in the directory where you installed UnrealIRCd.

#### Windows
Start -> All Programs -> UnrealIRCd -> UnrealIRCd

## Documentation & FAQ
You can find the **documentation** online at: https://www.unrealircd.org/docs/

We also have a good **FAQ**: https://www.unrealircd.org/docs/FAQ

## Website, support, and other links ##
* https://www.unrealircd.org - Our main website
* https://forums.unrealircd.org - Support
* https://bugs.unrealircd.org - Bug tracker
* ircs://irc.unrealircd.org:6697/unreal-support - IRC support
