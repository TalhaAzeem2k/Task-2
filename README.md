# Task-2
Docker Commands with outputs

#docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES 

#docker stop sharp_bassi
sharp_bassi  (The container is stooped/verified too from the list)

#docker rm sharp_bassi
sharp_bassi  (Container removed from the docker Containers list)

#docker exec eloquent_nobel cat /etc/hosts
127.0.0.1       localhost
::1     localhost ip6-localhost ip6-loopback
fe00::0 ip6-localnet
ff00::0 ip6-mcastprefix
ff02::1 ip6-allnodes
ff02::2 ip6-allrouters
172.17.0.2      3aa3be0463c4

#docker inspect eloquent_nobel
[
    {
        "Id": "3aa3be0463c4f1f10541eaeceb644938e7c4543a7c13ebdbd7579b64d9127853",
        "Created": "2023-08-10T20:02:47.807584799Z",
        "Path": "/docker-entrypoint.sh",
        "Args": [
            "nginx",
            "-g",
            "daemon off;"
        ],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 29070,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2023-08-10T20:55:03.319379056Z",
            "FinishedAt": "2023-08-10T20:04:32.430540046Z"
        },
        "Image": "sha256:89da1fb6dcb964dd35c3f41b7b93ffc35eaf20bc61f2e1335fea710a18424287",
        "ResolvConfPath": "/var/lib/docker/containers/3aa3be0463c4f1f10541eaeceb644938e7c4543a7c13ebdbd7579b64d9127853/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/3aa3be0463c4f1f10541eaeceb644938e7c4543a7c13ebdbd7579b64d9127853/hostname",
        "HostsPath": "/var/lib/docker/containers/3aa3be0463c4f1f10541eaeceb644938e7c4543a7c13ebdbd7579b64d9127853/hosts",
        "LogPath": "/var/lib/docker/containers/3aa3be0463c4f1f10541eaeceb644938e7c4543a7c13ebdbd7579b64d9127853/3aa3be0463c4f1f10541eaeceb644938e7c4543a7c13ebdbd7579b64d9127853-json.log",
        "Name": "/eloquent_nobel",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "default",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                22,
                74
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "host",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": false,
            "PidsLimit": null,
            "Ulimits": null,
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/e5019ce5c4ec0e029e7f1ddec7ea9bb52592c9da0ca542f85f849977f74d4e06-init/diff:/var/lib/docker/overlay2/bf95f1233a4b2dcb836d5daf80eda08cf024d5cd7cc5c89440a6d9cb6896db08/diff:/var/lib/docker/overlay2/ac7eda605d70cfbfe88c3e160a8744db3a8576f8004f0960df956938d5e7018f/diff:/var/lib/docker/overlay2/6c37b906e497f1a072aa8451ef9f72beb82e178c5f8c459bab898520d4b923b3/diff:/var/lib/docker/overlay2/8437bef806f056084df34be0f1a0e6258a240aab412ec753c46b141063fc398d/diff:/var/lib/docker/overlay2/2e9eabacbf7f49c3ba9bcbb720919e84ffa2abe14c7c89c4f8608556e269b933/diff:/var/lib/docker/overlay2/cc468e0e62e8aced79f7e53af929cbe66eb6584c7695aaf6498c07b1334b2dc4/diff:/var/lib/docker/overlay2/206cac303ea0927bd51071055bdc43969c70938ac00a879eb99639d1283ea210/diff",
                "MergedDir": "/var/lib/docker/overlay2/e5019ce5c4ec0e029e7f1ddec7ea9bb52592c9da0ca542f85f849977f74d4e06/merged",
                "UpperDir": "/var/lib/docker/overlay2/e5019ce5c4ec0e029e7f1ddec7ea9bb52592c9da0ca542f85f849977f74d4e06/diff",
                "WorkDir": "/var/lib/docker/overlay2/e5019ce5c4ec0e029e7f1ddec7ea9bb52592c9da0ca542f85f849977f74d4e06/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "3aa3be0463c4",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": true,
            "AttachStderr": true,
            "ExposedPorts": {
                "80/tcp": {}
            },
            "Tty": false,
            "OpenStdin": false,
            "StdinOnce": false,
            "Env": [
                "PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin",
                "NGINX_VERSION=1.25.1",
                "NJS_VERSION=0.7.12",
                "PKG_RELEASE=1~bookworm"
            ],
            "Cmd": [
                "nginx",
                "-g",
                "daemon off;"
            ],
            "Image": "nginx",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": [
                "/docker-entrypoint.sh"
            ],
            "OnBuild": null,
            "Labels": {
                "maintainer": "NGINX Docker Maintainers \u003cdocker-maint@nginx.com\u003e"
            },
            "StopSignal": "SIGQUIT"
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "058e402f3ab668755d236226c03d07d50ac7527e570562635c67d87fd48d8529",
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "Ports": {
                "80/tcp": null
            },
            "SandboxKey": "/var/run/docker/netns/058e402f3ab6",
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "c6f3e2df18fd9fb8ddb62b6fe53f31813d3c5e7f1e144dd481e61c25af66dc78",
            "Gateway": "172.17.0.1",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "172.17.0.2",
            "IPPrefixLen": 16,
            "IPv6Gateway": "",
            "MacAddress": "02:42:ac:11:00:02",
            "Networks": {
                "bridge": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": null,
                    "NetworkID": "efb4649f3d89d59d6e25cdd723964be85725b355f15918d7d71d67c09af86614",
                    "EndpointID": "c6f3e2df18fd9fb8ddb62b6fe53f31813d3c5e7f1e144dd481e61c25af66dc78",
                    "Gateway": "172.17.0.1",
                    "IPAddress": "172.17.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "MacAddress": "02:42:ac:11:00:02",
                    "DriverOpts": null
                }
            }
        }
    }
]

