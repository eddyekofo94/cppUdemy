# Useful stuff

Run code using code-runner inside bin folder: (Setting for VSCode):
`"code-runner.executorMap": {
        "cpp": "cd $dir && g++ -std=c++17 $fileName -o ../bin/$fileNameWithoutExt && cd .. && ./bin/$fileNameWithoutExt",
    },`