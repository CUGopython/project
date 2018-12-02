
![cover_small](https://user-images.githubusercontent.com/44420637/49211320-4f3aec00-f38d-11e8-8d3f-85a5c9d6a84a.jpg)
# Web Crawling Project

Our project consists of 2 parts, both based on Python. In the first part, we obtain thousands of Columbia University images by crawler and then merge these images to create a mosaic image using a software called "Foto-Mosaik-Edda".  In the second part, we make a GUI system for searching quant programs information. We get the quant programs information by crawler and make it a GUI system by tkinter and matplotlib. In this GUI, user can input a program name and the system will return a graph and some text information. In the graph, user will see historical applicants amounts and acceptance rates; in the text information, user will see applicants' mean scores, like GPA and GRE test results. We hope our project can help users to have intuition about quant programs' admission standards. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installation instructions
Requirements



```
Python packages: 
requests
bs4 
os
pandas
csv
datetime
numpy
matplotlib
tkinter 

Software:
Foto-Mosaik-Edda
```

### Installing

A step by step series of examples that tell you how to get a development env running

The step of installing packages will be

```
pip install requests
pip install bs4
pip install pandas
pip install csv
pip install numpy
pip install matplotlib
```
The step of installing software will be:
```
go to 'https://fmedda.com/en/download' to download a suitable version of Foto-Mosaik-Edda for your computer, windows or Mac OS X and then install it.
```

End with an example of getting some data out of the system or using it for a little demo

## Run Instructions


```
first part--image crawler project
1.run 'Download_images_whole.ipynb' to get all images by crawler.
2.download Foto-Mosaik-Edda from website and install it.
3.Open Foto-Mosaik-Edda, click 'Create/edit database', then click 'add pictures -- to a new database', then choose 'img' folder, which includes 3 subfolders, columbia, columbia2 and columbia3. Here please click all 3 boxes 'Include subfolders', 'Include hidden and system files', 'Synchronize found pictures with database'. Then click 'Run'. Then click 'Beginning'.
4.click 'Create photo mosaic', then choose 'Classic style photo mosaic'. Click 'next'. Then click 'Open', use our 'target_picture.png' as theme picture. Then click 'Save' to save your mosaic picture in a suitable place. Click 'Next' and choose database in step 3. Click 'Next', 'Next', 'Next' and 'Run'. Now you get result of our image project. We name it 'project_cover.jpg' and save it in repo.
```


## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors : Go Python Section 2

* **Jian Huang** - *Initial work* - [jh4025](https://github.com/jh4025)
* **Mengtao Li** - *Initial work* - [mengtaoli11](https://github.com/mengtaoli11)
* **Siq Li** - *sl4438* - [SiqiCU](https://github.com/SiqiCU)
* **Rui Liu** - *Initial work* - [CUliurui](https://github.com/CUliurui)


## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
