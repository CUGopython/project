
![cover_small](https://user-images.githubusercontent.com/44420637/49211320-4f3aec00-f38d-11e8-8d3f-85a5c9d6a84a.jpg)
# Web Crawling Project

Our project consists of two parts. Both are based on Python. 

In the first part, we obtained thousands of Columbia University images by an image crawler and then merged these images to create a image above using a software called "Foto-Mosaik-Edda". 

In the second part, We collected data from quant programs using web scrapping from https://quantnet.com/tracker/
and built an interface to display our results. 
Selecting different program, user can know about basic academic information including average GRE test scores, average GPA, and admission rate.


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
```

```
Software:
Foto-Mosaik-Edda
```

Installing


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
go to 'https://fmedda.com/en/download' to download and install Foto-Mosaik-Edda for your computer

```

End with an example of getting some data out of the system or using it for a little demo

## Run Instructions


```
First Part--Image crawler project
1.Run 'Download_images_whole.ipynb', you will have have a file img which contains all the images
2.Download Foto-Mosaik-Edda from website and install it.
3.Open Foto-Mosaik-Edda and follow the instructions,use all the images which download from websites 
as input, and you will get a picture of Butler Library. 

```

```
Second Part--Student information of Quantnet
1.Run 'quantnet_get_data_and_output_csv.ipynb' to get student information in 5 csv files: title.csv,
date.csv, type.csv, score.csv and status.csv. 

**Important: Since QuantNet is continually update its statistis,***
***in order to run Third Part and Fourth Part correctly, please use our 5 csv files on github***
```

```
Third Part--Data Cleaning and Functions
1. Run 'data_clean_final' to combine five csv files and do data cleaning.
2. In this process, we standardized GPA scores and GRE scores(data cleaning part).
3. Also we caculated the acceptance rate,GRE mean scores, and mean GPA.
4  You will get get 'Rate.csv' , 'cleandata.csv' and 'Number.csv' as your results.
```

```
Fourth Part--Build an interface to displace our result
1. Run 'tkinter.ipynb' to build a GUI system. 
2. In the system, clicking different programs, user can check quant program academic requirements.
```


## Authors : Go Python Section 2

* **Jian Huang** - [jh4025](https://github.com/jh4025)
* **Mengtao Li**  - [mengtaoli11](https://github.com/mengtaoli11)
* **Siq Li** -  [SiqiCU](https://github.com/SiqiCU)
* **Rui Liu**  - [CUliurui](https://github.com/CUliurui)


## Acknowledgments

* Free online Python courses
* Inspiration

