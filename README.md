# DayZ Community Samples

This repository is created by the DayZ Modding community, to help other modders learn how to do a certain thing, be it creating vehicles or weapons or script examples.

## Contribution

To contribute to this repository, please make a pull request with your changes or additions. Any changes or additions that have not been tested will be rejected.

You must ONLY upload source (unbinarized, unobfuscated and uncompressed) files. Anything else will be rejected.

## File Structure

When contributing to this repository, you must follow the structure below:
```
SampleWeapon
      - Sub-Folder
           - Texture.paa
           - Material.rvmat
      - Sub-Folder2
           - Proxy.p3d
      - Config.cpp
      - Weapon.p3d
```

All samples should be setup to work as a standalone mod. Any config/texture/model paths should be relative from the sample parent folder.

An example model path in a config would be `SampleWeapon\WeaponModel.p3d`.

If you are doing script-based samples, make sure to follow the VANILLA file structure, for example: `Scripts\4_World\Entities\ManBase\PlayerBase.c`.

##