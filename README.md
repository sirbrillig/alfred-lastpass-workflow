# alfred-lastpass-workflow
An [Alfred](http://www.alfredapp.com/) workflow for searching LastPass and copying the results to the clipboard

# Install
Download and install the `lpass` command-line tool from [the official repository](https://github.com/LastPass/lastpass-cli).

Log in in a Terminal window using `lpass login -trust`.

Install the `Search_LastPass.alfredworkflow` file by double-clicking it and
importing into Alfred.

The workflow is configured to use `zsh`. If you used `bash` when running
Terminal (the Mac OS default), you may need to edit the workflow and change the
script type to `/bin/bash`.

# Future plans
It would be nice to automate the login process and allow copying the username,
but this works for me for now. Contributions are welcome.

