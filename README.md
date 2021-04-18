# esx_toro_sheriff
This is a fork of the resource esx_policejob. Check the original out, it might help you set a department in the city of Los Santos (At Mission Row). The intent behind making and publishing this is to save people the hassle of editing it themselves.

This resource for ESX adds sheriff armories, vehicle garages and ability for cops to search, handcuff people and much more. The resource places the department up in Paleto Bay, but you can move all the points to Sandy Shores if you want. 

This resource is pretty straight fordward, so I'll provide only limited support. If I can't help you, the original developers of esx_policejob may be able to assist you in their issues section in GitHub or in the thread on the cfx.re forums.

Good luck with your server.

### Requirements
* Interior
  * https://es.gta5-mods.com/maps/paleto-bay-sheriff-s-office-extended-sp-and-fivem-mlo

* Auto mode
  * [esx_billing](https://github.com/ESX-Org/esx_billing)
  * [esx_vehicleshop](https://github.com/ESX-Org/esx_vehicleshop)

* Player management (boss actions and armory with buyable weapons)
  * [esx_addoninventory](https://github.com/ESX-Org/esx_addoninventory)
  * [esx_datastore](https://github.com/ESX-Org/esx_datastore)
  * [esx_society](https://github.com/ESX-Org/esx_society)

* ESX Identity Support
  * [esx_identity](https://github.com/ESX-Org/esx_identity)

* ESX License Support
  * [esx_license](https://github.com/ESX-Org/esx_license)

* ESX Service Support
  * [esx_service](https://github.com/ESX-Org/esx_service)

## Download & Installation

### Using [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx esx-org/esx_policejob
```

### Using Git
```
cd resources
git clone https://github.com/ESX-Org/esx_policejob [esx]/esx_policejob
```

### Manually
- Download https://github.com/ESX-Org/esx_policejob/archive/master.zip
- Put it in the `[esx]` directory


## Installation
- Import `esx_policejob.sql` in your database
- Add this to your server.cfg:

```
start esx_policejob
```

-  * If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`
   * If you want armory management you have to set `Config.EnableArmoryManagement` to `true` in `config.lua`
   * If you want license management you have to set `Config.EnableLicenses` to `true` in `config.lua`
   * If you want service management you have to set `Config.MaxInService` to a higher value than `-1` in `config.lua`

# Legal
### License
esx_toro_sheriff was made by modifying this script:

  esx_policejob - police script for ESX

  Copyright (C) 2015-2020 Jérémie N'gadi

  This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

  This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

  You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.

Therefore we adhere to the same licenses and conditions (Free software under GNU GPL)
