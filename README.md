# Opsales
voclabs:~/environment $ sudo apt install jitsi-meet
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  coturn fonts-lato javascript-common jicofo jitsi-meet-prosody jitsi-meet-turnserver jitsi-meet-web
  jitsi-meet-web-config jitsi-videobridge2 jq libevent-extra-2.1-6 libevent-openssl-2.1-6 libevent-pthreads-2.1-6
  libhiredis0.13 libjq1 libjs-jquery liblua5.1-0 liblua5.1-0-dev libmysqlclient20 libonig4 libpq5 libruby2.5
  libtool-bin lua-any lua-basexx lua-cjson lua-luaossl luarocks prosody rake ruby ruby-did-you-mean ruby-hocon
  ruby-minitest ruby-net-telnet ruby-power-assert ruby-test-unit ruby2.5 rubygems-integration
Suggested packages:
  sip-router lua-dbi-mysql lua-dbi-postgresql lua-dbi-sqlite3 lua-ldap ri ruby-dev bundler
Recommended packages:
  lua-readline lua-unbound
The following NEW packages will be installed:
  coturn fonts-lato javascript-common jicofo jitsi-meet jitsi-meet-prosody jitsi-meet-turnserver jitsi-meet-web
  jitsi-meet-web-config jitsi-videobridge2 jq libevent-extra-2.1-6 libevent-openssl-2.1-6 libevent-pthreads-2.1-6
  libhiredis0.13 libjq1 libjs-jquery liblua5.1-0 liblua5.1-0-dev libmysqlclient20 libonig4 libpq5 libruby2.5
  libtool-bin lua-any lua-basexx lua-cjson lua-luaossl luarocks rake ruby ruby-did-you-mean ruby-hocon ruby-minitest
  ruby-net-telnet ruby-power-assert ruby-test-unit ruby2.5 rubygems-integration
The following packages will be upgraded:
  prosody
