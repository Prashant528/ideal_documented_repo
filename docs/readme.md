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

## Building the documentation

Once you have setup the `doc-builder` and additional packages, you can generate the documentation by 
typing the following command:

```bash
doc-builder build transformers docs/source/en/ --build_dir ~/tmp/test-build
```

You can adapt the `--build_dir` to set any temporary folder that you prefer. This command will create it and generate
the MDX files that will be rendered as the documentation on the main website. You can inspect them in your favorite
Markdown editor.
