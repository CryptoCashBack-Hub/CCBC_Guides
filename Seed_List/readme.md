# To add the nodes to your configuration file
  ## Enter command below
  ```
    nano /root/.ccbc/ccbc.conf
  ```
  
  * Get the latest node seeds from and put them in our configuration file [here](https://github.com/CryptoCashBack-Hub/CCB_Guides/blob/master/Seed_List/seeds) Add nodes after current data.
  
  ## Now save you configuration file
  
  ```
  press crlt+o *Saves file*
  ```
  ```
  press crlt+x *Exits*
  ```
  ```
  press Y *If promted to answer Y/N*
  ```
  ```
  press enter
  ```
  
  ## Now you need to stop the service and start it back up
  
   ```
   ./ccbc-cli stop
   ```
   ```
   ./ccbcd
   ```
   
   ## Now make sure you block height increases and matches the current block height on the explorer
   
   ```
   watch ./ccbc-cli getinfo
   ```
   
   ## Make sure it synced all the way with this command
   ```
   ccbc-cli mnsync status
   ```
   
   
   ##### Provided by: litofcas
