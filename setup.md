to point jupyter notebook to virtual env

1. `pip3 install --user virtualenv`
1. `virtualenv myenv`
1. `virtualvenv myenv`
1. `. myenv/bin/activate.fish`
1. `pip install --user ipykernel`
1. `python -m ipykernel install --name=myenv`

now in vscode ctrl+shit+p and search for `kernel` and then select `myenv`

install `requests` module: `pip install requests`
