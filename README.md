## Automated testcases for CareApp Android Mobile

<Some details>

### Environment Setup

1. Global Dependencies
    * [Install Python](https://www.python.org/downloads/)
    * Or Install Python with [Homebrew](http://brew.sh/)
    ```
    $ brew install python
    ```
    * Install [pip](https://pip.pypa.io/en/stable/installing/) for package installation
    * Install [Android SDK](https://developer.android.com/studio/index.html)
    * Install [Appium](https://github.com/appium/appium/blob/master/docs/en/about-appium/getting-started.md)

2. Project
	* The recommended way to run your tests would be in [virtualenv](https://virtualenv.readthedocs.org/en/latest/). It will isolate the build from other setups you may have running and ensure that the tests run with the specified versions of the modules specified in the requirements.txt file.
	```$ pip install virtualenv```
	* Create a virtual environment in your project folder the environment name is arbitrary.
	```$ virtualenv venv```
	* Activate the environment:
	```$ source venv/bin/activate```
	* Install the required packages:
	```$ pip install -r requirements.txt```
    
3. Android Devices
	* Use the android studio to make virtual devices and add details to the base_test.py file
	* For testing on hardware devices, add the details to the base_test.py file

### Running Tests: -s to disable output capture.

Tests in Parallel:
```$ py.test -s src/```

### Advice/Troubleshooting

<some details>

### Known Issues: