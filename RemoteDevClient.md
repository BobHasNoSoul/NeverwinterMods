to use the dev client on a remote machine you must have the server mapped as a network drive via samba share so your computer can see it as Z:\Night however it can be any letter you want

you then need to copy the Night folder over to your hdd and then navigate to night/tools/bin (or if you have a beefy connection you can run the following command in command prompt via your samba share)

`./GameClient.exe  -SetProductName Night NW -SetShardCategory Live -SetShardName Neverwinter -MTCategory Live -ShardName Neverwinter -ShardCategory Live -controllerHost code -SetAccountServer code -SetTicketTracker code -SetShardBeaconMasterServer code -SetControllerTracker code`

note this assumes you already set up your hosts file accordingly if not replace code with the ip of server
