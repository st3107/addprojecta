# addprojecta
A bash script for those easy to forget tests and round trips before push (for example, me)

## installtion

Make sure you have your rg-db-group and regolith propoerly installed.

Clone this repo and go into it.

``git clone https://github.com/st3107/addprojecta.git``

``cd addprojecta``

Copy the script to one path in your ``$PATH`` variable. In macOS, you can do as the following.

``cp addprojecta /usr/local/bin/addprojecta``

``cp newproject /usr/local/bin/newproject``

Make the script executable. (Don't worry. It is not a virus. I promise.)

``chmod +x /usr/local/bin/addprojecta``

``chmod +x /usr/local/bin/newproject``

## Usage

First, go into the `local` folder of the `rg-db-group`.

``cd rg-db-group/local``

Use the `newproject` to create a new project as a local branch and push to remote (if you have already created the branch, skip this step).

``newproject <branch  name>``

Then, do your edits.

After you finish the editting, go into the ``local`` folder in your ``rg-db-group`` and run the script there.

``addprojecta <branch name>``

You will see that the regolith helper run, the round trip is done and changes are add, commited and pushed.
