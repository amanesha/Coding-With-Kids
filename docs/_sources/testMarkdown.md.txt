 Markdown
==================

To configure your Sphinx project for Markdown support, proceed as follows:
Install the Markdown parser MyST-Parser::

    pip install --upgrade myst-parser

Add myst_parser to the list of configured extensions::

    extensions = ['myst_parser']
    source_suffix = {
    '.rst': 'restructuredtext',
    '.txt': 'markdown',
    '.md': 'markdown',
    }

