# tem



```
├── .devcontainer
│   └── devcontainer.json   - the infomation of dev container  
│
├── deployment              - deployment folder
│   ├── conanfile.txt       - conan packages requirements
│   └── deploy.sh           - deploy commands
│
├── model                   - The content in this directory is merged together with other models
|                              specifiec as dependencies in the conanfile.py.
│   └── CHIPPS_EC1_Deployment_dummy_swc_proc_Log.arxml.arxml                    - ARXML file
│   
├── src                     - source codes
│   ├── DummyApp.cpp        - demo app
│   ├── DummyApp.h          - header file 
|   ├── CMakeLists.txt
|   └── main.cpp            - The main function of the ecu state manager application
|
├── test
|   ├── tests.cpp           - gtest 
│   └── CMakeLists.txt  
│
├── CMakeLists.txt        
|
├── codecheck.sh
|
├── conanfile.py
|
└── README.md

```

```
├── .devcontainer
│   └── devcontainer.json   - the infomation of dev container  
│
├── build                   - build folder
│   ├── bin       
│   ├── CMakeFiles  
|   ├── lib
|   ├── src
|   ├── test
|   ├── ...
|
├── deployment              - deployment folder
│   ├── conanfile.txt       - conan packages requirements
│   ├── deploy.sh           - deploy commands
│   ├── a3-app-core
|   ├── amsr-daemons        - the folder contains demo app 
|       ├── etc
|       ├── opt
|       └── sbin
|   ├── gtest
|   ├── ...
|
├── model                   - The content in this directory is merged together with other models
|                              specifiec as dependencies in the conanfile.py.
│   └── CHIPPS_EC1_Deployment_dummy_swc_proc_Log.arxml.arxml                    - ARXML file
│   
├── src                     - source codes
│   ├── DummyApp.cpp        - demo app
│   ├── DummyApp.h          - header file 
|   ├── CMakeLists.txt
|   └── main.cpp            - The main function of the ecu state manager application
|
├── src-gen                 - generated source codes based on AP    
│   ├── ara
│   ├── amsr
|   ├── conti
|   ├── scania
|   ├── traton
|   ├── ...
|
├── test
|   ├── tests.cpp           - gtest 
│   └── CMakeLists.txt  
│
├── CMakeLists.txt        
|
├── codecheck.sh
|
├── conanfile.py
|
└── README.md

```
