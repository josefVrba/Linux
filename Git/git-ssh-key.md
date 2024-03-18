## Create SSH key
```bash
ssh-keygen -t ed25519 -C <user-email>
```
## Link SSH key with Github
```bash
cat ~/.ssh/id_ed25519.pub
```
## Testing SSH connection
```bash
ssh -T git@github.com
```
