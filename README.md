Create .github folder in that create workflows sub folder
in workflows folder create a file called as deploy.yml
copy content as in deploy.yml from this repo.
click on repository settings > in left side secuirty section  click on "Secrets and Variables"
In repository Secrets section click on "New repository Secret"
Then add Name: SSH_PRIVATE_KEY and give secret as pem file and click on add secret.
Name: SERVER_USERNAME Secret as "ubuntu" as per your request.
Name: SERVER_HOST Secret as "Provide IP address of destination server."

Now configure server for password less authentications
Click on your user icon on top right side then click on settings.
In settings click on "ssh and GPG keys"
Then click on "New SSH key"
Give a name to this server and add title and key possibly use ip_pub.key(ssh-key-gen command should execute in server). Then click on add SSH key.
