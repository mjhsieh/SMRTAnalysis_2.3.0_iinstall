
```
$ vagrant up
$ vagrant ssh head01
vagrant$ bash /vagrant/smrtanalysis_2.3.0.140550_libc-2.5_centos-53.run \
              -p smrtanalysis-patch_2.3.0.140936.p4.run \
              --rootdir /smrtanalysis
```
And follow the instructions, mostly pressing enters, use localhost as the hostname.
SGE should be automatically picked up. After installation, use 
```
/smrtanalysis/admin/smrtportal-initd start
```
to start the SMRT portal.

- Point your host safari/firefox to log on http://localhost:8080
- register administrator is required for a new portal
- then start to use your toy cluster.