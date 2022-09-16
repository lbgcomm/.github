# [Laid Back Gaming](https://lbgaming.co)
## Who Are We?
We are a gaming community that hosts modded game servers in many games such as Counter-Strike, Rust, Garry's Mod, and Team fortress 2. We are a more laid-back gaming community and serve more loosened rules compared to a majority of other gaming communities. Please keep in mind this community allows **NSFW** content in certain channels/game servers (Not Suitable For Work) as long as it's legal and not directly insulting anybody.

We support [The Modding Community](https://moddingcommunity.com/) and love working with modders/content creators to host content on our game servers to the community!

## Our Infrastructure
Since a majority of games we host modded servers for include server software that is limited to single threads/cores in regards to performance, we try to purchase consumer CPU/memory hardware from hosting providers. Our main dedicated server for our game servers includes an **AMD Ryzen 9 5900X** processor along with 32 GBs of DDR4 RAM, and 512 GBs SSD NVMe. As we make more profit from our premium system, we will be upgrading our dedicated servers and Anycast network (for (D)DoS protection). We hope to build our own dedicated servers with high-performing CPUs and water-cooling so our modded servers have the best performance possible.

**WARNING** - We are **not** a hosting provider and do not offer modded servers/hardware to other server owners. Everything belongs to the community (LBG) and we have our own hand-picked staff, etc.

### Our Unique Anycast Network For (D)DoS Protection & Latency
We have a unique Anycast network that was built by [@gamemann](https://github.com/gamemann) (Christian Deacon) and [@Synkstar](https://github.com/Synkstar). [@gamemann](https://github.com/gamemann) was focusing on the Anycast network's packet processing software which was made last year (2021), but cannot devote as much time due to [The Modding Community](https://moddingcommunity.com/). Therefore, [@Synkstar](https://github.com/Synkstar) has taken over the project's software code/features.

Additionally, the firewall/router we've made including the following advantages and features.

* Packet processing software utilizes the Linux kernel's [XDP](https://www.iovisor.org/technology/xdp) hook through [(e)BPF](https://ebpf.io/). This enables fast packet processing which in return combats (D)DoS attacks **more efficiently** and **lowers** user's latency to our modded game servers.
* Allows us to implement our own (D)DoS protection/mitigation filters to combat layer 3 - 7 attacks.
* We own the ASN and IP blocks which allows us to scale the Anycast network capacity to meet our needs.
* More control over monitoring the whole network.
* Many other pros!

## Our Team
### Owners
* [@gamemann](https://github.com/gamemann) (AKA Christian Deacon)
* [@Synkstar](https://github.com/Synkstar)

### Community Managers
* Toxic
* X2D
* Pedro 

### System Administrators
* [@57_Wolve](https://github.com/57_Wolve)
* Kurante (AKA Fafy)
