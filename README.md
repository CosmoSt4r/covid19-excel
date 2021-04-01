# Get COVID-19 Reports
______________________

![Homepage](https://github.com/CosmoSt4r/covid19-excel/blob/master/static/Homepage.png?raw=true)

______________________

## How to use?

Enter the **country** you want to get report for. Choose the **period of time** by clicking
on the date inputs.
<br><br>
By default you will get **Excel** report in `.xlsx` format. But you can also import report as **CSV**
or include **charts** in **Excel** report by clicking on checkboxes.
<br><br>
**Note**: You can't import as CSV with charts.

______________________ 

## How to install?

### Clone

Clone this repo to your local machine using `git clone https://github.com/CosmoSt4r/covid19-excel`

### Required packages

To start the server you need the following packages: 

 - certifi
 - chardet
 - et-xmlfile
 - idna
 - jdcal
 - openpyxl
 - requests
 - urllib3
 - flask

To install packages:

```py
cd covid19-excel
pip install -r requirements.txt
```

### Starting the server

```py
python server.py
```
> or just open `server.py`

### Opening app in browser

Open your browser and go to the `127.0.0.1:5000` address. You will see the main page.

## Credits

This is just a fork of original [repo](https://github.com/AlexNickrodef/covid19-excel) 
created by [AlexNickrodef](https://github.com/AlexNickrodef).

Thanks to W.S.Toh and his [blog](https://code-boxx.com/) 
for free to use pretty [date picker](https://code-boxx.com/simple-datepicker-pure-javascript-css/).

This project works using Coronavirus Data [API](https://covid19tracking.narrativa.com/index_en.html)
 by [Narrativa](https://www.narrativa.com/es/inicio/).