1 upgraded, 39 newly installed, 0 to remove and 0 not upgraded.
Need to get 82.7 MB of archives.
After this operation, 164 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 fonts-lato all 2.0-2 [2698 kB]
Get:2 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 rubygems-integration all 1.11 [4994 B]
Get:3 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic-updates/main amd64 rake all 12.3.1-1ubuntu0.1 [44.9 kB]
Get:4 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 ruby-did-you-mean all 1.2.0-2 [9700 B] 
Get:5 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 ruby-minitest all 5.10.3-1 [38.6 kB]           
Get:6 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 ruby-net-telnet all 0.1.1-2 [12.6 kB]          
Get:7 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 ruby-power-assert all 0.3.0-1 [7952 B]         
Get:8 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 ruby-test-unit all 3.2.5-1 [61.1 kB]           
Get:9 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic-updates/main amd64 libruby2.5 amd64 2.5.1-1ubuntu1.13 [3074 kB]
Get:10 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic-updates/main amd64 ruby2.5 amd64 2.5.1-1ubuntu1.13 [48.6 kB]
Get:11 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 ruby amd64 1:2.5.1 [5712 B]                  
Get:12 https://download.jitsi.org stable/ jitsi-videobridge2 2.2-79-gf6426ea0-1 [37.2 MB]                        
Get:13 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 ruby-hocon all 1.2.5-1 [74.8 kB]          
Get:14 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 libonig4 amd64 6.7.0-1 [119 kB]           
Get:15 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 libjq1 amd64 1.5+dfsg-2 [111 kB]          
Get:16 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 jq amd64 1.5+dfsg-2 [45.6 kB]             
Get:17 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 lua-luaossl amd64 20161214-1build1 [75.5 kB]
Get:18 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 libevent-extra-2.1-6 amd64 2.1.8-stable-4build1 [56.2 kB]
Get:19 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 libevent-openssl-2.1-6 amd64 2.1.8-stable-4build1 [11.8 kB]
Get:20 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 libevent-pthreads-2.1-6 amd64 2.1.8-stable-4build1 [5228 B]
Get:21 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 libhiredis0.13 amd64 0.13.3-2.2 [25.3 kB]
Get:22 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic-updates/main amd64 libmysqlclient20 amd64 5.7.41-0ubuntu0.18.04.1 [729 kB]
Get:23 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic-updates/main amd64 libpq5 amd64 10.23-0ubuntu0.18.04.1 [108 kB]
Get:24 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic-updates/universe amd64 coturn amd64 4.5.0.7-1ubuntu2.18.04.3 [320 kB]
Get:25 http://packages.prosody.im/debian bionic/main amd64 prosody amd64 0.12.3-1~bionic1 [403 kB]
Get:26 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 javascript-common all 11 [6066 B]  
Get:27 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 libjs-jquery all 3.2.1-1 [152 kB]        
Get:28 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 liblua5.1-0 amd64 5.1.5-8.1build2 [100 kB]
Get:29 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 liblua5.1-0-dev amd64 5.1.5-8.1build2 [119 kB]
Get:30 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/main amd64 libtool-bin amd64 2.4.6-2 [79.5 kB]    
Get:31 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 lua-any all 24 [4718 B]         
Get:32 http://us-east-1.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 luarocks all 2.4.2+dfsg-1 [97.6 kB]
Get:33 https://download.jitsi.org stable/ jicofo 1.0-996-1 [21.0 MB]                                      
Get:34 https://download.jitsi.org stable/ jitsi-meet-web 1.0.6991-1 [15.8 MB]                                         
Get:35 https://download.jitsi.org stable/ jitsi-meet-web-config 1.0.6991-1 [27.7 kB]                                  
Get:36 https://download.jitsi.org stable/ lua-basexx 0.4.1-jitsi1 [4288 B]                                            
Get:37 https://download.jitsi.org stable/ lua-cjson 2.1.0.10-jitsi1 [20.1 kB]                                         
Get:38 https://download.jitsi.org stable/ jitsi-meet-prosody 1.0.6991-1 [71.3 kB]                                     
Get:39 https://download.jitsi.org stable/ jitsi-meet 2.0.8319-1 [3340 B]                                              
Get:40 https://download.jitsi.org stable/ jitsi-meet-turnserver 1.0.6991-1 [5408 B]                                   
Fetched 82.7 MB in 11s (7481 kB/s)                                                                                    
Extracting templates from packages: 100%
Preconfiguring packages ...
Selecting previously unselected package fonts-lato.
(Reading database ... 94662 files and directories currently installed.)
Preparing to unpack .../00-fonts-lato_2.0-2_all.deb ...
Unpacking fonts-lato (2.0-2) ...
Selecting previously unselected package rubygems-integration.
Preparing to unpack .../01-rubygems-integration_1.11_all.deb ...
Unpacking rubygems-integration (1.11) ...
Selecting previously unselected package rake.
Preparing to unpack .../02-rake_12.3.1-1ubuntu0.1_all.deb ...
Unpacking rake (12.3.1-1ubuntu0.1) ...
Selecting previously unselected package ruby-did-you-mean.
Preparing to unpack .../03-ruby-did-you-mean_1.2.0-2_all.deb ...
Unpacking ruby-did-you-mean (1.2.0-2) ...
Selecting previously unselected package ruby-minitest.
Preparing to unpack .../04-ruby-minitest_5.10.3-1_all.deb ...
Unpacking ruby-minitest (5.10.3-1) ...
Selecting previously unselected package ruby-net-telnet.
Preparing to unpack .../05-ruby-net-telnet_0.1.1-2_all.deb ...
Unpacking ruby-net-telnet (0.1.1-2) ...
Selecting previously unselected package ruby-power-assert.
Preparing to unpack .../06-ruby-power-assert_0.3.0-1_all.deb ...
Unpacking ruby-power-assert (0.3.0-1) ...
Selecting previously unselected package ruby-test-unit.
Preparing to unpack .../07-ruby-test-unit_3.2.5-1_all.deb ...
Unpacking ruby-test-unit (3.2.5-1) ...
Selecting previously unselected package libruby2.5:amd64.
Preparing to unpack .../08-libruby2.5_2.5.1-1ubuntu1.13_amd64.deb ...
Unpacking libruby2.5:amd64 (2.5.1-1ubuntu1.13) ...
Selecting previously unselected package ruby2.5.
Preparing to unpack .../09-ruby2.5_2.5.1-1ubuntu1.13_amd64.deb ...
Unpacking ruby2.5 (2.5.1-1ubuntu1.13) ...
Selecting previously unselected package ruby.
Preparing to unpack .../10-ruby_1%3a2.5.1_amd64.deb ...
Unpacking ruby (1:2.5.1) ...
Selecting previously unselected package ruby-hocon.
Preparing to unpack .../11-ruby-hocon_1.2.5-1_all.deb ...
Unpacking ruby-hocon (1.2.5-1) ...
Selecting previously unselected package jitsi-videobridge2.
Preparing to unpack .../12-jitsi-videobridge2_2.2-79-gf6426ea0-1_all.deb ...
Unpacking jitsi-videobridge2 (2.2-79-gf6426ea0-1) ...
Selecting previously unselected package libonig4:amd64.
Preparing to unpack .../13-libonig4_6.7.0-1_amd64.deb ...
Unpacking libonig4:amd64 (6.7.0-1) ...
Selecting previously unselected package libjq1:amd64.
Preparing to unpack .../14-libjq1_1.5+dfsg-2_amd64.deb ...
Unpacking libjq1:amd64 (1.5+dfsg-2) ...
Selecting previously unselected package jq.
Preparing to unpack .../15-jq_1.5+dfsg-2_amd64.deb ...
Unpacking jq (1.5+dfsg-2) ...
Selecting previously unselected package jicofo.
Preparing to unpack .../16-jicofo_1.0-996-1_all.deb ...
Running preinst install
Unpacking jicofo (1.0-996-1) ...
Selecting previously unselected package jitsi-meet-web.
Preparing to unpack .../17-jitsi-meet-web_1.0.6991-1_all.deb ...
Unpacking jitsi-meet-web (1.0.6991-1) ...
Selecting previously unselected package jitsi-meet-web-config.
Preparing to unpack .../18-jitsi-meet-web-config_1.0.6991-1_all.deb ...
Unpacking jitsi-meet-web-config (1.0.6991-1) ...
Preparing to unpack .../19-prosody_0.12.3-1~bionic1_amd64.deb ...
Unpacking prosody (0.12.3-1~bionic1) over (0.10.0-1build1) ...
dpkg: warning: unable to delete old directory '/etc/prosody/conf.avail': Directory not empty
Selecting previously unselected package lua-basexx.
Preparing to unpack .../20-lua-basexx_0.4.1-jitsi1_all.deb ...
Unpacking lua-basexx (0.4.1-jitsi1) ...
Selecting previously unselected package lua-luaossl:amd64.
Preparing to unpack .../21-lua-luaossl_20161214-1build1_amd64.deb ...
Unpacking lua-luaossl:amd64 (20161214-1build1) ...
Selecting previously unselected package lua-cjson:amd64.
Preparing to unpack .../22-lua-cjson_2.1.0.10-jitsi1_amd64.deb ...
Unpacking lua-cjson:amd64 (2.1.0.10-jitsi1) ...
Selecting previously unselected package jitsi-meet-prosody.
Preparing to unpack .../23-jitsi-meet-prosody_1.0.6991-1_all.deb ...
Unpacking jitsi-meet-prosody (1.0.6991-1) ...
Setting up rubygems-integration (1.11) ...
Setting up ruby-did-you-mean (1.2.0-2) ...
Setting up ruby-minitest (5.10.3-1) ...
Setting up ruby-net-telnet (0.1.1-2) ...
Setting up ruby-power-assert (0.3.0-1) ...
Setting up ruby2.5 (2.5.1-1ubuntu1.13) ...
Setting up ruby (1:2.5.1) ...
Setting up ruby-hocon (1.2.5-1) ...
Setting up jitsi-videobridge2 (2.2-79-gf6426ea0-1) ...
grep: /etc/jitsi/videobridge/config: No such file or directory
Generating an empty hocon config
useradd: warning: the home directory already exists.
Not copying any file from skel directory into it.
* Applying /etc/sysctl.d/10-console-messages.conf ...
kernel.printk = 4 4 1 7
* Applying /etc/sysctl.d/10-ipv6-privacy.conf ...
net.ipv6.conf.all.use_tempaddr = 2
net.ipv6.conf.default.use_tempaddr = 2
* Applying /etc/sysctl.d/10-kernel-hardening.conf ...
kernel.kptr_restrict = 1
* Applying /etc/sysctl.d/10-link-restrictions.conf ...
fs.protected_hardlinks = 1
fs.protected_symlinks = 1
* Applying /etc/sysctl.d/10-lxd-inotify.conf ...
fs.inotify.max_user_instances = 1024
* Applying /etc/sysctl.d/10-magic-sysrq.conf ...
kernel.sysrq = 176
* Applying /etc/sysctl.d/10-network-security.conf ...
net.ipv4.conf.default.rp_filter = 1
net.ipv4.conf.all.rp_filter = 1
net.ipv4.tcp_syncookies = 1
* Applying /etc/sysctl.d/10-ptrace.conf ...
kernel.yama.ptrace_scope = 1
* Applying /etc/sysctl.d/10-zeropage.conf ...
vm.mmap_min_addr = 65536
* Applying /etc/sysctl.d/20-jvb-udp-buffers.conf ...
net.core.rmem_max = 10485760
net.core.netdev_max_backlog = 100000
* Applying /usr/lib/sysctl.d/50-default.conf ...
net.ipv4.conf.all.promote_secondaries = 1
net.core.default_qdisc = fq_codel
* Applying /etc/sysctl.d/99-cloudimg-ipv6.conf ...
net.ipv6.conf.all.use_tempaddr = 0
net.ipv6.conf.default.use_tempaddr = 0
* Applying /etc/sysctl.d/99-sysctl.conf ...
fs.inotify.max_user_watches = 524288
* Applying /etc/sysctl.conf ...
fs.inotify.max_user_watches = 524288
Created symlink /etc/systemd/system/multi-user.target.wants/jitsi-videobridge2.service → /lib/systemd/system/jitsi-videobridge2.service.
Setting up rake (12.3.1-1ubuntu0.1) ...
Setting up ruby-test-unit (3.2.5-1) ...
Setting up libruby2.5:amd64 (2.5.1-1ubuntu1.13) ...
Selecting previously unselected package jitsi-meet.
(Reading database ... 97296 files and directories currently installed.)
Preparing to unpack .../0-jitsi-meet_2.0.8319-1_all.deb ...
Unpacking jitsi-meet (2.0.8319-1) ...
Selecting previously unselected package libevent-extra-2.1-6:amd64.
Preparing to unpack .../1-libevent-extra-2.1-6_2.1.8-stable-4build1_amd64.deb ...
Unpacking libevent-extra-2.1-6:amd64 (2.1.8-stable-4build1) ...
Selecting previously unselected package libevent-openssl-2.1-6:amd64.
Preparing to unpack .../2-libevent-openssl-2.1-6_2.1.8-stable-4build1_amd64.deb ...
Unpacking libevent-openssl-2.1-6:amd64 (2.1.8-stable-4build1) ...
Selecting previously unselected package libevent-pthreads-2.1-6:amd64.
Preparing to unpack .../3-libevent-pthreads-2.1-6_2.1.8-stable-4build1_amd64.deb ...
Unpacking libevent-pthreads-2.1-6:amd64 (2.1.8-stable-4build1) ...
Selecting previously unselected package libhiredis0.13:amd64.
Preparing to unpack .../4-libhiredis0.13_0.13.3-2.2_amd64.deb ...
Unpacking libhiredis0.13:amd64 (0.13.3-2.2) ...
Selecting previously unselected package libmysqlclient20:amd64.
Preparing to unpack .../5-libmysqlclient20_5.7.41-0ubuntu0.18.04.1_amd64.deb ...
Unpacking libmysqlclient20:amd64 (5.7.41-0ubuntu0.18.04.1) ...
Selecting previously unselected package libpq5:amd64.
Preparing to unpack .../6-libpq5_10.23-0ubuntu0.18.04.1_amd64.deb ...
Unpacking libpq5:amd64 (10.23-0ubuntu0.18.04.1) ...
Selecting previously unselected package coturn.
Preparing to unpack .../7-coturn_4.5.0.7-1ubuntu2.18.04.3_amd64.deb ...
Unpacking coturn (4.5.0.7-1ubuntu2.18.04.3) ...
Setting up jitsi-meet-web-config (1.0.6991-1) ...
Can't load /home/ubuntu/.rnd into RNG
140626994938304:error:2406F079:random number generator:RAND_load_file:Cannot open file:../crypto/rand/randfile.c:88:Filename=/home/ubuntu/.rnd
Generating a RSA private key
..............................................++++
.......................................++++
writing new private key to '/etc/jitsi/meet/opsales.sakura.ne.jp.key'
-----
Enabling module rewrite.
Considering dependency setenvif for ssl:
Module setenvif already enabled
Considering dependency mime for ssl:
Module mime already enabled
Considering dependency socache_shmcb for ssl:
Enabling module socache_shmcb.
Enabling module ssl.
See /usr/share/doc/apache2/README.Debian.gz on how to configure SSL and create self-signed certificates.
Enabling module headers.
Considering dependency proxy for proxy_http:
Enabling module proxy.
Enabling module proxy_http.
Considering dependency proxy for proxy_wstunnel:
Module proxy already enabled
Enabling module proxy_wstunnel.
Considering dependency mime for include:
Module mime already enabled
Enabling module include.
To activate the new configuration, you need to run:
  systemctl restart apache2
