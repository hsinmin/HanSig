# HanSig

`HanSig` is a large-scale offline Chinese handwritten signature dataset. The `HanSig` dataset has the following characteristics:
 
1. It consists of 35,400 signature samples from 238 writers (17,700 genuine signatures and an equal number of skilled forgeries).
2. For each name, 20 genuine signatures and 20 corresponding forgeries were collected.
3. It incorporates the real-world property of intra-writer variations by collecting signatures for a specific name in three different styles.
4. The signatures cropped from the scanned images have been preprocessed by removing table lines and excess blanks around the signatures, ready for instant use. 
5. It is applicable to both random and skilled forgery verification tasks.

## Data Examples ##


- Examples of collected signatures in three styles: neat (top), normal (middle), and stylish (bottom).

<img src="./images/HanSig_Style1.jpg" alt="HanSig_Style1" height="116"></br> 
<img src="./images/HanSig_Style2.jpg" alt="HanSig_Style2" height="128"></br> 
<img src="./images/HanSig_Style3.jpg" alt="HanSig_Style3" height="123">

- Examples of collected genuine (top) and forged (bottom) signatures.

<img src="./images/HanSig_samples5.png" alt="HanSig_samples5" height="125"></br> 
<img src="./images/HanSig_samples6.png" alt="HanSig_samples6" height="123">

* Each genuine signature image has a unique filename such as *original\_w1\_2\_3.jpg*. This filename is organized as follows: 
  * *w1* refers to the first writer who signed this signature
  * *2* means this signature belongs to the second name
  * *3* refers to the third signature image of a specific name 
* Each forged signature image has a unique filename such as *forgery\_w1\_2\_3.jpg*. This filename is organized similar to that of genuine signature images.

## Getting the data ##

Please fill in [the form](https://forms.gle/9ohyvCmPL4TU3yCm9) to obtain instructions for downloading the `HanSig` dataset. In addition, please refer to above-mentioned Data Examples and [our work](https://arxiv.org/abs/2308.00428) for detailed description of this dataset.

## Citation ##

If you use this dataset in your research, please cite our work: </br>
**F.-H. Huang and H.-M. Lu. Multiscale Feature Learning Using Co-Tuplet Loss for Offline Handwritten Signature Verification. *arXiv preprint arXiv:2308.00428*, 2023.**

```
@misc{huang2023multiscale,
      title = {Multiscale Feature Learning Using Co-Tuplet Loss for Offline Handwritten Signature Verification}, 
      author = {Fu-Hsien Huang and Hsin-Min Lu},
      year = {2023},
      eprint = {2308.00428},
      archivePrefix = {arXiv},
      primaryClass = {cs.CV}
}
```
