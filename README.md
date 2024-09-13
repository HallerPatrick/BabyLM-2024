# Submission for the BabyLM 2024 Shared Task


# Benchmark Results
We include links to the predictions, as well as the model links.

The prediction files can easily be downloaded with:

```bash
# Strict-Small Track
wget https://github.com/HallerPatrick/BabyLM-2024/blob/main/hgrn2_pile_10m_distill_babylm_textonly_predictions.json.gz

# Strict Track
wget https://github.com/HallerPatrick/BabyLM-2024/blob/main/hgrn2_pile_100m_distill_babylm_textonly_predictions.json.gz
```

OR (Single URLS for the OpenReivew submission)

```bash
wget https://github.com/HallerPatrick/BabyLM-2024/blob/main/predictions.zip
unzip predictions.zip
```

# Model Weights

The models are available at HuggingFace:

* Strict-small Track: https://huggingface.co/PatrickHaller/hgrn2_pile_10m_distill_babylm
* Strict Track: https://huggingface.co/PatrickHaller/hgrn2_pile_100m_distill_babylm

To download and use these models, the [fla](https://github.com/sustcsonglin/flash-linear-attention) package has to be installed first:

```bash
pip install -U git+https://github.com/sustcsonglin/flash-linear-attention
```
