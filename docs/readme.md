This is my documentation readme file.
# Generating the documentation

To generate the documentation, you first have to build it. Several packages are necessary to build the doc, 
you can install them with the following command, at the root of the code repository:

```bash
pip install -e ".[docs]"
```

Then you need to install our special tool that builds the documentation:

```bash
pip install git+https://github.com/huggingface/doc-builder
```
