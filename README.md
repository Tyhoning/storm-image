<p align="center">
  <h1 align="center">Storm Stream Processing Engine</h1>
  <p align="center">
    <a href="README_ZH.md"><strong>简体中文</strong></a> | <strong>English</strong>
  </p>

## Table of Contents

- [Repository Introduction](#repository-introduction)  
- [Prerequisites](#prerequisites)  
- [Image Specifications](#image-specifications)
- [Getting Help](#getting-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction  
[Apache Storm](https://github.com/apache/Storm) is a real-time computing framework tool. It can handle infinite data streams and provides real-time data processing capabilities with low latency and high throughput.

**Core Features:**
1. High performance, low latency: It can be applied to scenarios such as advertising search engines that require real-time response to advertisers' operations.
2. Distributed: It can easily handle scenarios with large amounts of data that cannot be processed by a single machine.
3. Scalability: With the development of business, the amount of data and computation is increasing, and the system can be horizontally expanded.
4. Fault tolerance: A single node failure does not affect the application.


**Architecture Design:**

![](./images/img001.png)

This project offers pre-configured [**Storm Stream Processing Engine**](https://marketplace.huaweicloud.com) images with Storm and its runtime environment pre-installed, along with deployment templates. Follow the guide to enjoy an "out-of-the-box" experience.

> **System Requirements:**
> - CPU: 4GHz or higher  
> - RAM: 8GB or more  
> - Disk: At least 60GB  

## Prerequisites  
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Specifications  

| Image Version                                                  | Description                                             | Notes |  
|----------------------------------------------------------------|---------------------------------------------------------|-------|  
| [Storm2.8.2-kunpeng-v1.0](https://github.com/HuaweiCloudDeveloper/Storm-image/tree/Storm2.8.2-kunpeng-v1.0) | Deployed on Kunpeng servers with Huawei Cloud EulerOS 2.0 64bit |  | 

## Getting Help
- Submit an [issue](https://github.com/HuaweiCloudDeveloper/Storm-image/issues)
- Contact Huawei Cloud Marketplace product support

## How to Contribute
- Fork this repository and submit a merge request.
- Update README.md synchronously based on your open-source mirror information.
