# esx_bmvehicles

Black Market vehicles is just another vehicle shop that strictly sells weaponized vehicles.  There is no phone number to call or map blip to see.  This must be found by word of mouth.

You can find the shop here:
![Shop Location](https://media.discordapp.net/attachments/455425743858434051/523391543617388554/f276af5ae096967b688aaaa2800a9e1e.png)

You will be teleported into the Smuggler's Run hangar:
![Inside Shop](https://media.discordapp.net/attachments/455425743858434051/523391543223255042/1582c5b3bfd90e7066692b0e918d6315.jpg)

## Requirements

* Auto mode (everyone can buy vehicles from the dealer)
  * No need to download another resource

* Player management (the car dealer job): billing, boss actions and more!
  * [esx_society](https://github.com/ESX-Org/esx_society)
  * [esx_billing](https://github.com/ESX-Org/esx_billing)
  * [esx_addonaccount](https://github.com/ESX-Org/esx_addonaccount)
  * [esx_addoninventory](https://github.com/ESX-Org/esx_addoninventory)
  * [cron](https://github.com/ESX-Org/cron)

## Download & Installation

### Using [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx esx-org/esx_vehicleshop
```

### Using Git
```
cd resources
git clone https://github.com/ESX-Org/esx_vehicleshop [esx]/esx_vehicleshop
```

### Manually
- Download https://github.com/ESX-Org/esx_vehicleshop/archive/master.zip
- Put it in the `[esx]` directory

## Installation
- Import `esx_vehicleshop.sql` in your database
- Add this in your `server.cfg`:

```
start esx_vehicleshop
```
- If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`

# Legal
### License
esx_vehicleshop - vehicle shop for ESX

Copyright (C) 2015-2018 Jérémie N'gadi

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
