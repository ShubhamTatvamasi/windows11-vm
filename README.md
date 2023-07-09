# Windows 11 Vagrant Box

Download windows 11 vagrant box:
```bash
vagrant box add gusztavvargadr/windows-11 \
  --box-version=2202.0.2306 \
  --provider=virtualbox
```

start windows:
```bash
vagrant up
```

sleep and resume:
```bash
vagrant suspend
vagrant resume
```

delete windows:
```bash
vagrant destroy
```
