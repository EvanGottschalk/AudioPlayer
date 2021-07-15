[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/EvanGottschalk/AudioPlayer">
    <img src="logo.png" alt="Logo" width="151" height="80">
  </a>

  <h3 align="center">AudioPlayer</h3>

  <p align="center">
    A simple program for adding sound effects to other programs
    <br />
    <a href="https://github.com/EvanGottschalk/AudioPlayer"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/EvanGottschalk/AudioPlayer">View Demo</a>
    ·
    <a href="https://github.com/EvanGottschalk/AudioPlayer/issues">Report Bug</a>
    ·
    <a href="https://github.com/EvanGottschalk/AudioPlayer/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)


### Built With

`Python`


<!-- GETTING STARTED -->
## Getting Started

Start by downloading `AudioPlayer.py`. You will also need to create a folder in the same directory called `_Python_SFX`. That's where you will store your `.mp3` files.

### Prerequisites

In addition to downloading `AudioPlayer.py` and creating a `_Python_SFX` folder, you will also need to download your own sound effects files. These should be `.mp3` files with descriptive names. Store them in your `_Python_SFX` folder.

### Installation

1. Download `AudioPlayer.py`

2. Create a folder in the same directory as `AudioPlayer.py` called `_Python_SFX`

3. **Legally** find `.mp3` files of your choosing online, or create your own. Store them in your `_Python_SFX` folder and add their names to `AudioPlayer.py`

4. That's it! You can now call `AudioPlayer` in other programs to add sound effects to them!


<!-- USAGE EXAMPLES -->
## Usage

While `AudioPlayer` can be used for any audio in any context, one of the handiest and simplest ways to use it is as an alert. For example, if one is running a loop that checks prices, `AudioPlayer` could be used as an audio alert if the `price` variable drops below a certain `threshold` value.

Example:
```sh
...
if price < threshold:
    AudioPlayer.playSound('Navi Hey')
...
```


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/EvanGottschalk/AudioPlayer/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@Fort1Evan](https://twitter.com/Fort1Evan) - magnus5557@gmail.com

Project Link: [https://github.com/EvanGottschalk/AudioPlayer](https://github.com/EvanGottschalk/AudioPlayer)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

Thinking about contributing to this project? Please do! Your Github username will then appear here.




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/EvanGottschalk/AudioPlayer.svg?style=for-the-badge
[contributors-url]: https://github.com/EvanGottschalk/AudioPlayer/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/EvanGottschalk/AudioPlayer.svg?style=for-the-badge
[forks-url]: https://github.com/EvanGottschalk/AudioPlayer/network/members
[stars-shield]: https://img.shields.io/github/stars/EvanGottschalk/AudioPlayer.svg?style=for-the-badge
[stars-url]: https://github.com/EvanGottschalk/AudioPlayer/stargazers
[issues-shield]: https://img.shields.io/github/issues/EvanGottschalk/AudioPlayer.svg?style=for-the-badge
[issues-url]: https://github.com/EvanGottschalk/AudioPlayer/issues
[license-shield]: https://img.shields.io/github/license/EvanGottschalk/AudioPlayer.svg?style=for-the-badge
[license-url]: https://github.com/EvanGottschalk/AudioPlayer/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/EvanGottschalk
