See `dimitris_attestation.txt` in this directory for Dimitris Apostolou's signed attestation.

Hash of the [`challenge`](https://ppot.blob.core.windows.net/public/challenge_0028) file for verification:

```
    f71e9315 058c1c88 ba4cd22e 01f86242
    d81b5e74 de829ad8 8bd7ecef 475ca3ce
    d59eaa77 7e2ebfd3 14c38bde 84a47ebf
    c3143252 9c978b84 b25cddf7 a6212371
```

`response` was based on the hash:

```
    f71e9315 058c1c88 ba4cd22e 01f86242
    d81b5e74 de829ad8 8bd7ecef 475ca3ce
    d59eaa77 7e2ebfd3 14c38bde 84a47ebf
    c3143252 9c978b84 b25cddf7 a6212371
```

Hash of the [`response`](https://ppot.blob.core.windows.net/public/response_0028_dimitris) file for verification:

```
    1488bd2d 1acf5ec7 c3636ff2 ba23cf99
    7cf9ef7e eee6af0f 98150c11 e1c18b14
    6c7225ed 6cecbe0d 749b8d2f b96a3139
    04ec9b9c d5035958 f77dae70 75d3326e
```

Blake2b hash of the `new_challenge` file for participant #29:

```
    aa470426 518e2a2e 287b1b18 92767431
    5646e93d d4f2ec4b d5beb54e 0d78f331
    9e98e46a 0d50dcf7 3f06bb7e 7258a752
    635d176e 8101350d 3d61108a 58e08962
```

The above `new_challenge` file: https://ppot.blob.core.windows.net/public/challenge_0029

Dimitris' attestation:

```
Attestation to response 0028
----------------------------

*Date*: Mon Mar 23 2020 - Wed Mar 25 2020
*Name*: Dimitris Apostolou
*Location*: Voula, Greece
*Device*: Apple MacBook Pro 15,1 with macOS 10.15.4 (19E264b)
*Commit Hash*: bf852c168676a7afc5dd17b47ff9b8f394aeab8a
*Challenge*:
URL: https://ppoteu.blob.core.windows.net/public/challenge_0028

```
`challenge` file contains decompressed points and has a hash:
	f71e9315 058c1c88 ba4cd22e 01f86242 
	d81b5e74 de829ad8 8bd7ecef 475ca3ce 
	d59eaa77 7e2ebfd3 14c38bde 84a47ebf 
	c3143252 9c978b84 b25cddf7 a6212371 
`challenge` file claims (!!! Must not be blindly trusted) that it was based on the original contribution with a hash:
	379ecd36 fd2650c0 2196c9b4 13ea0f28 
	2d5545c9 ed270075 fd5b5000 60a41e67 
	8d5b75fc b22221b4 2636b741 0c45d9a1 
	68a4bf12 a6e91efc 14e09be2 20780990
```

*Response*:
```
The BLAKE2b hash of `./response` is:
	1488bd2d 1acf5ec7 c3636ff2 ba23cf99 
	7cf9ef7e eee6af0f 98150c11 e1c18b14 
	6c7225ed 6cecbe0d 749b8d2f b96a3139 
	04ec9b9c d5035958 f77dae70 75d3326e
```

*Time taken* 
Download: About 10 hours
Execution: About 10 hours
Upload: About 31 hours

*Entropy Sources*: Keys smashing

*Side channel defences*: Disabled WiFi
*Postprocessing*: Rebooted the machine
```
