# new_project

## Python Virtual Environment

### How to Create venv
- We will be using `cmd` command prompt to create our venv.
- Lets understand with an example.
  #### For example:
- Open `cmd` get into desired dir.
- Lets create a folder in d drive which will contain all our python venvs
  ```
  d:\md myenvs
  ```
- Now, we have created our env folder which will contain all our venvs, moving on, will get into the folder
  ```
  d:\cd myenvs
  ```
- Now, will create our python venv `test` inside the `myenvs` folder
  ```
  python -m venv test
  ```
- To view the created venv will use `dir` cmd to view the folder in the dir
- our python venv is created
### How to activate venv
- We will pass the complete address of our venv bat file
  ```
  d:\myenvs\test\scripts\activate.bat
  ```

### How to pip inside the venv
- Once our venv is activated we can install all our packages in it.
  For example lets install `pandas`
  ```
  pip install pandas
  ```
 ### To deactivate venv
- To deactivate the running venv
  ```
  deactivate
  ```
  
  

  
