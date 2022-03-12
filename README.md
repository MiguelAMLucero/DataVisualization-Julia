# Data Visualization with Julia
Here you can find the material and instructions to get started with basic 
julia ploting and data visualization

To install julia from mac, you can use brew running:

`brew install --cask julia`

After instalation ended, run:

`/usr/local/bin/julia`

and you must see julia started in your console.

Now we add the IJulia with

`using Pkg`

`Pkg.add("IJulia")`

Then we start our jupyterlab 

`using IJulia`

`jupyterlab()`

Once we have our notebook open we can install the Plots package

`] add Plots`

To quickly test if julia is working try

`println("hello world")`
