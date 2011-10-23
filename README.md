AppProxyCap 
===========
Application-wide proxy setting

## Usage
add the following line to your application before any network call:

	[AppProxyCap activate];
	[AppProxyCap setProxy:AppProxy_HTTP Host:@"127.0.0.1" Port:8086];


## Supported OS
Tested in Mac OS X 10.7.2, iOS 5.0 device and simulator