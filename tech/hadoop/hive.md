C:\Users\user\vagrant\hadoop>vagrant box list
~~~
centos7 (virtualbox, 0)
~~~
C:\Users\user\vagrant\hadoop>vagrant up dn01 dn02 nn01 > hive.log
~~~
Bringing machine 'dn01' up with 'virtualbox' provider...
Bringing machine 'dn02' up with 'virtualbox' provider...
Bringing machine 'nn01' up with 'virtualbox' provider...
==> dn01: Importing base box 'centos7'...
[K==> dn01: Matching MAC address for NAT networking...
==> dn01: Setting the name of the VM: dn01
==> dn01: Clearing any previously set network interfaces...
==> dn01: Preparing network interfaces based on configuration...
    dn01: Adapter 1: nat
    dn01: Adapter 2: hostonly
==> dn01: Forwarding ports...
    dn01: 22 (guest) => 2222 (host) (adapter 1)
==> dn01: Running 'pre-boot' VM customizations...
==> dn01: Booting VM...

C:\Users\user\vagrant\hadoop>type hive.log
Bringing machine 'dn01' up with 'virtualbox' provider...
Bringing machine 'dn02' up with 'virtualbox' provider...
Bringing machine 'nn01' up with 'virtualbox' provider...
==> dn01: Importing base box 'centos7'...
[K==> dn01: Matching MAC address for NAT networking...
==> dn01: Setting the name of the VM: dn01
==> dn01: Clearing any previously set network interfaces...
==> dn01: Preparing network interfaces based on configuration...
    dn01: Adapter 1: nat
    dn01: Adapter 2: hostonly
==> dn01: Forwarding ports...
    dn01: 22 (guest) => 2222 (host) (adapter 1)
==> dn01: Running 'pre-boot' VM customizations...
==> dn01: Booting VM...
==> dn01: Waiting for machine to boot. This may take a few minutes...
    dn01: SSH address: 127.0.0.1:2222
    dn01: SSH username: vagrant
    dn01: SSH auth method: private key
~~~
