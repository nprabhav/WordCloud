# WorldCloud
[![forthebadge](http://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.png?v=103)](https://opensource.org/licenses/mit-license.php)

It creates a WordCloud image of given query.

 ## Usage

 ```sh
 bash run.sh
 sudo python3 create_wordcloud.py [Query]

 ```
 You don't need to really install anything. `run.sh` takes care of everything. Really.

 How to use?
-----------
If you wish to install manually, follow this process.

To use, it is recommended to make `virtualenv` and then install all required packages:

* Installing virtualenv:
```
$ sudo pip install virtualenv
```
* Making virtualenv:
```
$ virtualenv venv
```
* Go to your dir and activate it:
```
$ . venv/bin/activate
```
* To install all required packages:
 ```
 $ pip install -r requirements.txt
 or
 $ sudo pip install -r requirements.txt
```
* Run the application:
```
sudo python3 create_wordcloud.py [Query]
```


 ## Tools and Technologies Used
 ```
 beautifulsoup4==4.7.1
 certifi==2018.11.29
 chardet==3.0.4
 cycler==0.10.0
 idna==2.8
 kiwisolver==1.0.1
 matplotlib==3.0.2
 numpy==1.16.1
 Pillow==5.4.1
 pyparsing==2.3.1
 python-dateutil==2.8.0
 requests==2.21.0
 six==1.12.0
 soupsieve==1.8
 urllib3==1.24.1
 wikipedia==1.4.0
 wordcloud==1.5.0

```

 ## Description
 A word cloud is an image made of words that together resemble a cloudy shape.
 The size of a word shows how important it is e.g. how often it appears in a text — its frequency.

 People typically use word clouds to easily produce a summary of large documents (reports, speeches), to create art on a topic (gifts, displays) or to visualise data (tables, surveys).

 ## Convenient screenshot


<img src="https://github.com/nprabhav/WordCloud/blob/master/images/wc.png" width="450">


 ## Contributing

 Your contributions are always welcome :smile: ! Please have a look at the [contribution guidelines](CONTRIBUTING.md) first.

 Before working on an issue / feature, it is **crucial** that you're assigned the task on a GitHub issue.
 * If a relevant issue already exists, discuss on the issue and get yourself assigned on GitHub.
 * If no relevant issue exists, open a new issue and get it assigned to yourself on GitHub.
 Please proceed with a Pull Request only after you're assigned. It'd be a waste of your time as well as ours if you have not contacted us before hand when working on some feature / issue.


 ## License
 The MIT License (MIT) 2019 - [Prabhav Nalhe](https://github.com/nprabhav).
 Please have a look at the [LICENSE](LICENSE) for more details.
