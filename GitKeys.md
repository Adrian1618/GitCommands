
# Create a Key
~ ssh-keygen -t ecdsa-sk -C "your_email@example.com"

# Go into the public key generated and pass it to GitHub

# Add ssh key to the ssh-agent
~ eval "$(ssh-agent -s)"
~ ssh-add "NameOfKey"
