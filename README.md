# Shipper
An easy to use, shipping processing library for Laravel!

## Features

 - **Send** cargo info to shipper company.
 - **Check** cargo status with tracking number.
 - **Cancel** shippment with tracking number.
 - **Log** sended shipments to database.
 - Test it with companies **sandbox**.
 - Send Ship Request with **Laravel Queue**

## Integrated Shipping Companies
All shipper package  must implement ShipperContract.

The following shippers are available:

Shipper | 1.x | Composer Package | Maintainer
--- | --- | --- | ---
[mng](https://github.com/herkod/shipper-mng) | ✓ | herkod/shipper-mng | [Herkod/Shipper](https://github.com/herkod)
[aras](https://github.com/herkod/shipper-aras) | ✓ | herkod/shipper-aras | [Herkod/Shipper](https://github.com/herkod)
[surat](https://github.com/herkod/shipper-surat) | ✓ | herkod/shipper-surat | [Herkod/Shipper](https://github.com/herkod)
[ptt](https://github.com/herkod/shipper-ptt) | ✓ | herkod/shipper-ptt | [Herkod/Shipper](https://github.com/herkod)
[yurtici](https://github.com/herkod/shipper-yurtici) | ✓ | herkod/shipper-yurtici | [Herkod/Shipper](https://github.com/herkod)
