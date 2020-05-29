# addprojecta
A bash script for those easy to forget tests and round trips before push (for example, me)

## installtion

Make sure you have your rg-db-group and regolith propoerly installed.

Clone this repo and go into it.

``git clone https://github.com/st3107/addprojecta.git``

``cd addprojecta``

Copy the script to one path in your ``$PATH`` variable. In macOS, you can do as the following.

``cp addprojecta /usr/local/bin/addprojecta``

Make the script executable. (Don't worry. It is not a virus. I promise.)

``chmod +x /usr/local/bin/addprojecta``

## Usage

First, checkout a new local branch and push it to the remote and set uptream.

``git checkout -b <new branch>``

``git push -u origin <new branch>``

Then, do your edits.

After you finish the editting, go into the ``local`` folder in your ``rg-db-group`` and run the script there.

``addprojecta``

You will see that the regolith helper run, the round trip is done and changes are add, commited and pushed.