Enabling site opsales.sakura.ne.jp.
To activate the new configuration, you need to run:
  systemctl reload apache2
-------------------------------------------------------------------------
This script will:
- Need a working DNS record pointing to this machine(for hostname )
- Install additional dependencies in order to request Let’s Encrypt certificate (acme.sh)
- Configure and reload nginx or apache2, whichever is used
- Configure the coturn server to use Let's Encrypt certificate and add required deploy hooks
- Configure renew of certificate

  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  1032    0  1032    0     0  11096      0 --:--:-- --:--:-- --:--:-- 10978
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  216k  100  216k    0     0  4597k      0 --:--:-- --:--:-- --:--:-- 4597k
[Fri Feb 24 13:25:17 UTC 2023] Installing from online archive.
[Fri Feb 24 13:25:17 UTC 2023] Downloading https://github.com/acmesh-official/acme.sh/archive/master.tar.gz
[Fri Feb 24 13:25:17 UTC 2023] Extracting master.tar.gz
[Fri Feb 24 13:25:17 UTC 2023] It is recommended to install socat first.
[Fri Feb 24 13:25:17 UTC 2023] We use socat for standalone server if you use standalone mode.
[Fri Feb 24 13:25:17 UTC 2023] If you don't use standalone mode, just ignore this warning.
[Fri Feb 24 13:25:17 UTC 2023] Installing to /opt/acmesh/.acme.sh
[Fri Feb 24 13:25:17 UTC 2023] Installed to /opt/acmesh/.acme.sh/acme.sh
[Fri Feb 24 13:25:17 UTC 2023] No profile is found, you will need to go into /opt/acmesh/.acme.sh to use acme.sh
[Fri Feb 24 13:25:17 UTC 2023] Installing cron job
no crontab for root
no crontab for root
[Fri Feb 24 13:25:17 UTC 2023] Good, bash is found, so change the shebang to use bash as preferred.
[Fri Feb 24 13:25:18 UTC 2023] OK
[Fri Feb 24 13:25:18 UTC 2023] Install success!
[Fri Feb 24 13:25:18 UTC 2023] Using CA: https://acme-v02.api.letsencrypt.org/directory
[Fri Feb 24 13:25:18 UTC 2023] Create account key ok.
[Fri Feb 24 13:25:18 UTC 2023] Registering account: https://acme-v02.api.letsencrypt.org/directory
[Fri Feb 24 13:25:19 UTC 2023] Registered
[Fri Feb 24 13:25:19 UTC 2023] ACCOUNT_THUMBPRINT='alppZ3v9bO-hMZz79xmhXf0wq0s5q00uqEjLHRTqBaE'
[Fri Feb 24 13:25:19 UTC 2023] Creating domain key
[Fri Feb 24 13:25:19 UTC 2023] The domain key is here: /opt/acmesh/.acme.sh/opsales.sakura.ne.jp_ecc/opsales.sakura.ne.jp.key
[Fri Feb 24 13:25:19 UTC 2023] Single domain='opsales.sakura.ne.jp'
[Fri Feb 24 13:25:19 UTC 2023] Getting domain auth token for each domain
[Fri Feb 24 13:25:20 UTC 2023] Getting webroot for domain='opsales.sakura.ne.jp'
[Fri Feb 24 13:25:20 UTC 2023] Verifying: opsales.sakura.ne.jp
[Fri Feb 24 13:25:20 UTC 2023] Pending, The CA is processing your order, please just wait. (1/30)
[Fri Feb 24 13:25:23 UTC 2023] opsales.sakura.ne.jp:Verify error:219.94.163.80: Invalid response from http://opsales.sakura.ne.jp/.well-known/acme-challenge/WBch-5VP4J1imyvFGi6INjfFrX0sowCGNA9pmEPVfq4: 404
[Fri Feb 24 13:25:23 UTC 2023] Please add '--debug' or '--log' to check more details.
[Fri Feb 24 13:25:23 UTC 2023] See: https://github.com/acmesh-official/acme.sh/wiki/How-to-debug-acme.sh
Issuing the certificate from Let's Encrypt failed, continuing ...
You can retry later by executing:
/usr/share/jitsi-meet/scripts/install-letsencrypt-cert.sh tatshi07@gmail.com
Account creation failed. Status: 22, response: 


       ;dOocd;
     .dNMM0dKO.
     lNMMMKd0K,
    .xMMMMNxkNc
     dMMMMMkxXc
     cNMMMNl..
     .kMMMX;             Interested in adding telephony to your Jitsi meetings?
      ;XMMMO'
       lNMMWO'           Sign up on https://jaas.8x8.vc/components?host=opsales.sakura.ne.jp
        lNMMM0,                        and follow the guide in the dev console.
         lXMMMK:.
          ;KMMMNKd.  'oo,
           'xNMMMMXkkkkOKOl'
             :0WMMMMMMNOkk0Kk,
              .cdOWMMMMMWXOkOl
                 .;dKWMMMMMXc.
                    .,:cll:'


