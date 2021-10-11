# ThereminProject
Creation and assambly of a theremin(musical instrument) from electrical circuits 
<p align="center">
<img width=500px src="images/final3.png" alt="explode"></a>

<div align="center">
<img width=100px src="https://img.shields.io/badge/status-finished-green" alt="explode"></a>
<img width=80px src="https://img.shields.io/badge/license-CC-blue" alt="explode"></a>
</div>

## Table of contents 
- [Table of Contents](#table-of-contents)
- [General info](#general-info)
- [Parts required](#parts-required)
- [Circuit and first assambly](#circuit-and-first-assambly)


## General info
### Authors

@ [**Ivan Porras Estebanez**](https://github.com/Ivan-Porras)

@ [**Jimena de la Fuente Alcalde**](https://instagram.com/_jimawariii_03_?utm_medium=copy_link)

### References

@ [**GreatScottLab**](https://www.instructables.com/member/GreatScottLab/)

### Other information: 

@ **InitDate:** 23/02/2021

@ **PresentationDate:** 27/6/2021 


## Parts required
This project requires some electrical componentes(capacitators, resistors, integrated circuits ...) 
Here I gonna put the list of components that I used to complete it(You can find all this components in pages like aliexpress or ebay): 
- 1x [CD4093 NAND IC](https://es.aliexpress.com/item/1005001922727519.html?spm=a2g0o.productlist.0.0.1f9f2dd8dP3mdU&algo_pvid=a6ead60f-3b0a-493a-a8fc-e203e4897054&aem_p4p_detail=202110110350132362705910756620013918823&algo_exp_id=a6ead60f-3b0a-493a-a8fc-e203e4897054-6&pdp_ext_f=%7B%22sku_id%22%3A%2212000018120013015%22%7D)
- 1x [MCP602 OpAmp](https://es.aliexpress.com/item/32459211616.html?spm=a2g0o.productlist.0.0.333f4c9eiVFawj&algo_pvid=409f117a-8b95-41cb-946f-04548cbbd9a2&algo_exp_id=409f117a-8b95-41cb-946f-04548cbbd9a2-9&pdp_ext_f=%7B%22sku_id%22%3A%2256403604204%22%7D)
- 2x [100pF Capacitator](https://es.aliexpress.com/item/1005001958775985.html?spm=a2g0o.productlist.0.0.248c4dab32kasv&algo_pvid=52309e2a-cc47-48b1-b793-d74953763794&aem_p4p_detail=202110110352054216941306177600013922384&algo_exp_id=52309e2a-cc47-48b1-b793-d74953763794-0&pdp_ext_f=%7B%22sku_id%22%3A%2212000018228270124%22%7D)
- 1x [1nF(1000pf) Capacitor](https://es.aliexpress.com/item/1005001969200393.html?spm=a2g0o.productlist.0.0.2a1c37b1BcAsSs&algo_pvid=f1a4dd47-0c42-40a8-9433-48ce521ad231&aem_p4p_detail=202110110406228649250402418600013976495&algo_exp_id=f1a4dd47-0c42-40a8-9433-48ce521ad231-0&pdp_ext_f={"sku_id"%3A"12000018268193596"})
- 1x [4.7µF Capacitor](https://es.aliexpress.com/item/1005002075527957.html?spm=a2g0o.productlist.0.0.77ec5e50Ad7Ope&algo_pvid=7daaeccd-a98e-4e5c-9f75-c8a087087536&aem_p4p_detail=202110110407566240865031938800013163840&algo_exp_id=7daaeccd-a98e-4e5c-9f75-c8a087087536-0&pdp_ext_f=%7B%22sku_id%22%3A%2212000018654903128%22%7D)
- 6x [10k Resistor](https://es.aliexpress.com/item/32952657927.html?spm=a2g0o.productlist.0.0.8ba335d9ijZQ4K&algo_pvid=2e371b20-11c3-42b3-b683-10e5aa3811cd&algo_exp_id=2e371b20-11c3-42b3-b683-10e5aa3811cd-0&pdp_ext_f=%7B%22sku_id%22%3A%2266353322894%22%7D)
- 1x [5.1k Resistor](https://es.aliexpress.com/item/32952657927.html?spm=a2g0o.productlist.0.0.8ba335d9ijZQ4K&algo_pvid=2e371b20-11c3-42b3-b683-10e5aa3811cd&algo_exp_id=2e371b20-11c3-42b3-b683-10e5aa3811cd-0&pdp_ext_f=%7B%22sku_id%22%3A%2266353322894%22%7D)
- 1x [6.8k Resistor](https://es.aliexpress.com/item/32952657927.html?spm=a2g0o.productlist.0.0.8ba335d9ijZQ4K&algo_pvid=2e371b20-11c3-42b3-b683-10e5aa3811cd&algo_exp_id=2e371b20-11c3-42b3-b683-10e5aa3811cd-0&pdp_ext_f=%7B%22sku_id%22%3A%2266353322894%22%7D)
- 2x [10k Potentiometer](https://es.aliexpress.com/item/1005002292828444.html?spm=a2g0o.productlist.0.0.47c84fe655HtHZ&algo_pvid=d904a206-faa1-4c1a-91fc-564c2b038df7&aem_p4p_detail=20211011041027346059857318910014188431&algo_exp_id=d904a206-faa1-4c1a-91fc-564c2b038df7-0&pdp_ext_f=%7B%22sku_id%22%3A%2212000019947320944%22%7D)
- 1x [Antenna](https://es.aliexpress.com/item/1005003211915613.html?spm=a2g0o.productlist.0.0.7f701dd2soDN0u&algo_pvid=306ad35c-5a81-450c-9a67-29ac22393050&aem_p4p_detail=202110110410517544220031519830013991168&algo_exp_id=306ad35c-5a81-450c-9a67-29ac22393050-2&pdp_ext_f=%7B%22sku_id%22%3A%2212000024683718642%22%7D)
- 1x [Power Jack](https://es.aliexpress.com/item/4001146018106.html?spm=a2g0o.productlist.0.0.517722f4IZy4p1&algo_pvid=0875037d-9cf7-4f1e-9f04-ad46b01e2a98&algo_exp_id=0875037d-9cf7-4f1e-9f04-ad46b01e2a98-28&pdp_ext_f=%7B%22sku_id%22%3A%2210000014889737303%22%7D)
- 1x [Audio Jack](https://es.aliexpress.com/item/4001146018106.html?spm=a2g0o.productlist.0.0.517722f4IZy4p1&algo_pvid=0875037d-9cf7-4f1e-9f04-ad46b01e2a98&algo_exp_id=0875037d-9cf7-4f1e-9f04-ad46b01e2a98-28&pdp_ext_f=%7B%22sku_id%22%3A%2210000014889737303%22%7D)
- [Printed circuit board](https://es.aliexpress.com/item/4000033405046.html?spm=a2g0o.productlist.0.0.64d83201mtCfsv&algo_pvid=36f320ca-1aed-44e1-ac46-a1dbb836e3c5&algo_exp_id=36f320ca-1aed-44e1-ac46-a1dbb836e3c5-15&pdp_ext_f=%7B%22sku_id%22%3A%2212000020757514458%22%7D)
- [Housing](https://www.amazon.de/gp/product/B0056BPREM/ref=as_li_qf_sp_asin_il_tl?ie=UTF8&tag=great043-21&camp=1638&creative=6742&linkCode=as2&creativeASIN=B0056BPREM&linkId=7268437bb45f7b3b0dee3759b5275222)(Also you can use a 3D printer)  

 **Optional(Personal Recommendation):**
- 1x [>= 1A 5V Power adaptor](https://es.aliexpress.com/item/32844702891.html?spm=a2g0o.productlist.0.0.22443e75z8R1uB&algo_pvid=814149db-685e-4c27-b236-2c19e61b7e5b&algo_exp_id=814149db-685e-4c27-b236-2c19e61b7e5b-52&pdp_ext_f=%7B%22sku_id%22%3A%2265171865046%22%7D)
- 1x [Portable mini speaker](https://es.aliexpress.com/item/1005003053429529.html?spm=a2g0o.productlist.0.0.32b95970dXEWev&algo_pvid=33723007-0a05-4028-ae22-84704daf29ae&algo_exp_id=33723007-0a05-4028-ae22-84704daf29ae-12&pdp_ext_f=%7B%22sku_id%22%3A%2212000023555611420%22%7D)

(Only in you want to do a previous circuit to test it) 
- 1x [Protoboard](https://es.aliexpress.com/item/32711841420.html?spm=a2g0o.productlist.0.0.311f3765E7gF4R&algo_pvid=2b691f68-db34-46a7-93b8-a29ab5e5c58d&algo_exp_id=2b691f68-db34-46a7-93b8-a29ab5e5c58d-2&pdp_ext_f=%7B%22sku_id%22%3A%2260928567388%22%7D)
- [Male to Male wires](https://es.aliexpress.com/item/4000203371860.html?spm=a2g0o.productlist.0.0.525b4636Op6nXa&algo_pvid=65911792-bfc6-4007-8010-d973aad76f3e&aem_p4p_detail=2021101105004514764101802082500014142017&algo_exp_id=65911792-bfc6-4007-8010-d973aad76f3e-1&pdp_ext_f=%7B%22sku_id%22%3A%2210000000774493026%22%7D) 


## Circuit and first assambly
To test the connections before soldering the circuit we use a protoboard, the wires connection in the pics cal look little caotic (because I also used this project to teach my gf about circuits and how to use the protoboard) but it's not difficult to replicate it. 

**This is the circuit diagram:**
<p align="center">
<img width=500px src="images/circuito.png" alt="explode"></a>

**Final Protoboard Result:**

<img width=400px src="images/protofinal3.jpeg" alt="explode"></a>
<img width=400px src="images/protofinal2.jpeg" alt="explode"></a>

**Sound test:**
<img width=400px src="images/cap.jpeg" alt="explode"></a>


## Final assambly 
Now it's time to take our tin soldering iron and the printed circuit boards and start soldering the ciruit. Take care with the potenciometers, it can be difficult to weld for starters. 



## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
