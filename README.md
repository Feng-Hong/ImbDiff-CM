# Improving Diffusion Models for Class-Imbalanced Training Data via Capacity Manipulation (ICLR 2026)


## 📖 Overview

While diffusion models have achieved remarkable success in image generation, they struggle with **class-imbalanced datasets**, often leading to significant performance degradation on minority classes. 

Our paper identifies **model capacity allocation** as a key factor: majority classes tend to monopolize an unnecessarily large portion of the model's capacity, restricting the representation of minority classes. To address this, we propose **Capacity Manipulation (CM)**.

### Key Contributions:
* **Capacity Reservation:** We leverage low-rank decomposition to explicitly partition model parameters into a component for general/majority knowledge and a reserved component for minority expertise.
* **Capacity Manipulation Loss:** We introduce a novel loss ($L_{CM}$) that strategically allocates knowledge to the reserved capacity during training using consistency and diversity objectives.
* **Efficiency:** CM reallocates existing capacity without increasing model size, meaning it introduces **zero additional inference overhead**.
* **Orthogonality:** CM is orthogonal to existing imbalanced learning methods and can be integrated with them for further performance boosts.


---

* **[Coming Soon]** We are currently organizing the source code.

---

## 📝 Citation

If you find our work or this codebase useful, please consider citing our paper:

```bibtex
@inproceedings{hong2026improving,
  title={Improving Diffusion Models for Class-Imbalanced Training Data via Capacity Manipulation},
  author={Hong, Feng and Yao, Jiangchao and Shen, Yifei and Li, Dongsheng and Zhang, Ya and Wang, Yanfeng},
  booktitle={International Conference on Learning Representations (ICLR)},
  year={2026}
}
