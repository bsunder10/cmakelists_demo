# Basic CMake Project configuration

## Building from the main file
~~~
    cmake --build {folder_dirctory}
~~~

### Example: 
To build for a project whose build has to be in a folder called **"build"**
~~~
cmake --build build
~~~

### Note:
> When more than one CMakeLists.txt file exists, there will be subfolders in the build folder for all the project folders consisting of CMakeLists.txt files. 
So when using more than one CMakeLists.txt file <br><br>  
~~~
./build/{main_folder_name}/{main_file_name}
~~~

#### Example;
For a **main** as output file is in **main** folder, then the output can be seen by using the below command
~~~
./build/main/main
~~~

