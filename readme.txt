1. create folder 
2. use git init command to build composer.json and .lock
3. use composer require --dev orchestra/testbench
4. create git ignore using command "echo "/vendor/" > .gitignore"


    "autoload-dev": {
        "psr-4": {
            "Jerickcm\\Press\\Tests": "tests/"
        }
    },