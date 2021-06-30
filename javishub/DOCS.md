# Javis Addons: JAVIS DUSUN HUB

## Installation

Follow these steps to get the add-on installed on your system:

1. Navigate in your Home Assistant frontend to **Supervisor** -> **Add-on Store**.
2. Find the "JAVIS DUSUN_HUB" add-on and click it or choose to "Reload" if you don't see Javis HC
3. Click on the "INSTALL" button.

## How to use

In tab Configuration set your config:
_With Javis HC ip is 192.168.x.x Username password of mqtt are "javis" and "javis2020" you need to configure the following:_

```yaml
data_path: /share/dusun
mqtt:
  server: 192.168.x.x
  port: 1883
  username: javis
  password: javis2020

```

## Known issues and limitations

- This add-on can only be used via Ingress and has no direct access.

## Support

Got some problem?

You have several options to get them answered, contact us:

- https://nhathongminh.io/
- https://www.facebook.com/nhathongminh.io/

## Store

If you are interested in our products, 
shop at:
- https://shopee.vn/chinhnd82
