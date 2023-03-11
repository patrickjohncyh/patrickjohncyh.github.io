### [FashionCLIP](https://huggingface.co/patrickjohncyh/fashion-clip)

`FashionCLIP` is a CLIP-like model develoepd to produce generalizable, multimodal product
representations for the fahion domain. We achieve this by fine-tuning a pretrained CLIP model
on a <image,caption> dataset dervied from a high quality fashion catalog containing over 800K
product. We study whether such fine-tuning is sufficient to produce product representations that
are zero-shot transferable to entirely new datasets and tasks.

<p align="center">
    <img src="assets/img/fashionclip.gif" width="75%">
</p>

Our results demonstrate strong zero-shot classification on a wide range of fashion datasets,
highlighting the merits of doamin specific fine-tuning. Furthermore, we study the _compositional_
and _grounding_ capabilities of CLIP-like models by creating synthetic products (see above ``_Nike Dress_'')
and testing FashionCLIP retrieval/classifcation on them. Our model is hosted on [Hugging Face](https://huggingface.co/patrickjohncyh/fashion-clip), check it out!

