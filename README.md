# Find and delete not required developer files to save some space, currently only for OSX


## (Alas Don't work) One time clean without installing:
Open folder with you frontend projects and run  
`wget -O - https://raw.githubusercontent.com/menemy/clean_dev_files/master/clean_dev_files | bash`
or  
`curl https://raw.githubusercontent.com/menemy/clean_dev_files/master/clean_dev_files | bash`


## Download and run for future use
`mkdir -p ~/bin && curl  https://raw.githubusercontent.com/menemy/clean_dev_files/master/clean_dev_files > ~/bin/clean_dev_files && chmod +x ~/bin/clean_dev_files && ~/bin/clean_dev_files`

### Install trash command `brew install trash` to move directories in Trash instead of deleting
