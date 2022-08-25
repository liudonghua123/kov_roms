# Knights of Valour roms

These roms are download from https://www.planetemu.net/roms/finalburn-neo-arcade-games?page=K. There are 46 roms in this repo.

### Motivation

I collect these roms just based on personal interests and hobbies. Please do not use for commercial purposes or other illegal purposes.

I searched and compared the kov roms in [fbneo roms](https://www.planetemu.net/roms/finalburn-neo-arcade-games?page=K), [fba roms](https://www.planetemu.net/roms/fb-alpha?page=K), [mame roms](https://www.planetemu.net/roms/mame-roms?page=K) on https://www.planetemu.net/. There are 46 in fbneo, 31 in fba and 32 in mame. I just tested a few roms, all of the three emulator works.

### List

```shell
.
├── kov111.zip
├── kov114.zip
├── kov115.zip
├── kov2100.zip
├── kov2101.zip
├── kov2102.zip
├── kov2103.zip
├── kov2104.zip
├── kov2106.zip
├── kov2nl_300.zip
├── kov2nl_301.zip
├── kov2nl.zip
├── kov2p200.zip
├── kov2p202.zip
├── kov2p203.zip
├── kov2p204.zip
├── kov2pemp.zip
├── kov2pfwll.zip
├── kov2pshpd.zip
├── kov2p.zip
├── kov2.zip
├── kov3_100.zip
├── kov3_101.zip
├── kov3_102.zip
├── kov3.zip
├── kovassga.zip
├── kovplus2020tx.zip
├── kovplusa.zip
├── kovplus.zip
├── kovqhsgsa.zip
├── kovqhsgsd.zip
├── kovqhsgs.zip
├── kovsgqyza.zip
├── kovsgqyzb.zip
├── kovsgqyzc.zip
├── kovsgqyzd.zip
├── kovsgqyz.zip
├── kovsh100.zip
├── kovsh101.zip
├── kovsh102.zip
├── kovsh103.zip
├── kovshb.zip
├── kovshp100.zip
├── kovshp101.zip
├── kovshpqszltw.zip
├── kovshpqszl.zip
├── kovshp.zip
├── kovshpzqhl.zip
├── kovsh.zip
├── kovytzyce.zip
├── kovytzyws.zip
├── kovytzy.zip
├── kov.zip
└── pgm.zip
```

### Updates

- Add 3 roms of [Knights of Valour 2 New Legend](https://www.planetemu.net/rom/mame-roms/kov2nl), *mame only*.

- Add 4 roms of [Knights of Valour 3](https://www.planetemu.net/rom/mame-roms/kov3), *mame only*. The [kov3](https://www.planetemu.net/rom/mame-roms/kov3) is larger then 100MB which over the github maximum single file size. So I did not upload here. If you want to run `kov3` game, you must download yourself.

### Notice

I tested within the latest fbneo `v1.0.0.02`, only two games not auto discoverable. It seems other 44 games are ok.

- [Knights of Valour Plus - Qun Xiong Luan Wu 2020 (Hack) [Hack]](https://www.planetemu.net/rom/finalburn-neo-arcade-games/kovplus2020tx)

    The related rom file is `kovplus2020tx.zip`.

    When try to run it, these errors occured. *But you can still run it.*

    ```
    kovplus2020tx was found (D:\game\fbneo\roms\arcade\pgm\kovplus2020tx).
    pgm was found (D:\game\fbneo\roms\arcade\pgm\pgm).
    kovplus was found (D:\game\fbneo\roms\arcade\pgm\kovplus).

    The following ROMs are invalid:
    ? essential program ROM 2020tx_p0603_119.u1 has a CRC of 8726FFED (correct is C0DE9E51).

    The ROMset exhibits the following problems:
    ? essential data is invalid, the game might not run!
    ? program data is invalid.
    ```

- [Knights of Valour 2 Plus - Feng Wu Long Yin (Ver. 205S, Hack) [Hack]](https://www.planetemu.net/rom/finalburn-neo-arcade-games/kov2pfwll)

    The related rom file is `kov2pfwll.zip`.

    When try to run it, these errors occured.

    ```
    kov2pfwll was found (D:\game\fbneo\roms\arcade\pgm\kov2pfwll).
    pgm was found (D:\game\fbneo\roms\arcade\pgm\pgm).
    kov2p was found (D:\game\fbneo\roms\arcade\pgm\kov2p).

    The following ROMs are invalid:
    ? essential program ROM kov2pfwll_32m.u8 is 4096k which is too small (correct is 6144kB).
    ? essential program ROM kov2pfwll_16m.u23 has a CRC of A147C7F1 (correct is 5EBB2CD8).

    The ROMset exhibits the following problems:
    ? essential data is missing, the game will not run!
    ? program data is missing.
    ```