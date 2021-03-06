See `zac_attestation.sig` in this directory for Zac Williamson's signed attestation.

Hash of the [`challenge`](https://ppot.blob.core.windows.net/public/challenge_0006) file for verification:

```
        a7b3c130 cd8dbd26 769cfbcb e4c9a4ef
        9055d13b ac932854 81c1007c acf51d29
        c00dd146 d73a6670 47f65200 ae227e01
        d589c609 04d263a4 1f5f187d 03fcc692
```

`response` was based on the hash:      

```
        a7b3c130 cd8dbd26 769cfbcb e4c9a4ef
        9055d13b ac932854 81c1007c acf51d29
        c00dd146 d73a6670 47f65200 ae227e01
        d589c609 04d263a4 1f5f187d 03fcc692
```

Hash of the [`response`](https://ppot.blob.core.windows.net/public/response_0006_zac) file for verification:

```
        fbb8512f 393ffd01 7c20b1b6 6f7f5cf2
        05f1de39 4fa987a7 03dc3fc6 c3957613
        b33e69a9 143ae272 cd3e02b1 4db3c5d4
        24ab0695 27e3e813 2a7b7ecf 8bbd05df
```

Blake2b hash of the `new_challenge` file for participant #7:

```
        3e1140e5 66971cbd e6308dc3 d3f2ef4e
        2c36bb4d b16704ed 0ffd26ee 7d80ccce
        f2b46aa4 6feadf3e 2da8c43e ccf7588a
        09e6cd94 85a4dd05 20af752d b0f24128
```

The above `new_challenge` file: https://ppot.blob.core.windows.net/public/challenge_0007

Zac's attestation (from `zac_attestation.txt`):

```
Hello there,

I finished computing a response file for the sixth round of the powers of tau ceremony.

Date: 25-27 September 2019

Name: Zachary Williamson

Location: London, UK

Device(s): Surface pro 6, running Windows 10

Challenge hash:

        a7b3c130 cd8dbd26 769cfbcb e4c9a4ef
        9055d13b ac932854 81c1007c acf51d29
        c00dd146 d73a6670 47f65200 ae227e01
        d589c609 04d263a4 1f5f187d 03fcc692

Response hash:

        fbb8512f 393ffd01 7c20b1b6 6f7f5cf2
        05f1de39 4fa987a7 03dc3fc6 c3957613
        b33e69a9 143ae272 cd3e02b1 4db3c5d4
        24ab0695 27e3e813 2a7b7ecf 8bbd05df

Hash of new_challenge file for participant #7

        3e1140e5 66971cbd e6308dc3 d3f2ef4e
        2c36bb4d b16704ed 0ffd26ee 7d80ccce
        f2b46aa4 6feadf3e 2da8c43e ccf7588a
        09e6cd94 85a4dd05 20af752d b0f24128

Entropy sources: Randomly key mashing, not much else!

Time taken: around 48 hours.

Side channel defences: None

Attached the attestation as a file and a GPG signature. The signature can be verified with gpg --verify zac_attestation.sig zac_attestation.txt.

Zac
```
