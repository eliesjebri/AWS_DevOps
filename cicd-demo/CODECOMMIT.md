# Set up Git to access codecommit repository on Linux
git config --global credential.helper '!aws codecommit credential-helper $@'\
git config --global credential.UseHttpPath true\
git config --global --edit\
git config -l

# On Codecommit create README.md file / create new "master" branch and set it as default / Delete "main" branch

# Configure your git client
git config --global user.email ej@gmail.com\
git config --global user.name "elies"


