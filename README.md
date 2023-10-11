# tem



```
├── .devcontainer
│   └── devcontainer.json   - the infomation of dev container
│   
│
├── deployment              - deployment folder
│   ├── conanfile.txt       - conan packages requirements
│   └── deploy.sh           - deploy commands
│
│
├── model                   - this folder contains trainers of your project.
│   └── CHIPPS_EC1_Deployment_dummy_swc_proc_Log.arxml.arxml                  - ARXML file
│   
│   
├── src              - here's the main(s) of your project (you may need more than one main).
│   └── example_main.py  - here's an example of main that is responsible for the whole pipeline.
│  
├── test  
│   └── data_generator.py  - here's the data_generator that is responsible for all data handling.
│ 
├── test_package
│   └── conanfile.py
│
├── CMakeLists.txt              - deployment folder
│   
|
├── codecheck.sh
|
├── conanfile.py
|
└── README.md

```
