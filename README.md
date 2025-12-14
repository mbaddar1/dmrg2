# dmrg2
An enhanced DMRG Algorithm designed for Least-Square Regression Problems


Example blog posts --> papers to follow


https://medium.com/huggingface/distilbert-8cf3380435b5

https://arxiv.org/abs/1910.01108


others 


1) DistilBERT (Hugging Face)
Blog (authors): https://medium.com/huggingface/smaller-faster-cheaper-lighter-introducing-dilbert-a-distilled-version-of-bert-8cf3380435b5
Paper:          https://arxiv.org/abs/1910.01108

2) ALBERT (Google Research)
Blog (authors): https://research.google/blog/albert-a-lite-bert-for-self-supervised-learning-of-language-representations/
Paper:          https://arxiv.org/abs/1909.11942

3) BERT (Google Research)
Blog (authors): https://research.google/blog/open-sourcing-bert-state-of-the-art-pre-training-for-natural-language-processing/
Paper:          https://arxiv.org/abs/1810.04805


ChatGPT link
https://chatgpt.com/share/693ee639-1c70-8010-8a43-35bc8d51357d



# Similar Repos
One to focus on 

https://github.com/tenpy/tenpy/blob/main/tenpy/algorithms/dmrg.py

why ? capsulated lib with good code


Here are **real GitHub repositories with Python DMRG implementations** (educational and research), all relevant if you want to *read/extend pythonic code for density-matrix renormalization group (DMRG)*:

### 📌 Core Python DMRG Repositories

1. **MiniDMRG** — educational DMRG in pure Python
   [https://github.com/YemingMeng/MiniDMRG](https://github.com/YemingMeng/MiniDMRG) ([GitHub][1])
   A lightweight, NumPy-based DMRG implementation under ~1000 lines, good for stepping through the algorithm logic. ([GitHub][1])

2. **dmrg101: Python implementation + tutorial**
   [https://github.com/iglpdc/dmrg101](https://github.com/iglpdc/dmrg101) ([GitHub][2])
   A Python DMRG code with tutorial and exercises — helps understand core steps. ([GitHub][2])

3. **simple-DMRG-with-MPS** — basic DMRG using matrix product states
   [https://github.com/Qottmann/simple-DMRG-with-MPS](https://github.com/Qottmann/simple-DMRG-with-MPS) ([GitHub][3])
   Clear Python notebook demonstrating DMRG sweeps on MPS. ([GitHub][3])

4. **DMRGPy (Jose Lado)** — Python interface + example code
   [https://github.com/joselado/dmrgpy](https://github.com/joselado/dmrgpy) ([GitHub][4])
   Python library for spin chains & fermionic systems using DMRG (with ITensor backend). ([GitHub][4])

5. **TensorTrain DMRG notebooks** — teaching code using TensorNetwork
   [https://github.com/DerWeh/tensortrain](https://github.com/DerWeh/tensortrain) ([GitHub][5])
   Includes notebooks like `02_dmrg.ipynb` explaining DMRG sweep steps with TensorNetwork. ([GitHub][5])

---

### 📌 Useful Tensor Network Python Libraries (with DMRG support)

These aren’t “pure DMRG only”, but they include **DMRG routines and ecosystem support**:

✅ **TeNPy — Tensor Network Python**
[https://github.com/tenpy/tenpy](https://github.com/tenpy/tenpy) ([GitHub][6])
A full tensor-network library with DMRG (MPS/MPO) implementations and examples — suitable for more serious research. ([GitHub][6])

📌 **TeNPy toy codes (tutorials)**
[https://github.com/tenpy/tenpy_toycodes](https://github.com/tenpy/tenpy_toycodes) ([GitHub][7])
Small Python example codes used in tensor network tutorials and schools. ([GitHub][7])

⚠️ *PyTeNet* (Tensor Network operations) doesn’t have full standalone DMRG but provides the building blocks:
[https://github.com/cmendl/pytenet](https://github.com/cmendl/pytenet) ([GitHub][8])

---

## 🧠 How to Use These Repos

**Quick learning path**

1. **MiniDMRG** – read the code (~1000 lines) to understand sweep logic.
2. **dmrg101 / simple-DMRG-with-MPS** – follow tutorial notebooks.
3. **TensorTrain notebooks** – see sweep behaviour with TensorNetwork.
4. **TeNPy** – scale up to real problems (spin chains, Hubbard models).

---

If you want, I can also point you to **Jupyter notebooks that walk through DMRG step by step** or help extract some of these into a **readable pseudo-code summary**.

[1]: https://github.com/YemingMeng/MiniDMRG?utm_source=chatgpt.com "YemingMeng/MiniDMRG"
[2]: https://github.com/iglpdc/dmrg101?utm_source=chatgpt.com "iglpdc/dmrg101: Python implementation of the DMRG ..."
[3]: https://github.com/Qottmann/simple-DMRG-with-MPS?utm_source=chatgpt.com "Qottmann/simple-DMRG-with-MPS"
[4]: https://github.com/joselado/dmrgpy?utm_source=chatgpt.com "joselado/dmrgpy"
[5]: https://github.com/DerWeh/tensortrain?utm_source=chatgpt.com "DerWeh/tensortrain: Tensor methods (DMRG and TDVP) ..."
[6]: https://github.com/tenpy/tenpy?utm_source=chatgpt.com "Tensor Network Python (TeNPy)"
[7]: https://github.com/tenpy/tenpy_toycodes?utm_source=chatgpt.com "tenpy/tenpy_toycodes: Tutorials to Tensor Network ..."
[8]: https://github.com/cmendl/pytenet?utm_source=chatgpt.com "cmendl/pytenet: Python implementation of quantum tensor ..."
