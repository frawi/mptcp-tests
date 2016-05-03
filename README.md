# mptcp-tests

Testing of Multipath TCP using Mininet

## Requirements

* VirtualBox
* Vagrant

## Run

```
vagrant up
vagrant ssh
cd /vagrant
sudo ./benchmark.py --paths 10
```

## Parameters

To see the available parameters for the benchmark run:

```
./benchmark.py --help
```

