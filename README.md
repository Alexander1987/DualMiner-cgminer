# DualMiner-cgminer
cgminer for One Chip DualMiner USB

Usage:

First run the AutoInstaller to compile and install cgminer.

	$ ./RPi-AutoInstaller

Wait for the AutoInstaller to finish and then use the Worker Generator to make executable bash file for running miner.

	$ ./Worker-Generator

First choose a name for the bash script to be saved as, no spaces allowed.

	  Save As:
	  Exampe

Second type/paste in chosen scrypt pool url.

	  Pool URL:
	  stratum+tcp://us2.litecoinpool.org:3333

Third type/paste in worker name for selected pool.

	  Pool Worker:
	  Meap10.Test

Forth type/paste in worker password.

	  Worker Password:
	  x

Once that's done run the script just made with a ./ infront of the name.

	$ ./Example  

If all is done well you should see something like this.

 [2021-08-28 10:35:29] Started cgminer 3.5.0                    
 [2021-08-28 10:35:29] dualminer Detect LTC: Test Success at 1:5-i0: get 00050cdd, should: 00050cdd                    
 [2021-08-28 10:35:31] Detected Ltc devices total: 1                    
 [2021-08-28 10:35:31] Probing for an alive pool                    
 [2021-08-28 10:35:31] Pool 0 difficulty changed to 256                    
 [2021-08-28 10:35:32] Network diff set to 669G                    
 [2021-08-28 10:35:34] Stratum from pool 0 requested work restart                    
 [2021-08-28 10:35:34] Stratum from pool 0 detected new block                    
 [2021-08-28 10:35:49] Stratum from pool 0 requested work restart                    
 [2021-08-28 10:35:56] Stratum from pool 0 detected new block                    
 [2021-08-28 10:35:57] Stratum from pool 0 requested work restart                    
 [2021-08-28 10:37:15] Stratum from pool 0 detected new block                    
 [2021-08-28 10:37:15] Stratum from pool 0 requested work restart                    
 [2021-08-28 10:37:38] Stratum from pool 0 detected new block                    
 [2021-08-28 10:37:38] Stratum from pool 0 requested work restart                    
 [2021-08-28 10:38:01] Accepted 537d4954 Diff 447/256 DM 0                    
 [2021-08-28 10:38:01] Accepted 48f0f7a5 Diff 1.63K/256 DM 0 
