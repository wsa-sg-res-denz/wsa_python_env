## 1A. Create Env  
To use the spec file to create an identical environment on the same machine or another machine:  
`conda create --name myenv --file spec-file.txt`
<br>
<br>

## 1B. Install into Existing Env
To use the spec file to install its listed packages into an existing environment:  
`conda install --name myenv --file spec-file.txt`
<br>
<br>

## 2. Install remaining pip libraries
type `pip install -r requirement.txt` on the command prompt to install all the required library package
