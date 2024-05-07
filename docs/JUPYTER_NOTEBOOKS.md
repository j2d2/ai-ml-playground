# Jupyter Notebooks

Note: JupyterLab is the new IDE-like version of Jupyter Notebooks

## Docs

[Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/en/stable/)  

[Jupyter/IPython Notebook Quick Start Guide: Running the Jupyter Notebook](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)

## Debugging in Notebooks

If you see an error, immediately after an uncaught exception, add this to the next code block:  
`%debug` -> Python debugger
  - opens an `ipdb` (iPython Debugger) prompt
  - Read errors from bottom up, tracing backwards

### Essential Debugger commands with `%debug`:

`p <var`: print single variable  
`l`: print source code  
`bt`: show backtrace  
`u`: step up to function that called the current function  

_From within a function definition:_

`breakpoint()`: stops execution and launches debugger to:
  - Step line-by-line through the code
  - Uncover hard-to-find erros

JupyterLab has an "Enable Debugger" button in the toolbar, enabled graphical approach to the debugger (avoids having to enter commmands at the prompt)  

## Extensions
* Autocomplete - language service protocol (adds tooltips and code diagnostics) (jupyterlab-lsp)
* nbdime - useful Diff and Merge tools
* 







