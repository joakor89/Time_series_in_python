# Time Series Forecasting with Python

The field of Data Science, although seemingly complex, is in essence an exploration of information and the patterns within.

Data science encompasses various methods and theories drawn from many fields within the context of mathematics, statistics, and computer science. This repository is devoted to a deeper understanding of Time Series Forecasting, particularly for Data Science and Machine Learning, with exercises and solutions from the well-regarded book "Time Series Forecasting in Python" (Marco Peixeiro, 2022).

The primary aim of this repository is to provide an accessible yet comprehensive resource to those embarking on their journey in the field of data science. The repository will provide explanations, solutions, and insights into the numerous exercises contained within the aforementioned book.

## Content Review:
Section 1: (Time Waits for no one: Bird's-eye view of time series, differences with other regression tasks, naive prediction& random walk  )

Section 2: (Forecasting with Statistical Models: moving avg process, autogressive process, modeling complex time series)

Section 3: (Large-Scale Forecasting with Deep Learning: Data windowing, baby steps in D.L, filtering with CNN, using predictions to make more predictions)

Section 4: (Automating Forecasting at Sacale: Automating with Prophet)

## Usage and Contribution

This repository is open for all to use and learn from. However, keep in mind that this repository is meant to be a supplement to your learning and not a substitute for the book itself.

If you wish to contribute to this repository, please feel free to open a pull request. Let's cultivate a collaborative space where knowledge can be shared and gained.

#### Note:
As this repository strictly serves an educational purpose, it abides by the guidelines set forth regarding fair use. 
It does not aim to infringe upon any copyrights held by the author or the publisher.

## Citation:
Peixeiro M. (2022).  Time Series Forecasting in Python. Manning  ISBN 978-1-61729-988-9

Remember: "It's for the ultimate end of science."

## Disclaimer
This repository is unofficial and not affiliated, endorsed or certified by Marco Peixeiro - Time Series Forecasting in Python.
It has been created for educational purposes, and the repository owner is not responsible for any incorrect information or misuse.

Your journey in the exciting world of data science begins here. Dive in, explore, and let's learn together.

### Important Update for Time Series Analysis using Prophet
For those delving into the state-of-the-art methodologies in time series analysis, it is crucial to note
that the installation process for the Prophet library, originally developed by Facebook, 
has undergone significant updates. While the prior approach to installation involved the use of pip install 
fbprophet==0.7.1, this method has been deprecated due to evolving dependencies and enhancements in the library's architecture.

As of the current landscape, the library has been transitioned to prophet==1.1.5. This iteration marks a substantial leap forward, incorporating advanced features and optimizations that reflect the latest research and best practices in the field of time series forecasting.

It is imperative for data scientists and researchers cloning this repository to utilize the updated installation command:

##### Library
```sh
pip install prophet==1.1.5
```

This ensures compatibility with the most current methodologies and leverages the full potential of Prophet for predictive analytics.
The transition to this version addresses prior installation issues and sets the stage for more robust and accurate time series modeling.

# Virtual Environment
```sh
pip install --upgrade pip
python3 -m pip install virtualenv
python3 -m venv env
source env/bin/activate
source env/bin/deactivate
pip3 install -r requirements.txt
```

# Github Environment

Performed from Terminal Console
```sh
1. git init
2. git remote add origin ["copy here ssh or https"]
3. git remote -v
4. git add -A
5. git add .
6. git commit -m "insert here your commit"
7. git status
8. git push origin master
```

### Additional GitHub Commands
if you already created your repository, then:
```sh
1. git remote add origin ["copy here ssh or https"] 
2. same procedure applied above
3. Note: if you already got your ReadMe.md & License.md then,
firstly request your git pull origin master. THIS IS ALWAYS A RECOMMENDED PRACTICE.
4. git push origin master
```
