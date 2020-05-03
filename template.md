# MATLAB



## History of MATLAB

MATLAB is a programming language in which mathematical notation is used and algorithms and mathematical functions are developed.

MATLAB was not originally a programming language, its development began in the late 1970s.
> The person who started to develop was Cleve Moler.Cleve Moler's main goal in developing MATLAB was that his students could access EISPACK and LINPACK without needing to use Fortran.

MATLAB, which started to be developed for this purpose, became popular in the field of mathematics in a short time.Immediately after its popularity increased, engineer Jack Little and his friend Steve Bangert realized the mathematical potential of MATLAB and offered cooperation to Moler.After this solidarity, they re-encoded MATLAB in language C. And in 1984 they launched PC-MATLAB.


## Why was MATLAB invented?

As we mentioned above; MATLAB was developed to enable a teacher to reach LINPACK and EISPACK to their students without using any other programming language.


## When/why shall we use MATLAB?

MATLAB; It started like a simple calculator and went a long way.It is very common to use MATLAB especially in engineering applications. 
It is frequently used in the analysis of systems and in the visualization of mathematical calculations.MATLAB has a mathematical function library that can perform the calculation of linear algebra and matrices as a math product.

### The main areas use of MATLAB are:
* Numerical Linear Algebra Calculations
* Data Analysis and Visualization
* Creating Graphics for Big Data
* Algorithm Development
* Machine Learning
* Data Science
* Deep Learning
* Creating Graphical User Interface and Application Programming Interface
* Simulation


You can apply and design different algorithms using MATLAB.
By uploading data from different sources such as file, database or internet into MATLAB,you can analyze them or have them visualized with various options.
You can still simulate data models, prototypes and products you design or calculate with MATLAB.
You can also design interfaces for users and even MATLAB to work with other programming applications more easily.


## How to setup an environment to use it in different platforms?
You can choose different operating systems to use MATLAB. You can install and fully use the matlab environment in the 3 most popular operating systems below;
1. Windows
2. MacOS
3. Linux

> Some universities provide free access to MATLAB for their students to use.

### Matlab Environment Setup:
**If you want all downloads independent of the operating system to be original, you need to open an account on the official Matlab website**
* For Windows:
  * Firstly you should visit the [Official Website](https://www.mathworks.com/downloads/web_downloads/?s_iid=hp_ff_t_downloads) for MATLAB and you should download the most suitable version to your PC.
  * After the download of the suitable installation file is completed. The downloaded .exe is run and environment installation is provided.
* For MacOS :
  * Download the original setup file from the official Matlab website, 
  * Enter license key information or user account information.
  * Select the folder where the Matlab Environment will be installed.
  * Wait for the setup is completed.
  * You can check this video for visualize Instructions [HERE](https://www.youtube.com/watch?v=fMS2pu015WI)
* For Linux : 
  * After the installation downloaded from the official website as described in the above sections, the following steps are applied to start the application in the linux system.
  * To start MATLAB on Linux platforms, type matlab at the operating system prompt. If you did not set up symbolic links in the installation procedure, then type matlabroot/bin/matlab. matlabroot is the name of the folder in which you installed MATLAB. To see the folder, type matlabroot.
  * Check [documentation](https://www.mathworks.com/help/matlab/matlab_env/start-matlab-on-linux-platforms.html#responsive_offcanvas) for more

## Example Codes:

* **Create Functions in Files:**

  ```matlab
  function f = fact(n)
      f = prod(1:n);
  end
  
  x = 5;
  y = fact(5)
  ```
  y = 120
* **Matrices and Arrays:**
  * Array Creation
      ```matlab
      a = [1 2 3 4]
      ```
      a = 1×4

      1     2     3     4
      
  * Create Zeros Matrix
      ```matlab
      z = zeros(5,1)
      ```
* **Plotting Expressions:**
  ```matlab
  fplot(@(x) sin(x))
  ```
  ![Plotting Graph](https://www.mathworks.com/help/examples/graphics/win64/PlotExpressionExample_01.png)
  
## Things That Are Specific To This Language (Cool Matlab Features and Unusual Use Of Matlab Functions):
* Based on Matlab, large-scale simulations can be processed.
* Image Processing can be done on videos and images using 'Simulink'.
* Graphs can be plotted on large scale datasets.
* Due to its extensive documentation and community, Matlab is a preferred distribution in many Scientific platforms and research-development environments.



