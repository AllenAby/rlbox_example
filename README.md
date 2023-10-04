# rlbox_example
Running Rust code in RLBox

## Cloning this repo with submodules
`git clone --recurse-submodules https://github.com/AllenAby/rlbox_example.git`

## Build RLBox
`cd rlbox`

`cmake -S . -B ./build -DCMAKE_BUILD_TYPE=Release`

`cmake --build ./build --config Release --parallel`

`cd build && sudo make install`

## Building RLBox tools repo
`cd rlbox_wasm2c_sandbox`

`cmake -S . -B ./build`

`cmake --build ./build --target all`

`make`

## Running myapp
`make`

`./myapp`