# Set up Git to access codecommit repository on Linux

git config --global credential.helper '!aws codecommit credential-helper $@'
git config --global credential.UseHttpPath true
git config --global --edit
git config -l