Selecting previously unselected package jitsi-meet-turnserver.
(Reading database ... 97435 files and directories currently installed.)
Preparing to unpack .../0-jitsi-meet-turnserver_1.0.6991-1_all.deb ...
Unpacking jitsi-meet-turnserver (1.0.6991-1) ...
Selecting previously unselected package javascript-common.
Preparing to unpack .../1-javascript-common_11_all.deb ...
Unpacking javascript-common (11) ...
Selecting previously unselected package libjs-jquery.
Preparing to unpack .../2-libjs-jquery_3.2.1-1_all.deb ...
Unpacking libjs-jquery (3.2.1-1) ...
Selecting previously unselected package liblua5.1-0:amd64.
Preparing to unpack .../3-liblua5.1-0_5.1.5-8.1build2_amd64.deb ...
Unpacking liblua5.1-0:amd64 (5.1.5-8.1build2) ...
Selecting previously unselected package liblua5.1-0-dev:amd64.
Preparing to unpack .../4-liblua5.1-0-dev_5.1.5-8.1build2_amd64.deb ...
Unpacking liblua5.1-0-dev:amd64 (5.1.5-8.1build2) ...
Selecting previously unselected package libtool-bin.
Preparing to unpack .../5-libtool-bin_2.4.6-2_amd64.deb ...
Unpacking libtool-bin (2.4.6-2) ...
Selecting previously unselected package lua-any.
Preparing to unpack .../6-lua-any_24_all.deb ...
Unpacking lua-any (24) ...
Selecting previously unselected package luarocks.
Preparing to unpack .../7-luarocks_2.4.2+dfsg-1_all.deb ...
Unpacking luarocks (2.4.2+dfsg-1) ...
Setting up libhiredis0.13:amd64 (0.13.3-2.2) ...
Setting up libjs-jquery (3.2.1-1) ...
Setting up lua-any (24) ...
Setting up libtool-bin (2.4.6-2) ...
Setting up lua-luaossl:amd64 (20161214-1build1) ...
Setting up libevent-openssl-2.1-6:amd64 (2.1.8-stable-4build1) ...
Setting up libonig4:amd64 (6.7.0-1) ...
Setting up jitsi-meet-web (1.0.6991-1) ...
Setting up fonts-lato (2.0-2) ...
Setting up libjq1:amd64 (1.5+dfsg-2) ...
Setting up lua-basexx (0.4.1-jitsi1) ...
Setting up libpq5:amd64 (10.23-0ubuntu0.18.04.1) ...
Setting up libevent-pthreads-2.1-6:amd64 (2.1.8-stable-4build1) ...
Setting up lua-cjson:amd64 (2.1.0.10-jitsi1) ...
Setting up libmysqlclient20:amd64 (5.7.41-0ubuntu0.18.04.1) ...
Setting up liblua5.1-0:amd64 (5.1.5-8.1build2) ...
Setting up javascript-common (11) ...
apache2_invoke: Enable configuration javascript-common
Setting up prosody (0.12.3-1~bionic1) ...
Installing new version of config file /etc/init.d/prosody ...
Installing new version of config file /etc/logrotate.d/prosody ...
Installing new version of config file /etc/prosody/prosody.cfg.lua ...
Created symlink /etc/systemd/system/multi-user.target.wants/prosody.service → /lib/systemd/system/prosody.service.
Setting up libevent-extra-2.1-6:amd64 (2.1.8-stable-4build1) ...
Setting up jq (1.5+dfsg-2) ...
Setting up liblua5.1-0-dev:amd64 (5.1.5-8.1build2) ...
Setting up jitsi-meet-prosody (1.0.6991-1) ...

