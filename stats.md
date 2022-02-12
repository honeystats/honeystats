### General 
  IP addresses - aggregate logs
  
  Country - use geoip processor in kibana on IP addresses
  
  Time of day - aggregate logs
  
  Ports probed?
  
  Services hacked/attempted - based on log source

### SSH
  IP addresses
  
  Source ports
  
  Country - use geoip processor in kibana on IP addresses
  
  Time of day
  
  Usernames
  
  Passwords
  
  Commands entered
  
  Packets?
  
  Bytes?
  
    -script needs to record this information into a log

### Web


### FTP


### RDP


### possibilities if time
  connection length of time
  
  record keystrokes
  
  files downloaded/URLs accessed - possibly infer purpose of attack (botnet, cryptomining, etc)
  
  files accessed - if we are adding files?
  
  time between commands - differentiate human vs script
  
  maybe try p0f? - passive OS fingerprinting
