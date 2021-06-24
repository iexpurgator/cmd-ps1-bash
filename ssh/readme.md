# Setup Servers

## Linux

Install `ssh` & `openssh-server`:
```bash
sudo apt install ssh openssh-sever -y
```

Check open port `openssh-server` using:
```bash
sudo service ssh status
```

## MacOS

Set remote login:
```bash
sudo systemsetup -setremotelogin on
```

Check remote login:
```bash
sudo systemsetup -getremotelogin
```

# Transfer

## Send

```bash
scp -r /path/of/file user_name@hostname_or_local_ip:/path/file
```

## Receive

```bash
scp -r user_name@hostname_or_local_ip:/path/file /path/of/file
```
