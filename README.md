# clean_node_modules
Find and delete all node_modules to save some space


# One time clean without installing:
Open folder with you frontend projects and run  
`wget -O - https://raw.githubusercontent.com/menemy/clean_node_modules/master/clean_node_modules | bash`
or  
`curl https://raw.githubusercontent.com/menemy/clean_node_modules/master/clean_node_modules | bash`


# Download for future use
`mkdir -p ~/bin && curl  https://raw.githubusercontent.com/menemy/clean_node_modules/master/clean_node_modules > ~/bin/clean_node_modules && chmod +x ~/bin/clean_node_modules`
