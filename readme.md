
## Usage

Fork/clone this repository.

run `python3 initialize_project.py` to download dependencies.

### Compile for Desktop

`cd desktop`

`cmake .` (only the first time, and everytime you add new files)

`make`

`cd ..`

`./desktop/out/game`


### Compile for HTML/Web

**NOTE**: [install Emscripten first](https://emscripten.org/docs/getting_started/downloads.html)

`cd html`

`emconfigure cmake .` (only the first time, and everytime you add new files)

`make`

`emrun out/game.html`