**************************
Prosody was unable to find lua-unbound
This package can be obtained in the following ways:

  Debian/Ubuntu | sudo apt install lua-unbound                                  
       luarocks | luarocks install luaunbound                                   
         Source | https://www.zash.se/luaunbound.html                           

Old DNS resolver library will be used
More help can be found on our website, at https://prosody.im/doc/depends
**************************


**************************
Prosody was unable to find lua-unbound
This package can be obtained in the following ways:

  Debian/Ubuntu | sudo apt install lua-unbound                                  
       luarocks | luarocks install luaunbound                                   
         Source | https://www.zash.se/luaunbound.html                           

Old DNS resolver library will be used
More help can be found on our website, at https://prosody.im/doc/depends
**************************


**************************
Prosody was unable to find lua-unbound
This package can be obtained in the following ways:

  Debian/Ubuntu | sudo apt install lua-unbound                                  
       luarocks | luarocks install luaunbound                                   
         Source | https://www.zash.se/luaunbound.html                           

Old DNS resolver library will be used
More help can be found on our website, at https://prosody.im/doc/depends
**************************


**************************
Prosody was unable to find lua-unbound
This package can be obtained in the following ways:

  Debian/Ubuntu | sudo apt install lua-unbound                                  
       luarocks | luarocks install luaunbound                                   
         Source | https://www.zash.se/luaunbound.html                           

