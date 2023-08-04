<div align="center">
  <p>
    <a href="" >
      <img src="https://www.acs.com.hk/en/download-product-image-library/6187/6187-images-acr39t-a1.png" width="256px"/>
    </a>
  </p>
  <p>
    <h1 align="center">
    SmartCard ACR39T-A1
    </h1>
  </p>
</div>

Ubuntu 22.04 intallation instructions
## 🚀 Getting started
* [Download](https://www.acs.com.hk/en/products/331/acr39t-a1-smart-card-reader/) latest availabe driver for your card.
* Install `eoan` driver (or newer)
* Reboot your PC
* Open terminal and:
  ```bash
  sudo systemctl start pcscd
  sudo systemctl enable pcscd
  
  ```
> You are now able to use your ACS ACR39T-A1 smart card