u can choose the GNS3 VM, or not
i choose the latter, running in my local machine

Ubuntu:
```bash
sudo add-apt-repository ppa:gns3/ppa
sudo apt update
sudo apt install gns3-gui gns3-server
sudo apt install dynamips vpcs
# do NOT need to install VMware, which may be a little difficult on Ubuntu :)
```

Windows:
> [STFW](https://www.cnblogs.com/ghbuff/p/12676955.html)

just follow the blog, it's nice,
and maybe u will meet some trouble, like 

```txt
Can not connect to GNS3 VM
```
At least there are 3 point/way u need to notice:
1. netsh winsock reset
2. firewall problem
3. **the GNS3 version != GNS3 VM version**, which i meet

---

keys:
u don't need to download Cisco Router image/bin from its official website,
u can download it in GNS3, very easy and convenient
