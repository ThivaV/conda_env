# conda environments

* Export an environment:
	```bash
	$ conda env export --name <ENV_NAME> > <FILE_NAME>.yml
	```
* Import an environment:
	```bash
	$ conda env create --file <FILE_NAME>.yml
	```
