# Before Getting Started

Below we talk about things you need to consider before you get started using
Bi5m.

## Choosing Your Multisig Strategy

Bi5m can support any multisig strategy, it can even be for a single-sig wallet
with an airgapped signing device. As such, you need to decide what M of N
strategy to use, but we make the following recommendations based on how much
money you will be storing:

* Under $5,000: 1 of 2
* Under $25,000: 2 of 3
* More than $25,000: 3 of 5

Increasing the value of M (the number of signatures required for spending) can
lessen the chance of theft by making an attacker need to access more locations.
However, you may also need to increase N (the total number of keys), in order
to lessen the risk of loss, but in some ways this can make it easier to steal
again because there are more options available for an attacker to choose from.
Further, you need to physically secure more computers as you increase N.

## Number of Computers Required and Costs

There are three main criteria which you should consider before using this
project. Firstly, the number of computers required to maintain your multisig is
`N + 1`. Some examples:

multisig | number of private keys (N) | number of computers needed
-------- | -------------------------- | --------------------------
1 of 1   | 1                          | 2
1 of 2   | 2                          | 3
3 of 5   | 5                          | 6
4 of 5   | 5                          | 6

_(Notice that the M in the multisig strategy doesn't affect the number of
computers needed.)_

There is obviously a cost component to this: buying 6 used laptops to set up a
3 of 5 multisig, even if the computers are old, can run several hundred
dollars (more details about the requirements for the computers is given below).

## Physical Security

The second main criteria is that none of the private key computers may be
located in the same physical location.

Also, we recommend against password-protecting the computers, so that if you
pass away or forget the password, you do not lose your Bitcoin. Further, a
backup of the private keys will be stored on an unencrypted USB drive, which
would negate any benefit that password-protecting the computer would have.

Therefore, the computers must be physically secured. They should be kept in
safes or locked rooms, which cannot be accessed by unknown parties.

A final note: we don't want your Bitcoin to be lost if you pass away. The
locations should not be so hidden that, upon your untimely death, they are
unknown and lost to your inheritors.

Location ideas include:

- One in your home in a safe
- In safes in the homes of friends or family who'd you would trust with having
  full access to all your bank accounts and retirement funds.
- In a safe deposit box where no employee has any idea what you are storing in
  the box.

## Linux

A final criteria to consider is that this project requires you install a fresh
copy of Linux on each of the computers. This is not tremendously difficult, but
you may run into some speed bumps along the way. You will primarily need to be
able to search for help on the internet or ask a friend with Linux experience
to help.
