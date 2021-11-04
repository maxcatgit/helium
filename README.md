# helium

https://danielandrade.net/2020/08/23/running-a-helium-miner-on-digitalocean/

https://danielandrade.net/2020/09/28/adding-a-diy-hotspot-to-the-helium-blockchain/

https://docs.helium.com/mine-hnt/full-hotspots/become-a-maker/hotspot-integration-testing/

https://docs.helium.com/mine-hnt/full-hotspots

Helium RAK Miner review - https://www.disk91.com/2021/technology/lora/helium-rak-miner-review/

RAK Miner V2 SDcard replacement - https://shop.parleylabs.com/products/sandisk-64gb-extreme-microsdxc-with-helium-firmware

RaspberyPI Bluethooth - https://pimylifeup.com/raspberry-pi-ibeacon/

Hotspot WiFi Configuration - https://docs.helium.com/mine-hnt/full-hotspots/become-a-maker/hotspot-wifi-configuration/

------------
We had to get an alpha code that is placed into your assertion commands below. They were added using the HostOS terminal on the Balena Cloud.

docker exec miner miner txn add_gateway owner=YOURWALLET --payer 14fzfjFcHpDR1rTH8BNPvSi5dKBbgxaDnmsVPbCjuq9ENjpZbxh

helium-wallet --format json onboard ADD_GW_MINER_OUTPUT --onboarding CODE --commit

docker exec miner miner txn assert_location owner=YOURWALLET location=LAT,LON --payer 14fzfjFcHpDR1rTH8BNPvSi5dKBbgxaDnmsVPbCjuq9ENjpZbxh

helium-wallet --format json onboard ASSERT_GW_MINER_OUTPUT --onboarding CODE --commit
--------------