Old DNS resolver library will be used
More help can be found on our website, at https://prosody.im/doc/depends
**************************

Generating RSA private key, 2048 bit long modulus (2 primes)
....................................+++++
...........+++++
e is 65537 (0x010001)
Choose key size (2048): Key written to /var/lib/prosody/opsales.sakura.ne.jp.key
Please provide details to include in the certificate config file.
Leave the field empty to use the default value or '.' to exclude the field.
countryName (JP): localityName (The Internet): organizationName (Your Organisation): organizationalUnitName (XMPP Department): commonName (opsales.sakura.ne.jp): emailAddress (xmpp@opsales.sakura.ne.jp): 
Config written to /var/lib/prosody/opsales.sakura.ne.jp.cnf
Certificate written to /var/lib/prosody/opsales.sakura.ne.jp.crt


**************************
Prosody was unable to find lua-unbound
This package can be obtained in the following ways:

  Debian/Ubuntu | sudo apt install lua-unbound                                  
       luarocks | luarocks install luaunbound                                   
         Source | https://www.zash.se/luaunbound.html                           

Old DNS resolver library will be used
More help can be found on our website, at https://prosody.im/doc/depends
**************************

Generating RSA private key, 2048 bit long modulus (2 primes)
.+++++
....................................................+++++
e is 65537 (0x010001)
Choose key size (2048): Key written to /var/lib/prosody/auth.opsales.sakura.ne.jp.key
Please provide details to include in the certificate config file.
Leave the field empty to use the default value or '.' to exclude the field.
countryName (JP): localityName (The Internet): organizationName (Your Organisation): organizationalUnitName (XMPP Department): commonName (auth.opsales.sakura.ne.jp): emailAddress (xmpp@auth.opsales.sakura.ne.jp): 
Config written to /var/lib/prosody/auth.opsales.sakura.ne.jp.cnf
Certificate written to /var/lib/prosody/auth.opsales.sakura.ne.jp.crt

Clearing symlinks in /etc/ssl/certs...
done.
Updating certificates in /etc/ssl/certs...
rehash: warning: skipping ca-certificates.crt,it does not contain exactly one certificate or CRL
125 added, 0 removed; done.
Running hooks in /etc/ca-certificates/update.d...

