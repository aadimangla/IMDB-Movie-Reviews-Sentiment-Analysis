[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]](https://github.com/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis/issues)
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
<!--   <a href="">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

  <h3 align="center">IMDB Movie Reviws Sentiment Analysis</h3>

  <p align="center">
    <!-- An awesome README template to jumpstart your projects! -->
    <br />
<!--     <a href=""><strong>Explore the docs »</strong></a> -->
    <br />
    <br />
    <!--<a href="">View Demo</a>
    ·
    <a href="">Report Bug</a>
    · -->
    <a href="https://github.com/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [How to Train ?](#How-to-Train-?)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](images/product.png)

It analyses the movie review entered by a user for any specific movie and analyses what is the sentiment of the review. It helps the companies rate the movie and understand crowd sentiment regarding it. Sentiment analysis is a natural language processing problem where text is understood and the underlying intent is predicted. Sentiment analysis, also called opinion mining, is the field of study that analyzes people’s opinions, sentiments, evaluations, appraisals, attitudes, and emotions towards entities such as products, services, organizations, individuals, issues, events, topics, and their attributes

Here's why:
* Sentiment analysis has long been a problem for business, marketing and management areas for more
value earned in the decision process
* Sentiment Analysis also helps organisations measure the ROI of their marketing campaigns and improve their customer service.
* Since sentiment analysis gives the organisations a sneak peek into their customer’s emotions, they can be aware of any crisis that’s to come well in time – and manage it accordingly.

The dataset is the [arge Movie Review Dataset](http://ai.stanford.edu/~amaas/data/sentiment/) often referred to as the IMDB dataset.

The Large Movie Review Dataset (often referred to as the IMDB dataset) contains 25,000 highly polar moving reviews (good or bad) for training and the same amount again for testing. The problem is to determine whether a given moving review has a positive or negative sentiment.

The data was collected by Stanford researchers and was used in a 2011 paper [PDF](http://ai.stanford.edu/~amaas/papers/wvSent_acl2011.pdf) where a split of 50/50 of the data was used for training and test.
### Built With
This chatbot was build using following frameworks, libraries and softwares.
* [RASA](https://rasa.com/)
* [Spacy](https://spacy.io/)
* [NLTK](https://www.nltk.org/)



<!-- GETTING STARTED -->
## Getting Started

To run this project you need to follow the following steps.

### Prerequisites

These are the prerequisites you need to build this bot as well as run it.

```sh
$ pip3 install  rasa==1.10.8
$ pip3 install rasa[spacy]
$ python -m spacy download en_core_web_md
$ python -m spacy link en_core_web_md en
$ pip3 install  pandas==1.1.0
$ pip3 install  nltk==3.5
$ pip3 install fuzzywuzzy==0.18.0
```
#### Extra SETUP
- Create conda environment and create project in this environment
- After installing requirements in above Modules LIST
- To add custom component to rasa
    -   Add current working directory of this project in your python environment variable      -   eg: PATH = D:\Projects\...\Restaurant-Bot-Automation
- To set the console channel Timeout in seconds
    -  Go to Anaconda3\envs\{your_rasa_env}\Lib\site-packages\rasa\core\channels\console.py
    -  And set DEFAULT_STREAM_READING_TIMEOUT_IN_SECONDS=200 

#### How to Train ?
- ##### To use default Rasa configs
```sh
$ rasa train
```
- ##### To use spacy config pipeline (Fast to train)
```sh
$ rasa train -c spacy_config.yml
```

#### How to run 
- ##### To run action server
```sh
$ rasa run actions --actions actionserver.actions
```
- ##### To run rasa in debug mode to inspect slot filling and entities ..,
```sh
$ rasa shell --debug
```
- ##### To run rasa in normal shell
```sh
$ rasa shell
```



<!-- USAGE EXAMPLES -->
## Usage

IBM estimates that 265 billion customer support tickets and calls are made globally every year, resulting in $1.3 trillion in customer service costs. IBM also referenced a Chatbots Magazine figure purporting that implementing customer service AI solutions, such as chatbots, into service workflows can reduce a business’ spend on customer service by 30 percent.
Here are the key areas for how customer service chatbots help businesses to deliver better support.

* Deliver instant customer support
* 24×7 availability
* Deliver seamless hybrid support along with live chat 
* Easy scalability
* Reduce your cost of customer support with bots
* Reduce support tickets
* Collect customer feedback & information
* Automate your social media support
* Minimize IVR frustrations
* Better chatbot support = higher customer happiness!!

_For more examples, please refer to the [Article](https://chatbotsmagazine.com/top-5-benefits-with-using-chatbots-for-your-business-159a0cee7d8a)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis/issues) for a list of proposed features (and known issues).



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

Aditya Mangla - [@aadimangla](https://twitter.com/aadimangla) - aadimangla@gmail.com - [adityamangla.com](http://www.adityamangla.com/index.html)

Project Link: [https://github.com/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis](https://github.com/aadimangla/Rasa-Chatbot)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [RASA](https://rasa.com/)
* [RASA Forums](https://forum.rasa.com/)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis.svg?style=flat-square
[contributors-url]: https://github.com/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis.svg?style=flat-square
[forks-url]: https://github.com/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis/network/members
[stars-shield]: https://img.shields.io/github/stars/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis.svg?style=flat-square
[stars-url]: https://github.com/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis/stargazers
[issues-shield]: https://img.shields.io/github/issues/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis.svg?style=flat-square
[issues-url]: https://github.com/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis/issues
[license-shield]: https://img.shields.io/github/license/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis.svg?style=flat-square
[license-url]: https://github.com/aadimangla/IMDB-Movie-Reviews-Sentiment-Analysis/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/aadimangla
[product-screenshot]: images/screenshot.png
