# Terraform 

```
https://download.virtualbox.org/virtualbox/7.1.12/VirtualBox-7.1.12-169651-Win.exe
https://developer.hashicorp.com/vagrant/install
https://code.visualstudio.com/download
```


```
https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170
```


Create Vagrantfile

```
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/jammy64"
end
```

## vagrant commands
```
vagrant init
vagrant up
vagrant status
vagrant ssh
```