Replacing debian:ACCVRAIZ1.pem
Replacing debian:AC_RAIZ_FNMT-RCM.pem
Replacing debian:Actalis_Authentication_Root_CA.pem
Replacing debian:AffirmTrust_Commercial.pem
Replacing debian:AffirmTrust_Networking.pem
Replacing debian:AffirmTrust_Premium.pem
Replacing debian:AffirmTrust_Premium_ECC.pem
Replacing debian:Amazon_Root_CA_1.pem
Replacing debian:Amazon_Root_CA_2.pem
Replacing debian:Amazon_Root_CA_3.pem
Replacing debian:Amazon_Root_CA_4.pem
Replacing debian:Atos_TrustedRoot_2011.pem
Replacing debian:Autoridad_de_Certificacion_Firmaprofesional_CIF_A62634068.pem
Replacing debian:Baltimore_CyberTrust_Root.pem
Replacing debian:Buypass_Class_2_Root_CA.pem
Replacing debian:Buypass_Class_3_Root_CA.pem
Replacing debian:CA_Disig_Root_R2.pem
Replacing debian:CFCA_EV_ROOT.pem
Replacing debian:COMODO_Certification_Authority.pem
Replacing debian:COMODO_ECC_Certification_Authority.pem
Replacing debian:COMODO_RSA_Certification_Authority.pem
Replacing debian:Certigna.pem
Replacing debian:Certum_Trusted_Network_CA.pem
Replacing debian:Certum_Trusted_Network_CA_2.pem
Replacing debian:Comodo_AAA_Services_root.pem
Replacing debian:Cybertrust_Global_Root.pem
Replacing debian:D-TRUST_Root_Class_3_CA_2_2009.pem
Replacing debian:D-TRUST_Root_Class_3_CA_2_EV_2009.pem
Replacing debian:DigiCert_Assured_ID_Root_CA.pem
Replacing debian:DigiCert_Assured_ID_Root_G2.pem
Replacing debian:DigiCert_Assured_ID_Root_G3.pem
Replacing debian:DigiCert_Global_Root_CA.pem
Replacing debian:DigiCert_Global_Root_G2.pem
Replacing debian:DigiCert_Global_Root_G3.pem
Replacing debian:DigiCert_High_Assurance_EV_Root_CA.pem
Replacing debian:DigiCert_Trusted_Root_G4.pem
Replacing debian:E-Tugra_Certification_Authority.pem
Replacing debian:EC-ACC.pem
Replacing debian:Entrust.net_Premium_2048_Secure_Server_CA.pem
Replacing debian:Entrust_Root_Certification_Authority.pem
Replacing debian:Entrust_Root_Certification_Authority_-_EC1.pem
Replacing debian:Entrust_Root_Certification_Authority_-_G2.pem
Replacing debian:GDCA_TrustAUTH_R5_ROOT.pem
Replacing debian:GlobalSign_ECC_Root_CA_-_R4.pem
Replacing debian:GlobalSign_ECC_Root_CA_-_R5.pem
Replacing debian:GlobalSign_Root_CA.pem
Replacing debian:GlobalSign_Root_CA_-_R2.pem
Replacing debian:GlobalSign_Root_CA_-_R3.pem
Replacing debian:Go_Daddy_Class_2_CA.pem
Replacing debian:Go_Daddy_Root_Certificate_Authority_-_G2.pem
Replacing debian:Hellenic_Academic_and_Research_Institutions_ECC_RootCA_2015.pem
Replacing debian:Hellenic_Academic_and_Research_Institutions_RootCA_2011.pem
Replacing debian:Hellenic_Academic_and_Research_Institutions_RootCA_2015.pem
Replacing debian:Hongkong_Post_Root_CA_1.pem
Replacing debian:ISRG_Root_X1.pem
Replacing debian:IdenTrust_Commercial_Root_CA_1.pem
Replacing debian:IdenTrust_Public_Sector_Root_CA_1.pem
Replacing debian:Izenpe.com.pem
Replacing debian:Microsec_e-Szigno_Root_CA_2009.pem
Replacing debian:NetLock_Arany_=Class_Gold=_Főtanúsítvány.pem
Replacing debian:Network_Solutions_Certificate_Authority.pem
Replacing debian:OISTE_WISeKey_Global_Root_GB_CA.pem
Replacing debian:QuoVadis_Root_CA_1_G3.pem
Replacing debian:QuoVadis_Root_CA_2.pem
Replacing debian:QuoVadis_Root_CA_2_G3.pem
Replacing debian:QuoVadis_Root_CA_3.pem
Replacing debian:QuoVadis_Root_CA_3_G3.pem
Replacing debian:SSL.com_EV_Root_Certification_Authority_ECC.pem
Replacing debian:SSL.com_EV_Root_Certification_Authority_RSA_R2.pem
Replacing debian:SSL.com_Root_Certification_Authority_ECC.pem
Replacing debian:SSL.com_Root_Certification_Authority_RSA.pem
Replacing debian:SZAFIR_ROOT_CA2.pem
Replacing debian:SecureSign_RootCA11.pem
Replacing debian:SecureTrust_CA.pem
Replacing debian:Secure_Global_CA.pem
Replacing debian:Security_Communication_RootCA2.pem
Replacing debian:Security_Communication_Root_CA.pem
Replacing debian:Staat_der_Nederlanden_EV_Root_CA.pem
Replacing debian:Starfield_Class_2_CA.pem
Replacing debian:Starfield_Root_Certificate_Authority_-_G2.pem
Replacing debian:Starfield_Services_Root_Certificate_Authority_-_G2.pem
Replacing debian:SwissSign_Gold_CA_-_G2.pem
Replacing debian:SwissSign_Silver_CA_-_G2.pem
Replacing debian:T-TeleSec_GlobalRoot_Class_2.pem
Replacing debian:T-TeleSec_GlobalRoot_Class_3.pem
Replacing debian:TUBITAK_Kamu_SM_SSL_Kok_Sertifikasi_-_Surum_1.pem
Replacing debian:TWCA_Global_Root_CA.pem
Replacing debian:TWCA_Root_Certification_Authority.pem
Replacing debian:TeliaSonera_Root_CA_v1.pem
Replacing debian:USERTrust_ECC_Certification_Authority.pem
Replacing debian:USERTrust_RSA_Certification_Authority.pem
Replacing debian:XRamp_Global_CA_Root.pem
Replacing debian:certSIGN_ROOT_CA.pem
Replacing debian:ePKI_Root_Certification_Authority.pem
Replacing debian:AC_RAIZ_FNMT-RCM_SERVIDORES_SEGUROS.pem
Replacing debian:ANF_Secure_Server_Root_CA.pem
Replacing debian:Certigna_Root_CA.pem
Replacing debian:Certum_EC-384_CA.pem
Replacing debian:Certum_Trusted_Root_CA.pem
Replacing debian:Entrust_Root_Certification_Authority_-_G4.pem
Replacing debian:GLOBALTRUST_2020.pem
Replacing debian:GTS_Root_R1.pem
Replacing debian:GTS_Root_R2.pem
Replacing debian:GTS_Root_R3.pem
Replacing debian:GTS_Root_R4.pem
Replacing debian:GlobalSign_Root_CA_-_R6.pem
Replacing debian:GlobalSign_Root_E46.pem
Replacing debian:GlobalSign_Root_R46.pem
Replacing debian:Hongkong_Post_Root_CA_3.pem
Replacing debian:Microsoft_ECC_Root_Certificate_Authority_2017.pem
Replacing debian:Microsoft_RSA_Root_Certificate_Authority_2017.pem
Replacing debian:NAVER_Global_Root_Certification_Authority.pem
Replacing debian:OISTE_WISeKey_Global_Root_GC_CA.pem
Replacing debian:Trustwave_Global_Certification_Authority.pem
Replacing debian:Trustwave_Global_ECC_P256_Certification_Authority.pem
Replacing debian:Trustwave_Global_ECC_P384_Certification_Authority.pem
Replacing debian:UCA_Extended_Validation_Root.pem
Replacing debian:UCA_Global_G2_Root.pem
Replacing debian:certSIGN_Root_CA_G2.pem
Replacing debian:e-Szigno_Root_CA_2017.pem
Replacing debian:emSign_ECC_Root_CA_-_C3.pem
Replacing debian:emSign_ECC_Root_CA_-_G3.pem
Replacing debian:emSign_Root_CA_-_C1.pem
Replacing debian:emSign_Root_CA_-_G1.pem
Adding debian:auth.opsales.sakura.ne.jp.pem
done.
done.
Setting up jicofo (1.0-996-1) ...
Updating /etc/jitsi/jicofo/config to use jicofo.conf
Generating an empty jicofo.conf file
useradd: warning: the home directory already exists.
Not copying any file from skel directory into it.
Setting up coturn (4.5.0.7-1ubuntu2.18.04.3) ...
Adding group `turnserver' (GID 118) ...
Done.
Adding system user `turnserver' (UID 113) ...
Adding new user `turnserver' (UID 113) with group `turnserver' ...
Not creating home directory `/'.
Setting up luarocks (2.4.2+dfsg-1) ...
Making manifest for /usr/local/lib/luarocks/rocks
Warning: This looks like a local rocks tree, but you did not pass --local-tree.
Generating index.html for /usr/local/lib/luarocks/rocks
Setting up jitsi-meet (2.0.8319-1) ...
Setting up jitsi-meet-turnserver (1.0.6991-1) ...
Configuring turnserver
Processing triggers for systemd (237-3ubuntu10.56) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
Processing triggers for fontconfig (2.12.6-0ubuntu2) ...
Processing triggers for ufw (0.36-0ubuntu0.18.04.2) ...
Processing triggers for ureadahead (0.100.0-21) ...
Processing triggers for libc-bin (2.27-3ubuntu1.6) ...
voclabs:~/environment $ 
