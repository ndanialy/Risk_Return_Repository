# Risk_Return_Repository

An application for analyzing investments to calculate risk, return, and beta statistics in order to determine which one to add to a portfolio.

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [pathlib](https://docs.python.org/3/library/pathlib.html) for the path functions to locate the csv files.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [matplotlib](https://docs.python.org/3/library/pathlib.html) for the data visualization.

---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab
```
---

## Usage

The App imports and cleans the investment data from the csv before visualizing the data for the daily returns over the time period:

![daily return data](https://user-images.githubusercontent.com/96391748/151107914-67a15890-9311-4c21-852f-d498107b502b.PNG)

In addition, it creates a graph comparing the cumulative returns of the investments over the time period:

![cumulative returns](https://user-images.githubusercontent.com/96391748/151108040-5cacb41c-5467-4d5b-af4f-d498d20c9e76.PNG)

The app also calculates and visualizes the risk of the different investments through the standard deviation:

![risk](https://user-images.githubusercontent.com/96391748/151108183-fc6adfa6-0f20-465c-8000-86a37ee6100e.PNG)

It calculates the sharpe ratio and displays them as a bar graph:

![sharpe ratio](https://user-images.githubusercontent.com/96391748/151108302-37538734-5022-42cd-b77b-5d8e089c24a4.PNG)

Finally, the rolling betas are calculated and visualized:

![rolling beta](https://user-images.githubusercontent.com/96391748/151108403-4334160e-90fa-4842-88f1-720b1cd4d66a.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
