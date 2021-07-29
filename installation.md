# Installation

Neural Studio requires Tensorflow&gt;=2.2.0 to work. Other dependencies are as following.

* OpenCV
* Numpy
* Pandas
* Matplotlib
* Pyrex
* Scikit-learn
* Psutil
* GPUtil

{% hint style="warning" %}
Check for dependency version conflicts before installing neural studio.
{% endhint %}

#### Install From PyPi

```bash
pip install neural-studio
```

#### Build from source

{% hint style="info" %}
To build from source you need to install following list of dependencies.
{% endhint %}

1. NodeJS 
2. Python &gt;= 3.6
3. CUDA &gt;= 10.2 \( Optional for GPU support \)
4. Tensorflow &gt;= 2.2.0 

```bash
git clone https://github.com/monjoybme/Neural-Studio
cd Neural-Studio
pip install -r requirements.txt
cd html
npm install 
cd ..
./build.sh    
```

This will create wheel\(.whl\) file for current release which you can install by running following commands. 

```bash
cd dist
pip installl neural_studio-x.y.z-py3-none-any.whl
```

