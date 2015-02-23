# scriptcollections
This script requires argparse
easy_install argparse

Run the script
update_python_switchers.py 

Next, you will need to add this to your $HOME/.bash_profile

export OLD_PATH=$PATH
. $HOME/.python_switchers.sh 

update_python_switchers.py --use-fancy-prompt
