# mac-cleanup

### A cleanup script for macOS

</br>

<details>
  <summary>
  What does script do?
  </summary>

</br>

* Empty the Trash on All Mounted Volumes and the Main HDD
* Clear System Log Files
* Clear Adobe Cache Files
* Cleanup iOS Applications
* Remove iOS Device Backups
* Cleanup Xcode Derived Data and Archives
* Reset iOS simulators
* Cleanup Homebrew Cache
* Cleanup Any Old Versions of Gems
* Cleanup Dangling Docker Images
* Purge Inactive Memory
* Cleanup pip cache
* Cleanup Pyenv-VirtualEnv Cache
* Cleanup npm Cache
* Cleanup Yarn Cache
* Cleanup Docker Images and Stopped Containers
* Cleanup CocoaPods Cache Files
* Cleanup composer cache
* Cleanup Dropbox cache
* Remove PhpStorm logs
* Remove Minecraft logs and cache
* Remove Steam logs and cache
* Remove Lunar Client logs and cache
* Remove Microsoft Teams logs and cache
* Remove Wget logs and hosts
* Removes Cacher logs
* Deletes Android caches
* Clears Gradle caches
* Deletes Kite logs
* Clears Go module cache
* Clears Poetry cache

### 🆕 **Advanced Cleanup Features**

#### 🗂️ **System Files & Caches**
* Clear QuickLook thumbnails cache
* Remove .DS_Store files from all directories
* Clear font caches (ATS)
* Clear icon services cache
* Clear location services cache
* Remove core dumps
* Clear system installer logs

#### 🌐 **Browser Data (Advanced)**
* Clear Safari downloads and website data
* Remove Chrome crash dumps
* Clear Firefox crash reports
* Clear Microsoft Edge cache
* Clear Opera cache
* Clear Brave browser cache

#### 📱 **iOS/Mobile Development**
* Clear iOS device support files
* Remove old simulator runtimes
* Clear Xcode user data
* Clear iOS app installer cache

#### 🎮 **Gaming & Entertainment**
* Clear Discord cache
* Clear Spotify persistent cache
* Clear VLC cache
* Clear IINA cache
* Clear Steam workshop files

#### 💼 **Professional Apps**
* Enhanced Adobe Creative Cloud cleanup
* Clear Final Cut Pro cache
* Clear Logic Pro cache
* Clear Sketch cache
* Clear Figma desktop cache
* Clear Canva cache

#### 🔧 **Development Tools (Extended)**
* Clear Rust cargo registry cache
* Clear Python pip cache
* Clear Ruby gems cache
* Clear Maven repository cache
* Clear PHP Composer cache
* Clear R packages cache
* Clear Conda packages cache

#### 📝 **Code Editors & IDEs**
* Enhanced JetBrains IDEs cache cleanup
* Clear VSCode extensions node_modules
* Clear Sublime Text cache
* Clear Cursor cache
* Clear Nova cache

#### 💬 **Communication Apps**
* Clear Slack cache
* Clear Zoom cache and logs
* Clear WhatsApp cache
* Clear Telegram Desktop cache and logs

#### 🗄️ **Database & Servers**
* Clear MongoDB logs
* Clear PostgreSQL logs
* Clear MySQL logs
* Clear Redis logs
* Clear Elasticsearch logs

#### 🔄 **Cloud Storage**
* Clear OneDrive cache and logs
* Clear Box cache
* Clear pCloud cache
* Clear Sync.com cache

#### ⚡ **System Optimization**
* Rebuild LaunchServices database
* Clear quarantine attributes from Downloads
* Reset font cache

#### 🛡️ **Security & Privacy**
* Clear keychain logs
* Clear diagnostic reports
* Clear crash reporter data
* Clear analytics and usage statistics

</details>



## Install Automatically

### Using homebrew

```bash
brew tap fwartner/tap
brew install fwartner/tap/mac-cleanup
```
<details>
  <summary>
  Error: SHA256 mismatch
  </summary>

