
<h1 align="center">
  <br>
  <a href="https://github.com/s0md3v/Photon"><img src="https://image.ibb.co/h5OZAK/photonsmall.png" alt="Photon"></a>
  <br>
  Photon
  <br>
</h1>

<h4 align="center">Incredibly fast crawler designed for OSINT.</h4>

<p align="center">
  <a href="https://github.com/s0md3v/Photon/releases">
    <img src="https://img.shields.io/github/release/s0md3v/Photon.svg">
  </a>
  <a href="https://pypi.org/project/photon/">
    <img src="https://img.shields.io/badge/pypi-@photon-red.svg?style=style=flat-square"
         alt="pypi">
  </a>
  <a href="https://github.com/s0md3v/Photon/issues?q=is%3Aissue+is%3Aclosed">
      <img src="https://img.shields.io/github/issues-closed-raw/s0md3v/Photon.svg">
  </a>
  <a href="https://github.com/s0md3v/Photon/commits/master">
    <img src="https://img.shields.io/travis/com/s0md3v/Photon.svg">
  </a>
</p>

![demo](https://image.ibb.co/kQSUcz/demo.png)

## Key Features

#### Data Extraction
Photon can extract the following data while crawling:

- URLs (in-scope & out-of-scope)
- URLs with parameters (`example.com/gallery.php?id=2`)
- Intel (emails, social media accounts, amazon buckets etc.)
- Files (pdf, png, xml etc.)
- Secret keys (auth/API keys & hashes)
- JavaScript files & Endpoints present in them
- Strings matching custom regex pattern
- Subdomains & DNS related data

The extracted information is saved in an organized manner.\
![save demo](https://image.ibb.co/dS1BqK/carbon_2.png)

#### Flexible
Control timeout, delay, add seeds, exclude URLs matching a regex pattern and other cool stuff.
The extensive range of [options](https://github.com/s0md3v/Photon/wiki/Usage) provided by Photon lets you crawl the web exactly the way you want.\

#### Genius
Photon's smart thread management & refined logic gives you top notch performance.\
Still, crawling can be resource intensive but Photon has some tricks up it's sleeves. You can fetch URLs archived by [archive.org](https://archive.org/) to be used as seeds by using `--wayback` option.\
In Ninja Mode, 3 online services are used to make requests to the target on your behalf.\
So basically, now you have 4 clients making requests to the same server simultaneously which gives you a speed boost if you have a slow connection, minimizes the risk of connection reset as well as delays requests from a single client.

#### Plugins
- **[wayback](https://github.com/s0md3v/Photon/wiki/Usage#use-urls-from-archiveorg-as-seeds)**
- **[dnsdumpster](https://github.com/s0md3v/Photon/wiki/Usage#dumping-dns-data)**
- **[Exporter](https://github.com/s0md3v/Photon/wiki/Usage#export-formatted-result)**

#### Frequent & Seamless Updates
Photon is under heavy development and updates for fixing bugs. optimizing performance & new features are being rolled regularly.

If you would like to see features and issues that are being worked on, you can do that on [Development](https://github.com/s0md3v/Photon/projects/1) project board.

Updates can be installed & checked for with the `--update` option. Photon has seamless update capabilities which means you can update Photon without losing any of your saved data.

### Contribution & License
You can contribute in following ways:

- Report bugs
- Develop plugins
- Add more "APIs" for ninja mode
- Give suggestions to make it better
- Fix issues & submit a pull request

Please read the [guidelines](https://github.com/s0md3v/Photon/wiki/Guidelines) before submitting a pull request or issue.

Do you want to have a conversation in private? Hit me up on my [twitter](https://twitter.com/s0md3v/), inbox is open :)

**Photon** is licensed under [GPL v3.0 license](https://www.gnu.org/licenses/gpl-3.0.en.html)
