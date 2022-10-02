# RDP Windows Remote


![](https://i.postimg.cc/66vNjyJ6/ezgif-com-gif-maker-1.gif)


## System Info
- OS: Windows Server
- RAM: 7GB DRAM
- Disk: 14GB available of 408GB (SSD)
- Processer: 3.3GHz(2 cores)
- Screen: Flexible
- Internet Speed: 1Gbps or higher
- Preinstall: Python 2, NodeJS 14, PHP 8, R, Epic Launcher, Visual Studio, Chrome, Firefox, Microsoft Edge...

## How to use
* Click Fork in the right corner of the screen to save it to your Github.
* Visit https://dashboard.ngrok.com to get **NGROK_AUTH_TOKEN**
* In Github go to ⚙ Settings> Secrets> New repository secret
* In Name: enter **NGROK_AUTH_TOKEN**
* In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into
* Press Add secret
* Go to Action> windows_remote> Run workflow
* Reload the page and press build > build
* Connect with VNC Viewer/Default Remote Desktop Application
    + Install VNC Viewer
    + Go to: https://dashboard.ngrok.com/endpoints/status copy host(eg: 0.tcp.in.ngrok.io:13472)
    + Username: runneradmin


# Microsoft Windows Server 2022 
- OS Version: 10.0.20348 Build 1006
- Image Version: 20220925.1

## Enabled windows optional features
- Windows Subsystem for Linux [WSLv1]

## Installed Software
### Language and Runtime
- Bash 5.1.16(1)-release
- Go 1.17.13
- Julia 1.8.1
- Kotlin 1.7.10
- LLVM 14.0.6
- Node 16.17.1
- Perl 5.32.1
- PHP 8.1.10
- Python 3.9.13
- Ruby 3.0.4p208

### Package Management
- Chocolatey 1.1.0
- Composer 2.4.2
- Helm 3.9.4
- Miniconda 4.12.0 (pre-installed on the image but not added to PATH)
- NPM 8.15.0
- NuGet 6.3.0.131
- pip 22.2.2 (python 3.9)
- Pipx 1.1.0
- RubyGems 3.2.33
- Vcpkg (build from master \<57d3194e7>)
- Yarn 1.22.19

#### Environment variables
| Name                    | Value    |
| ----------------------- | -------- |
| VCPKG_INSTALLATION_ROOT | C:\vcpkg |
| VCPKG_ROOT              | C:\vcpkg |

### Project Management
- Ant 1.10.12
- Gradle 7.5
- Maven 3.8.6
- sbt 1.7.1

### Tools
- 7zip 22.01
- aria2 1.36.0
- azcopy 10.16.0
- Bazel 5.3.1
- Bazelisk 1.13.2
- Bicep 0.10.61
- Cabal 3.8.1.0
- CMake 3.24.2
- CodeQL Action Bundle 2.10.5
- Docker Compose v1 1.29.2
- Docker Compose v2 2.11.1
- Docker master-dockerproject-2022-03-26
- Docker-wincred 0.7.0
- ghc 9.4.2
- Git 2.37.3.windows.1
- Git LFS 3.2.0
- ImageMagick 7.1.0-49
- InnoSetup 6.2.1
- jq 1.6
- Kind 0.16.0
- Kubectl 1.25.2
- Mercurial 5.0
- Mingw-w64 11.2.0
- Newman 5.3.2
- NSIS v3.08
- OpenSSL 1.1.1
- Packer 1.8.2
- Pulumi v3.40.1
- R 4.2.1
- Service Fabric SDK 9.0.1028.9590
- Stack 2.9.1
- Subversion (SVN) 1.14.2
- Swig 4.0.2
- VSWhere 3.0.3
- WinAppDriver 1.2.2009.02003
- WiX Toolset v3.11.2.4516
- yamllint 1.28.0
- zstd 1.5.2

### CLI Tools
- Alibaba Cloud CLI 3.0.127
- AWS CLI 2.7.35
- AWS SAM CLI 1.57.0
- AWS Session Manager CLI 1.2.339.0
- Azure CLI 2.40.0
- Azure DevOps CLI extension 0.25.0
- GitHub CLI 2.16.0
- Hub CLI 2.14.2

### Rust Tools
- Cargo 1.64.0
- Rust 1.64.0
- Rustdoc 1.64.0
- Rustup 1.25.1

#### Packages
- bindgen 0.60.1
- cargo-audit 0.17.0
- cargo-outdated 0.11.1
- cbindgen 0.24.3
- Clippy 0.1.64
- Rustfmt 1.5.1

### Browsers and webdrivers
- Google Chrome 105.0.5195.127
- Chrome Driver 105.0.5195.52
- Microsoft Edge 105.0.1343.50
- Microsoft Edge Driver 105.0.1343.50
- Mozilla Firefox 105.0.1
- Gecko Driver 0.31.0
- IE Driver 3.150.1.1
- Selenium server 4.4.0

#### Environment variables
| Name              | Value                              |
| ----------------- | ---------------------------------- |
| CHROMEWEBDRIVER   | C:\SeleniumWebDrivers\ChromeDriver |
| EDGEWEBDRIVER     | C:\SeleniumWebDrivers\EdgeDriver   |
| GECKOWEBDRIVER    | C:\SeleniumWebDrivers\GeckoDriver  |
| SELENIUM_JAR_PATH | C:\selenium\selenium-server.jar    |

### Java
| Version             | Vendor          | Environment Variable |
| ------------------- | --------------- | -------------------- |
| 8.0.345+1 (default) | Eclipse Temurin | JAVA_HOME_8_X64      |
| 11.0.16+101         | Eclipse Temurin | JAVA_HOME_11_X64     |
| 17.0.4+101          | Eclipse Temurin | JAVA_HOME_17_X64     |

### Shells
| Name          | Target                            |
| ------------- | --------------------------------- |
| gitbash.exe   | C:\Program Files\Git\bin\bash.exe |
| msys2bash.cmd | C:\msys64\usr\bin\bash.exe        |
| wslbash.exe   | C:\Windows\System32\bash.exe      |

### MSYS2
- Pacman 6.0.1

##### Notes:
```
Location: C:\msys64

Note: MSYS2 is pre-installed on image but not added to PATH.
```

