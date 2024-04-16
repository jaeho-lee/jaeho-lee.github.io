---
title: "24S - Efficient ML"
weight: 5
---

## **EECE695E: Efficient ML Systems (Spring 2024)**

### **Team**
- **Instructor.** Jaeho Lee 이재호  
[firstname.lastname@postech.ac.kr](mailto:jaeho.lee@postech.ac.kr)
- **TA.** Hagyeong Lee 이하경  
[firstnamelastname@postech.ac.kr](mailto:hagyeonglee@postech.ac.kr)  

### **Location & Time**
- **Class.** Mondays & Wednesdays, 11:00AM--12:15PM, PIAI 122.
- **Office Hr.** Mondays 5:00PM--6:00PM, Eng. Building #407 (+ by appointment).


### **Schedule (tentative)**
- **W1. Deep Learning Recap** 
	- (2/19) [Introduction to Efficient ML & Logistics](https://docs.google.com/presentation/d/1AguRlUZBHTOY3G3KSlHg5f1UO7nLMLsrLKPOJ3C2Dg0/edit?usp=sharing)
	- (2/21) [Computations of DL](https://docs.google.com/presentation/d/1PvA5nT8hUXTrwSf3X39DtQWIwMB57q2qTAfhYmdEFZI)
- **W2. Sparsity**
	- (2/26) [Algorithmic aspects of pruning](https://docs.google.com/presentation/d/1l9bVqH2JEbeZJAkdWiUveNHPa9T7FleITWybaGs_KSU/edit?usp=sharing)
	- (2/28) [System aspects of pruning](https://docs.google.com/presentation/d/1gdYAYsyy7mrqIwQhLuQQ8RmsGfnfcNX-D7xxGGdNxAE/edit?usp=sharing)
- **W3. Quantization + Special Lecture**
	- (3/4) [Basic ideas of quantization](https://docs.google.com/presentation/d/1cUZ5eXRSdUwwE7IFP0ZB2n-mND3s8BpCfju6kEctRcI/edit?usp=sharing)
	- (~~3/6~~ -> 3/8, Fri) Special Lecture by Tae-ho Kim @ Nota
- **W4. Quantization + Distillation**
	- (3/11) [PTQ and QAT](https://docs.google.com/presentation/d/1T55I6R7z0x1wjU2kVmTt4HORXOacu5N1lelF_7EFrN4/edit?usp=sharing)
	- (3/13) [Distillation](https://docs.google.com/presentation/d/1s_ckHKwxJdXYhpH6Hcx3ku5oY6a4W_EQ017x3zuwXNE/edit?usp=sharing)
- **W5. Neural Architecture Search**
	- (3/18) [Search Space, Search Strategy (pt 1)](https://docs.google.com/presentation/d/1btbe25uE4_S6grlsYjEpAjuTFk6yR7W-RhVg2uMLRo8/edit?usp=sharing)
	- (3/20) [Search Strategy (pt 2), Performance Evaluation](https://docs.google.com/presentation/d/1UZUeh30bpszHAWYqR1x9T2f6AoxLBUxBIVCb4us8PwQ/edit?usp=sharing)
- **W6. Adaptation**
	- (3/25) [Continual Learning](https://docs.google.com/presentation/d/1Ao8_-vQGinhYr_38-xRdJT76kRKElyOz0vPOjv0JknA/edit?usp=sharing)
	- (3/27) [Meta-Learning & Test-time Training](https://docs.google.com/presentation/d/1zWbqx-wDDVHYC-IExCQs77XpthXvfGs_S09h_EjE94c/edit?usp=sharing)
- **W7. Parallelism**
	- (4/1) [Data and Model Parallelism](https://docs.google.com/presentation/d/1KRawgbDPOv6xti5HoWUL3jwLIjNhGnll4s9yc5ZRbYY/edit?usp=sharing)
	- (4/3) [Advanced Topics](https://docs.google.com/presentation/d/1-yUwgrGHYoHYwZa4CdET64tFHqznzPIEyC7azfkpkPE/edit?usp=sharing)
- **W8. (Mid-term week & Election Day)**
	- (4/8, 4/10)
- **W9. Model Merging & Editing**
	- (4/15) [Model Merging](https://docs.google.com/presentation/d/1DVAeuG9WM2Rd4MSkHhUo1uM6qKkI0CswUsz6siF7PGA/edit?usp=sharing)
	- (4/17) [Model Editing](https://docs.google.com/presentation/d/1FX4iyTLCaAr2e5Pyq0wCbTNjwxuP4gE1Ieg-NfTZjbI/edit?usp=sharing)
- **W10. Data Efficiency**
	- (4/22) Dataset Compression
	- (4/24) Data Compression
- **W11. Topics on LLM - 1**
	- (4/29) Transformers & LLM Basics
	- (5/1) Efficient Attention
- **W12. Topics on LLM - 2**
	- (5/6) Parameter-Efficient Fine-Tuning
	- (5/8) Quantization & Pruning
- **W13. Topics on LLM - 3** 
	- (5/13) Decoding & Batching Strategies
	- ~~(5/15)~~ Buddha's Day
- **W14. Topics on Diffusion Models**
	- (5/20) Diffusion Model Basics
	- (5/22) Acceleration & Tuning
- **W15. Presentations Week - 1**
	- (5/27, 5/29)
- **W16. Presentations Week - 2**
	- (6/3, 6/5)

### **Recommended Materials**
- **Blog Posts**
	- [LLM inference performance engineering](https://www.databricks.com/blog/llm-inference-performance-engineering-best-practices?fbclid=IwAR38VwybKZYFZNEFmAviNojzwlI7jLNLt-mFBV8ecwoBen_DzJ0CP0LG_-w) by Databricks
- **Videos**
	- [State-space models tutorial](https://www.youtube.com/watch?v=dKJEpOtVgXc) by Sasha Rush
	- [Trends in deep learning hardware](https://www.youtube.com/watch?v=HtrR1HRZIGA) by Bill Dally
- **Related Courses**
	- [Efficient deep learning systems](https://github.com/mryab/efficient-dl-systems) at HSE university and Yandex
	- [Machine learning compilation](https://mlc.ai/) at CMU
	- [TinyML and efficient deep learning](https://hanlab.mit.edu/courses/2023-fall-65940) at MIT
	- [Machine learning hardware and systems](https://abdelfattah-class.github.io/ece5545/sp23) at Cornell
	- [Advances in Foundation Models](https://stanford-cs324.github.io/winter2023/) at Stanford
- **Books and surveys**
	- [Algorithms for modern hardware](https://en.algorithmica.org/hpc/) by Sergey Slotin
	- [Efficient deep learning book](https://efficientdlbook.com/) by Menghani and Singh
	- [Compute-Efficient Deep Learning: Algorithmic Trends and Opportunities](https://arxiv.org/abs/2210.06640) by Bartoldson et al.