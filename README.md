# DriverTester
DriverTester it's a little program I developed to test IOCTLs in Drivers.
It was developed to test the functionality of the HackAV Rootkit.
Works in x86/x64 systems.

## Releases

Go to the Releases tab and download the compiled executables.

## Usage

In order to work it needs the devicename of the driver to connect, the ioctl to test and an optional buffer to send.

```
DriverTester.exe DRIVERNAME IOCTL [BUFFER]
```

Connect to "ccc" driver and send the IOCTL 222009
```
DriverTester.exe ccc 222009
```

## Building 
__Requirements__
 - Download and install Microsoft Visual C++ Build Tools or Visual Studio 

__Build Steps__
 - Clone the repo and navigate to the directory
 - Open the SLN file to open the project to Visual Studio
 - Select the platform in which you will be compiling the binary (x32 or x64)
 - Go to Compile->Compile Solution to generate the EXE file
 
 ## Feedback

Any questions, comments or requests you can find me on twitter: [@sisoma2](https://twitter.com/sisoma2)
Pull requests welcome! 