> If you'll see ```Error: SHA256 mismatch``` try this:
> 1. Copy "Actual" hash from error
> 2. Run ```brew edit fwartner/tap/mac-cleanup```
> 3. Press ```I``` and change ```sha256 "<some hash>"``` with hash from step 1
> 4. Press ```:```, then ```wq``` and ```Enter```
> 5. Re-run installation \
> ```brew install fwartner/tap/mac-cleanup```

</details>


### Using curl

```bash
curl -fsSL https://raw.githubusercontent.com/mac-cleanup/mac-cleanup-sh/main/installer.sh | bash -s install
```

### Using wget

```bash
wget https://raw.githubusercontent.com/mac-cleanup/mac-cleanup-sh/main/installer.sh -O - | bash -s install
```

## Step by Step Install

1. Download: `curl -o cleanup https://raw.githubusercontent.com/mac-cleanup/mac-cleanup-sh/main/mac-cleanup`
2. Make it executable: `chmod +x cleanup`
3. Move to make it globally usable: `sudo mv cleanup /usr/local/bin/cleanup`

### Note:
If installing with curl you need to call `cleanup` instead of `mac-cleanup`.

## Update

### Using curl

```bash
curl -fsSL "https://raw.githubusercontent.com/mac-cleanup/mac-cleanup-sh/main/installer.sh" | bash -s update
```

### Using wget

```bash
wget "https://raw.githubusercontent.com/mac-cleanup/mac-cleanup-sh/main/installer.sh" -O - | bash -s update
```

## Uninstall

### Using curl

```bash
curl -fsSL "https://raw.githubusercontent.com/mac-cleanup/mac-cleanup-sh/main/installer.sh" | bash -s uninstall
```

### Using wget

```bash
wget "https://raw.githubusercontent.com/mac-cleanup/mac-cleanup-sh/main/installer.sh" -O - | bash -s uninstall
```

## Usage Options

Help menu:

```
$ mac-cleanup -h

A Mac Cleanup Utility by fwartner
https://github.com/mac-cleanup/mac-cleanup-sh

USAGE:
 mac-cleanup [FLAGS]

FLAGS:
-h, --help       Prints help menu
-d, --dry-run    Print approx space to be cleaned
-v, --verbose    Print script debug info
-u, --update     Run brew update
```

## Contributors

### Code Contributors

This project exists thanks to all the people who contribute.
<a href="https://github.com/mac-cleanup/mac-cleanup-sh/graphs/contributors"><img src="https://opencollective.com/mac-cleanup/contributors.svg?width=890&button=false" /></a>

<a href="https://opencollective.com/mac-cleanup/organization/0/website"><img src="https://opencollective.com/mac-cleanup/organization/0/avatar.svg"></a>
<a href="https://opencollective.com/mac-cleanup/organization/1/website"><img src="https://opencollective.com/mac-cleanup/organization/1/avatar.svg"></a>
<a href="https://opencollective.com/mac-cleanup/organization/2/website"><img src="https://opencollective.com/mac-cleanup/organization/2/avatar.svg"></a>
<a href="https://opencollective.com/mac-cleanup/organization/3/website"><img src="https://opencollective.com/mac-cleanup/organization/3/avatar.svg"></a>
<a href="https://opencollective.com/mac-cleanup/organization/4/website"><img src="https://opencollective.com/mac-cleanup/organization/4/avatar.svg"></a>
<a href="https://opencollective.com/mac-cleanup/organization/5/website"><img src="https://opencollective.com/mac-cleanup/organization/5/avatar.svg"></a>
<a href="https://opencollective.com/mac-cleanup/organization/6/website"><img src="https://opencollective.com/mac-cleanup/organization/6/avatar.svg"></a>
<a href="https://opencollective.com/mac-cleanup/organization/7/website"><img src="https://opencollective.com/mac-cleanup/organization/7/avatar.svg"></a>
<a href="https://opencollective.com/mac-cleanup/organization/8/website"><img src="https://opencollective.com/mac-cleanup/organization/8/avatar.svg"></a>
<a href="https://opencollective.com/mac-cleanup/organization/9/website"><img src="https://opencollective.com/mac-cleanup/organization/9/avatar.svg"></a>

If you like what I am doing please consider [sponsor my work](https://github.com/sponsors/fwartner)!
