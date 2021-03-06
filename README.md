# Python Editor and Compiler
#### Implemented using [Brython](https://github.com/brython-dev/brython)

## Release Notes:
* Supports executing Python3 code
* Code Editor built using [Ace](https://github.com/ajaxorg/ace)
* Interactive Console built using [Brython](https://github.com/brython-dev/brython)
* Supporting stdin and stdout streams for testcases
* Returns a result object after every execution
    ```
    {
        "input": [<line>,<line>,...],
        "output": [<line>,<line>,...],
        "expected": [<line>,<line>,...],
        "code": <string>
    }
    ```

## TuDu:
* Testcase Evaluator ([help](https://github.com/veda-vyas/testcase-evaluator))

## Installation:
* Clone the Repository
``` git clone https://github.com/veda-vyas/code-editor.git ```
* Run a http server to serve the editor page
``` python -m SimpleHTTPServer ```
* Open your browser and navigate to
``` http://localhost:8000/editor.html ```
