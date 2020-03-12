## Add virtualenv as Python kernel
- Activate the virtualenv
- Install jupyter in the virtualenv
- Add the virtualenv as a jupyter kernel  
(venv)$ ipython kernel install --name "local-venv" --user

## List kernels
$ jupyter kernelspec list

## Remove kernels
$ jupyter kernelspec remove <kernel_name>

## Change Kernel name
- Check the kernels directory with `jupyter kernelspec  list`
- Go to the directory of the kernel, open up the file kernel.json and edit option "display_name".
