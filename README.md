Installation for Anaconda
--------------

* Open a command shell
* Type the following to install the first dependencies:
  ```shell
  conda install numpy scipy vtk
  ```
  Then choose "y".
* Install the last dependency like this:
  ```shell
  easy_install btk
  ```
* Proceed with the installation of *PyBiomech*:
  ```shell
  pip install PyBiomech --no-deps
  ```
* To verify than everything went ok, type:
  ```shell
  python
  ```
  and then import the library:
  ```py
  >>> import PyBiomech
  ```
  If no error occurs, then you have correctly installed it!
