# Supporting Materials
Additional Useful Information

[BACK to HOMEPAGE](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/README.md)



## Repositories

### Actively used to build the lab image:

1) Fedora RISC-V ESWIN EIC7700

2) Fedora RISC-V Koji (unofficial)


### Repositories Defined in the image
> Only the previously mentioned above repositories are actually active
>

---------------------------------------

#### File:  fedora-repo-eswin-eic7700.repo


fedora-riscv-eswin-eic7700]
name=Fedora RISC-V ESWIN EIC7700
baseurl=https://openkoji.iscas.ac.cn/pub/dist-repos/dl/ESWIN/EIC7700/repos/
enabled=1
priority=1
gpgcheck=0

--------------------------------------

#### File:  fedora-riscv-koji.repo

[fedora-riscv-koji]
name=Fedora RISC-V Koji
baseurl=http://openkoji.iscas.ac.cn/kojifiles/repos/f42-build/latest/riscv64/
enabled=1
gpgcheck=0

-------------------------------------

#### File:  fedora-cisco-openh264.repo

[fedora-cisco-openh264]
name=Fedora $releasever openh264 (From Cisco) - $basearch
metalink=https://mirrors.fedoraproject.org/metalink?repo=fedora-cisco-openh264-$releasever&arch=$basearch
type=rpm
enabled=0
metadata_expire=14d
repo_gpgcheck=0
gpgcheck=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=True

[fedora-cisco-openh264-debuginfo]
name=Fedora $releasever openh264 (From Cisco) - $basearch - Debug
metalink=https://mirrors.fedoraproject.org/metalink?repo=fedora-cisco-openh264-debug-$releasever&arch=$basearch
type=rpm
enabled=0
metadata_expire=14d
repo_gpgcheck=0
gpgcheck=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=True

[fedora-cisco-openh264-source]
name=Fedora $releasever openh264 (From Cisco) - $basearch - Source
metalink=https://mirrors.fedoraproject.org/metalink?repo=fedora-cisco-openh264-source-$releasever&arch=$basearch
type=rpm
enabled=0
metadata_expire=14d
repo_gpgcheck=0
gpgcheck=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=True

------------------------------

#### File: fedora-rawhide.repo

[rawhide-source]
name=Fedora - Rawhide - Source
#baseurl=http://download.example/pub/fedora/linux/development/rawhide/Everything/source/tree/
metalink=https://mirrors.fedoraproject.org/metalink?repo=rawhide-source&arch=$basearch
enabled=0
metadata_expire=6h
repo_gpgcheck=0
type=rpm
gpgcheck=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-rawhide-$basearch file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-43-$basearch
skip_if_unavailable=False

----------------------------

#### File:  fedora.repo

[fedora]
name=Fedora $releasever - $basearch
#baseurl=http://download.example/pub/fedora/linux/releases/$releasever/Everything/$basearch/os/
metalink=https://mirrors.fedoraproject.org/metalink?repo=fedora-$releasever&arch=$basearch
enabled=0
countme=1
metadata_expire=6h
repo_gpgcheck=0
type=rpm
gpgcheck=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=False

[fedora-debuginfo]
name=Fedora $releasever - $basearch - Debug
#baseurl=http://download.example/pub/fedora/linux/releases/$releasever/Everything/$basearch/debug/tree/
metalink=https://mirrors.fedoraproject.org/metalink?repo=fedora-debug-$releasever&arch=$basearch
enabled=0
metadata_expire=6h
repo_gpgcheck=0
type=rpm
gpgcheck=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=False

[fedora-source]
name=Fedora $releasever - Source
#baseurl=http://download.example/pub/fedora/linux/releases/$releasever/Everything/source/tree/
metalink=https://mirrors.fedoraproject.org/metalink?repo=fedora-source-$releasever&arch=$basearch
enabled=0
metadata_expire=6h
repo_gpgcheck=0
type=rpm
gpgcheck=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=False

----------------------------------

#### File: Fedora-updates.repo

[updates]
name=Fedora $releasever - $basearch - Updates
#baseurl=http://download.example/pub/fedora/linux/updates/$releasever/Everything/$basearch/
metalink=https://mirrors.fedoraproject.org/metalink?repo=updates-released-f$releasever&arch=$basearch
enabled=0
countme=1
repo_gpgcheck=0
type=rpm
gpgcheck=1
metadata_expire=6h
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=False

