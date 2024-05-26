# Diffie-Hellman Key Exchange Jupyter-Colab Challenges

This object is a service of Jupyter notebooks that can be imported into Google 
Colab (the I/O of the notebooks is compatible with Colab). Students should 
work in pairs to explore DHKE/RSA. The notebooks should be used in the 
following order:

### 1-introducing-dhke

- Introduces running a Jupyter/Python notebook
- Demonstrates DHKE/RSA in simple math primitives
- [Hosted Colab](https://colab.research.google.com/drive/1wycpR6m1LmtMxRMPmH8aOKKUkD0KnoYN)

### 2-partner-key-exchange

- Allows two students in different Jupyter notebooks to exchange a secret 
  over an untrusted channel using magic wormhole on the Python host runner
- Uses `cis.highline.edu` as the appid to uniquely identify the endpoints of 
  the tunnel, and should probably be changed
- [Hosted Colab](https://colab.research.google.com/drive/1PfmzVRCZy-D54nwnU79ngwA5y7U63GAy)

### 2.5-dhke-parameters-{alice,bob}

- Extension to partner key exchange that requires Alice and Bob to pick values
  from a standard 
- [Hosted Colab A](https://colab.research.google.com/drive/1rFJ4W2J3WvwVViFeCQdXWXnUmKiPGTdd)
- [Hosted Colab B](https://colab.research.google.com/drive/1STnlsAnp0-lVAM7Rdi1CCwfIWSg2ELGi)

### 3-challenge-derive-the-secret

- Challenge that asks students to bruteforce deriving the secret component of 
  DKHE/RSA using small values
- [Hosted Colab](https://colab.research.google.com/drive/1z7Mlz-gkNbrzRwhX4heTHd_somk69uav)

### 4-challenge-key-exchange-rfc-3526

- Challenge that asks students to implement message exchange in RFC 3526, 
  with authenticated messaging
- [Hosted Colab](https://colab.research.google.com/drive/1llmjDizrSbKvGFzJ_9CW7x4yRFRWB-6x)

## Learning Outcomes

1. Solve RSA shared secret derivation given simple inputs
2. Implement authenticated key exchange
3. Decrypt objects based captured ciphertext and inputs
4. Encrypt and exchange messages between hosted runtimes
5. Run Jupyter notebooks

[![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


