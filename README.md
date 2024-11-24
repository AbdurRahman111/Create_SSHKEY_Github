# Create_SSHKEY_Github

ssh-keygen -t ed25519 -C "your_email@example.com"

eval "$(ssh-agent -s)"

ssh-add ~/.ssh/id_ed25519

cat ~/.ssh/id_ed25519.pub

xclip -sel clip < ~/.ssh/id_ed25519.pub

ssh -T git@github.com

Hi username! You've successfully authenticated, but GitHub does not provide shell access.