#docker commit eloquent_nobel myapp-image
sha256:8dca7db2ee8b4c3b4cdec8e42e3ddc69fdb263861af8b91ad1f44a6f7bd9fa5e


#docker stats
CONTAINER ID   NAME             CPU %     MEM USAGE / LIMIT     MEM %     NET I/O       BLOCK I/O   PIDS
3aa3be0463c4   eloquent_nobel   0.00%     11.87MiB / 7.703GiB   0.15%     1.16kB / 0B   0B / 0B     9

#docker top eloquent_nobel
UID                 PID                 PPID                C                   STIME               TTY                 TIME                CMD
root                17077               17057               0                   11:10               ?                   00:00:00            nginx: master process nginx -g daemon off;
uuidd               17113               17077               0                   11:10               ?                   00:00:00            nginx: worker process
uuidd               17114               17077               0                   11:10               ?                   00:00:00            nginx: worker process
uuidd               17115               17077               0                   11:10               ?                   00:00:00            nginx: worker process
uuidd               17116               17077               0                   11:10               ?                   00:00:00            nginx: worker process
uuidd               17117               17077               0                   11:10               ?                   00:00:00            nginx: worker process
uuidd               17118               17077               0                   11:10               ?                   00:00:00            nginx: worker process
uuidd               17119               17077               0                   11:10               ?                   00:00:00            nginx: worker process
uuidd               17120               17077               0                   11:10               ?                   00:00:00            nginx: worker process


#docker start eloquent_nobel
eloquent_nobel

#docker pause eloquent_nobel
eloquent_nobel

#docker unpause eloquent_nobel
eloquent_nobel

#docker rename  eloquent_nobel talhamodelx

#docker attach talhamodelx
2023/08/11 11:30:34 [notice] 1#1: signal 3 (SIGQUIT) received, shutting down
2023/08/11 11:30:34 [notice] 22#22: gracefully shutting down
2023/08/11 11:30:34 [notice] 23#23: gracefully shutting down
2023/08/11 11:30:34 [notice] 24#24: gracefully shutting down
2023/08/11 11:30:34 [notice] 22#22: exiting
2023/08/11 11:30:34 [notice] 24#24: exiting
2023/08/11 11:30:34 [notice] 25#25: gracefully shutting down
2023/08/11 11:30:34 [notice] 26#26: gracefully shutting down
2023/08/11 11:30:34 [notice] 29#29: gracefully shutting down
2023/08/11 11:30:34 [notice] 26#26: exiting
2023/08/11 11:30:34 [notice] 27#27: gracefully shutting down
2023/08/11 11:30:34 [notice] 25#25: exiting
2023/08/11 11:30:34 [notice] 27#27: exiting
2023/08/11 11:30:34 [notice] 29#29: exiting
2023/08/11 11:30:34 [notice] 26#26: exit
2023/08/11 11:30:34 [notice] 25#25: exit
2023/08/11 11:30:34 [notice] 27#27: exit
2023/08/11 11:30:34 [notice] 29#29: exit
2023/08/11 11:30:34 [notice] 22#22: exit
2023/08/11 11:30:34 [notice] 28#28: gracefully shutting down
2023/08/11 11:30:34 [notice] 24#24: exit
2023/08/11 11:30:34 [notice] 28#28: exiting
2023/08/11 11:30:34 [notice] 28#28: exit
2023/08/11 11:30:34 [notice] 23#23: exiting
2023/08/11 11:30:34 [notice] 23#23: exit
2023/08/11 11:30:34 [notice] 1#1: signal 17 (SIGCHLD) received from 22
2023/08/11 11:30:34 [notice] 1#1: worker process 22 exited with code 0
2023/08/11 11:30:34 [notice] 1#1: worker process 24 exited with code 0
2023/08/11 11:30:34 [notice] 1#1: worker process 26 exited with code 0
2023/08/11 11:30:34 [notice] 1#1: worker process 29 exited with code 0
2023/08/11 11:30:34 [notice] 1#1: signal 29 (SIGIO) received
2023/08/11 11:30:34 [notice] 1#1: signal 17 (SIGCHLD) received from 25
2023/08/11 11:30:34 [notice] 1#1: worker process 25 exited with code 0
2023/08/11 11:30:34 [notice] 1#1: signal 29 (SIGIO) received
2023/08/11 11:30:34 [notice] 1#1: signal 17 (SIGCHLD) received from 28
2023/08/11 11:30:34 [notice] 1#1: worker process 28 exited with code 0
2023/08/11 11:30:34 [notice] 1#1: signal 29 (SIGIO) received
2023/08/11 11:30:35 [notice] 1#1: signal 17 (SIGCHLD) received from 23
2023/08/11 11:30:35 [notice] 1#1: worker process 23 exited with code 0
2023/08/11 11:30:35 [notice] 1#1: signal 29 (SIGIO) received
2023/08/11 11:30:35 [notice] 1#1: signal 17 (SIGCHLD) received from 27
2023/08/11 11:30:35 [notice] 1#1: worker process 27 exited with code 0