[updates-debuginfo]
name=Fedora $releasever - $basearch - Updates - Debug
#baseurl=http://download.example/pub/fedora/linux/updates/$releasever/Everything/$basearch/debug/
metalink=https://mirrors.fedoraproject.org/metalink?repo=updates-released-debug-f$releasever&arch=$basearch
enabled=0
repo_gpgcheck=0
type=rpm
gpgcheck=1
metadata_expire=6h
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=False

[updates-source]
name=Fedora $releasever - Updates Source
#baseurl=http://download.example/pub/fedora/linux/updates/$releasever/Everything/SRPMS/
metalink=https://mirrors.fedoraproject.org/metalink?repo=updates-released-source-f$releasever&arch=$basearch
enabled=0
repo_gpgcheck=0
type=rpm
gpgcheck=1
metadata_expire=6h
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=False

--------------------------------------------

#### File:  fedora-updates-testing.repo


[updates-testing]
name=Fedora $releasever - $basearch - Test Updates
#baseurl=http://download.example/pub/fedora/linux/updates/testing/$releasever/Everything/$basearch/
metalink=https://mirrors.fedoraproject.org/metalink?repo=updates-testing-f$releasever&arch=$basearch
enabled=0
countme=1
repo_gpgcheck=0
type=rpm
gpgcheck=1
metadata_expire=6h
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=False

[updates-testing-debuginfo]
name=Fedora $releasever - $basearch - Test Updates Debug
#baseurl=http://download.example/pub/fedora/linux/updates/testing/$releasever/Everything/$basearch/debug/
metalink=https://mirrors.fedoraproject.org/metalink?repo=updates-testing-debug-f$releasever&arch=$basearch
enabled=0
repo_gpgcheck=0
type=rpm
gpgcheck=1
metadata_expire=6h
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=False

[updates-testing-source]
name=Fedora $releasever - Test Updates Source
#baseurl=http://download.example/pub/fedora/linux/updates/testing/$releasever/Everything/SRPMS/
metalink=https://mirrors.fedoraproject.org/metalink?repo=updates-testing-source-f$releasever&arch=$basearch
enabled=0
repo_gpgcheck=0
type=rpm
gpgcheck=1
metadata_expire=6h
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-fedora-$releasever-$basearch
skip_if_unavailable=False

-------------------------------------

#### File:  openkoji-fedora.repo 

[fedora-riscv-koji]
name=Fedora RISC-V Koji
baseurl=http://openkoji.iscas.ac.cn/kojifiles/repos/f$releasever-build/latest/riscv64/
enabled=1
gpgcheck=0

------------------------------------------------------------------------------------------------






## Running Performance Co-Pilot (PCP) Exercise

### Steps:


**Due to overhead - we recommend you skip this section and optionally run it after the 3rd lab**
>

> In this exercise, we will install Performance Co-Pilot (Otherwise known as PCP). This tool will allow for near realtime graphical performance analysis of many metrics - however we will only install just a few of these checks for this workshop.
> PLEASE NOTE:  PCP is great for debugging, capacity planning, and troubleshooting ... BUT ... it does add a significant amount of overhead to any system... Use it accordingly.

> Open a terminal.

```
$  sudo -i

# dnf install -y   pcp  pcp-conf pcp-devel pcp-doc pcp-libs pcp-libs-devel pcp-gui
(output omitted)

# dnf install -y pcp2pdf pcp-pmda-dm pcp-pmda-bash pcp-pmda-lmsensors
(output omitted)

# dnf install -y  pcp-pmda-memcache pcp-pmda-netcheck pcp-pmda-podman pcp-pmda-rsyslog
(output omitted)

# dnf install -y  pcp-pmda-sockets pcp-pmda-summary pcp-pmda-trace pcp-pmda-systemd pcp-system-tools

# reboot

```





> Once the system has rebooted, log back into Gnome Desktop.


> Go to the applications selector (upper left hand corner) and scroll until you find "PCP Charts" - click on the icon.
![PCP 1](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab2a-pcp1.png)

![PCP 2](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab2a-pcp2.png)

![PCP 3](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab2a-pcp3.png)

![PCP 4](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab2a-pcp4.png)

![PCP 5](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab2a-pcp5.png)

![PCP 6](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab2a-pcp6.png)

![PCP 7](https://github.com/mattstonge/riscv_summit_devdays_fedora_AI_workshop/blob/main/images/lab2a-pcp7.png)








