# Setting Up Your Enviroment ( In linux and probably os x)
1 ) Generate ssh keys for your user ( If not already done )
```
ssh-keygen
```

2 ) Copy your key to github
```
cat ~/.ssh/id_rsa.pub
```
This will give you an output like
```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDXmjHClrLVQPTMYL029bSE9o/IGYl/MAhNFYeeQMzG9fCgJ+pQeFjgBSgH1S8yqDm0M4EKgkGMKSJ0HsyecMfNCCeABesWiNU4TD+ET/UhHSvAbKWEFy0527I/UkY3u4v9a7gRuC8jXjFjVGyoEgz3gR6NxdE+EDKr7D7eOwfa7WxvjxfG3uwShzlmUNxkNrEnF6lospdRn/C9PEPIBiDQGe9Sx0gcfeCKhi99c0/lUbPenlnaqsgt/fWXEQ4OM/7ZhtR1qOWXwvbz6ixcN1LlQOytMQdVas/vXceoVGR6Y9F0iFMaPL3qrm963rcjFBMQ4sfBFXZ1spt5Wo0VG5sN tholum@hplaptop

```

Copy this from and including ssh-rsa to user@hostname Then in github go to Settings -> Ssh Keys -> Add SSH Key, and copy this in the key area, and name it appropriatly ( to remove it if you pc gets lost ext... )

Now set your global config to who you are
```
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```
Last but not least, Get rid of nano as your default editor ( personal preference )

```
git config --global core.editor "vim"
```
