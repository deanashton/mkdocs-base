## Hardware
  
The Target Tracker software is recommended as a local installation and requires a minimum of:

- Microsoft Windows 7, 8 or 10
- 1.33 GHz Atom Processor
- 2GB of system memory
- At least 1GB available hard disk space
- Minimum screen resolution 1024 x 768
- Internet access with outgoing access to TCP port 1433
- IE11 must be installed to view the Exemplar videos
- The above specifications represent a minimum requirement and we use such devices in testing.  A device with the minimum specification may not offer the best experience of the Target Tracker program, particularly if it is to be used on a regular basis.  Vista support ends on April 11th 2017 to coincide with Microsoft ending their extended support for the operating system.

## Network

Only outbound connections on TCP port 1433 are needed for the application to communicate with SQL Azure database - inbound connections on TCP port 1433 should remain blocked.

### Observations Test
If you can see the Target Tracker logo below then Observations should work.

![](https://ttc.blob.core.windows.net/public/test.png)


If you cannot see the logo you will need to alter your internet filtering to permit access to *.blob.core.windows.net 

### Exemplars Test
If you can see the exemplar below then exemplars should work.
 
![](http://primarytracker.blob.core.windows.net/exemplars-tt/3-1-01.png)

### Video test
If you can view the video below then tutorial and exemplar videos should work.
 
Target Tracker Videos use Vimeo hosting. If you cannot see the video you will need to allow unfiltered access to vimeo.com
