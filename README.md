# What is Minergate-cli?

Minergate-cli is the console miner provided by [MinerGate](http://rebrand.ly/minergate).

MinerGate is a mining pool created by a group of cryptocoin enthusiast.

User-friendly miner supports Bytecoin, Monero, Quazarcoin, Litecoin, DarkNote, Fantomcoin, MonetaVerde, Aeon coin, Dashcoin and Infinium-8.

![logo](https://scontent.cdninstagram.com/t51.2885-19/s150x150/11939576_895926810497744_2081713499_a.jpg)

# How to use this image

Run in background:

```console
$ docker run -d --name some-minergate-cli minecoins/minergate-cli -user kamihicouki@gmail.com -fcn+xmr
```

Get minergate-cli options with:

```console
$ docker run --rm minecoins/minergate-cli -help
```

Fetch logs of a container:

```console
$ docker logs some-minergate-cli
```

# Donations
