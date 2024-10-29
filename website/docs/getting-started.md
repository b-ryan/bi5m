# Getting Started

## Step 1: Gather Supplies

Below, we will use `M` and `N` to represent the values you will be using for
your multisig strategy. For example, if you will be using a 3 of 5 multisig,
then `M = 3` and `N = 2`.

### Required

- Computers
    - Number needed: `N + 1`
    - One of the computers will be used to download the full Bitcoin
      blockchain. This process takes much less time when the computer has an
      SSD drive. It should also have at least 250 GB of space.
    - These computers do not need to be new or very powerful. In particular,
      the private key laptops are going to do very little. It's likely you or
      some friends may have old laptops lying around that you can repurpose.
      - _(We are also working on a lower-cost option that uses Raspberry Pi
        devices)_
    - It's recommended that you use computers from different manufacturers.
      However, they need to be able to run Linux, so Mac laptops will not
      work.
- USB thumb drives for backups and installing Linux
    - Number needed: `N + 2`
    - One of these will be used for installing Linux on your computers, so it
      needs at least 8GB of space. The others can be very small; under 1GB is
      fine.
    - **Buy new thumb drives, do not re-use old ones**
- Storage bags to keep computers and USB drives together
    - Number needed: `N + 1`
    - You need to make sure that each computer and its backup USB drive stay
      together. This can be done with some large envelopes, like
      [these][envelopes] or you could upgrade to laptop bags like [any of
      these][bags].
- Some way to put labels on everything. This could just be stickers and a
  sharpie or a label maker. I own a model similar to [this one][label maker]
  and find it useful around the house all the time.

Example supplies for a 3 of 5 multisig:

- 6 computers
- 7 USB thumb drives (1 with 8GB and 6 that can have less)
- 6 storage bags

It's possible to purchase each of these laptops for under $50 ([ebay search for
laptops under $50][ebay]), meaning you could get all of the above for around
$300-$350, maybe even less. Since 3 of 5 multisig is recommended when storing
more than $25,000, the investment here is well worth it.

[envelopes]: https://www.amazon.com/gp/product/B079XYRB4B/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8 "Envelopes"
[bags]: https://www.amazon.com/s?k=laptop+bags&i=office-products "Laptop Bags"
[ebay]: https://www.ebay.com/sch/i.html?_from=R40&_nkw=laptop&_sacat=0&rt=nc&_udhi=50 "Ebay search for laptops under $50"
[label maker]: https://www.amazon.com/Brother-P-touch-PTM95-Styles-Patterns/dp/B01GQHHYFE/ref=sr_1_6?sr=8-6 "Label maker"

### Optional

- Small Faraday bags for the USB drives
    - Number needed: `N + 1`
    - These provide an extra level of protection against things like solar
      flares, which could erase the data on your computer and the USB backup.
    - Some options can be found [here][faraday bags].

[faraday bags]: https://www.amazon.com/s?k=faraday+bag+for+usb+thumb+drive "Faraday bags on Amazon"

## Step 2: Label and Organize

Do the following:

For the 8 GB USB drive that is for installing Linux:

- Label it with `Linux`.

For the watch-only laptop:

- Label it with `Watch-Only`.
- Label one of the backup USB drives with the same label.
- Label one of the laptop envelopes / bags with the same label.
- Place the laptop and USB drive into the envelope / bag.

For each of the private key laptops:

- Label it with a name identifying the location where it will reside.
- Label one of the backup USB drives with the same label.
- Label one of the laptop envelopes / bags with the same label.
- Place the laptop and USB drive into the envelope / bag.

## Step 3: Install Ubuntu on the Watch-Only Laptop

- Always use the Long Term Support (LTS) version.
- [Here's a tutorial][ubuntu tutorial] for how to install it.

[ubuntu tutorial]: https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview "Tutorial for installing Ubuntu"

## Step 4: Install Bi5m on the Watch-Only Laptop

You will now switch over to the watch-only laptop. There, open `Firefox` by
clicking `Activities` on the top-left of the screen, then type in `firefox` and
click the icon, which will look like this:

![Firefox](/_images/firefox.png)

Then, type the following URL into Firefox in order to see the installation
instructions: [bi5m.com/install](https://bi5m.com/install)
